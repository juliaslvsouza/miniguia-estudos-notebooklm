- O tópico escolhido foi Modelagem de Sistemas Orientados a Objetos. O objetivo é que eu consiga estudar, revisar e testar o conhecimento para a prova que terei a respeito desta matéria da faculdade.
- As fontes utilizadas foram conteúdos disponibilizados pela própria professora da faculdade que leciona esta matéria - 12 anexos, entre arquivos de texto e fotos.

  RESUMOS:
- O que é a modelagem? Modelagem em Sistemas de Informação é a atividade de construir modelos que expliquem as características físicas, estruturais e funcionais, além dos comportamentos de um sistema. Um modelo é a representação abstrata de algo que se deseja produzir ou construir. Essa prática é essencial nos projetos pois ajuda a equipe de desenvolvimento a organizar a arquitetura do software para garantir que o sistema atenda aos requisitos do cliente, além de facilitar a comunicação do time, documentar as decisões tomadas, mitigar riscos e auxiliar na futura evolução e manutenção do sistema.

- O que é abstração? A abstração é o processo de observar o cenário do mundo real para identificar características e comportamentos semelhantes em um conjunto de objetos, filtrando e selecionando apenas aquilo que é relevante para o propósito e o domínio do sistema. Ela funciona como um filtro inicial, permitindo que você ignore a complexidade técnica para enxergar os serviços fundamentais do software e, no caso da orientação a objetos, identificar a Classe, que é o principal elemento que representa essa categoria de objetos abstraída.

- Quais os fundamentos da modelagem de sistemas orientados a objeto? Os fundamentos do paradigma de orientação a objetos sustentam-se em conceitos estruturais importantes:
- Classes e Instanciação: A classe é um molde abstrato e genérico que define a estrutura de um conjunto de objetos semelhantes. A instanciação é o ato de criar um objeto real na memória a partir dessa classe, sendo que cada objeto (instância) terá seus próprios valores independentes.
- Atributos e Métodos: Toda classe mapeia atributos (que armazenam os dados, estado e propriedades do objeto) e métodos (que representam os comportamentos, operações e ações que o objeto pode realizar).
 - Herança (Generalização/Especialização): Mecanismo onde classes mais específicas (subclasses) derivam e herdam as características e métodos de uma classe genérica (superclasse).
 - Polimorfismo: Decorrente da herança, permite que dois ou mais métodos possuam o mesmo nome (assinatura), mas se comportem e sejam implementados de forma diferente dependendo da classe especializada que os invoca.
 - Encapsulamento: Conceito que atua na proteção dos dados, frequentemente implementado através da definição de visibilidades (público, protegido, privado) para definir o que pode ser acessado por outras classes.
   
- O que é e como funciona o diagrama de caso de uso? O diagrama de caso de uso é um "diagrama de contexto" que apresenta, em alto nível de abstração, uma visão geral das funcionalidades que um sistema vai oferecer, delimitando sua fronteira. Seu foco principal é demonstrar de forma gráfica o que o sistema deve fazer, mas sem se preocupar em detalhar como isso será programado. Ele funciona mapeando a interação através de componentes simples:
 - Atores: Elementos externos (podem ser pessoas, equipamentos ou outros sistemas) que assumem um papel e interagem com o sistema para atingir um objetivo.
 - Casos de Uso: Representados por elipses, são as funcionalidades em si ou os serviços solicitados pelos atores.
 - Relacionamentos: Linhas que conectam esses elementos, podendo ser de Associação (comunicação direta entre ator e função), Inclusão (quando um caso de uso exige obrigatoriamente a execução de outro), Extensão (um comportamento opcional ou de variação que ocorre sob certas circunstâncias) e Generalização (herança entre atores ou casos de uso).

- O que é e como funciona o diagrama de classes? É o diagrama central e mais importante da modelagem orientada a objetos (UML), responsável por fornecer uma visão estática da estrutura lógica do sistema. Ele visualiza quais entidades irão compor a aplicação e como elas se conectam. Ele funciona detalhando as partes técnicas e estruturais:
 - Classes: São representadas por retângulos divididos em três blocos: o nome da classe, os seus atributos (dados) e os seus métodos (ações).
 - Relacionamentos: Demonstram a colaboração entre as classes para executar as funções. Eles indicam navegabilidade e multiplicidade (quantos elementos se ligam a quantos), e se dividem em Associação (conexão semântica para troca de mensagens), Agregação (relação "todo-parte" fraca, onde as partes podem existir sozinhas), Composição (relação "todo-parte" forte, onde as partes morrem se o todo for destruído), Generalização (herança) e Dependência (quando a mudança em uma classe afeta diretamente a outra).
   
- Qual a estrutura da documentação do diagrama de classe x do diagrama de caso de uso? A forma de documentar esses diagramas reflete seus diferentes propósitos práticos:
 - Documentação do Diagrama de Casos de Uso: É baseada em um documento textual e narrativo, redigido em linguagem simples, voltado para detalhar o passo a passo da interação entre o ator e o sistema. Ela pode ser classificada como informal, típica ou detalhada. Sua estrutura detalhada contempla: Nome da funcionalidade, Atores principais e secundários, Pré-condições (o que o sistema exige antes de começar), Pós-condições (estado final após o sucesso), o Cenário Principal (o fluxo ou "caminho feliz" das ações), os Fluxos Alternativos e Exceções (erros ou variações), além de incluir Estruturas de Dados e Regras de Negócio que balizam aquela função.
 - Documentação (Estrutura) do Diagrama de Classes: A documentação do diagrama de classes é inerentemente visual, estrutural e técnica. Em vez de textos narrativos, a estrutura de documentação desse diagrama dita regras rígidas de modelagem de software em seus blocos: os nomes precisam seguir vocabulário do domínio, os atributos devem ter o tipo de dado documentado (ex: int, String, double), os métodos exigem a declaração de suas assinaturas (tipos de parâmetros recebidos e valores de retorno). Adicionalmente, toda a estrutura aplica sinalizações matemáticas e de visibilidade lógicas (+ público, # protegido, - privado) e regras de multiplicidade (como *0..1, 1..**), definindo tecnicamente como o código-fonte deve ser implementado no futuro.

  
  GLOSSÁRIO:
- Abstração: Processo em que se procura encontrar características semelhantes em um conjunto de objetos do mundo real para identificar o principal elemento da orientação a objetos: a Classe.
- Engenharia de Requisitos: Subárea da engenharia de software focada no processo de definição (elicitação, modelagem e análise) de requisitos.
- Modelo: É a representação de algo que se deseja produzir ou construir, fornecendo visões de um sistema físico em um nível apropriado de detalhe.
- Modelagem de Sistemas: É a atividade de construir modelos que expliquem as características físicas, estruturais ou funcionais e os comportamentos de um sistema, auxiliando a equipe a organizar a arquitetura do software.
- Projeto: Esforço temporário com recursos delimitados, que tem como finalidade um resultado único.
- Requisitos Funcionais: São as ações que o stakeholder deseja que o sistema realize, ou seja, representam diretamente as funcionalidades do software.
- Requisitos Não Funcionais: São restrições impostas ao sistema, correspondendo a limitações, condições, consistências e validações de infraestrutura ou negócio que devem ser aplicadas sobre as funcionalidades.
- Stakeholder: Usuário que tem interesse no novo software e possui conhecimento sobre como a informação do negócio é gerida e modificada.
- Agregação: Tipo especial de associação estrutural de relacionamento "todo-parte" classificado como fraco, pois o tempo de vida do objeto "parte" não depende exclusivamente e unicamente do tempo de vida do objeto "todo" (ele pode fazer parte de vários objetos "todo").
- Associação: Conexão semântica (estrutural) que permite que classes ou atores troquem mensagens a fim de compartilhar informações e colaborar para a execução de funcionalidades.
- Atributos: Também chamados de propriedades, são as características que identificam um objeto e armazenam seus dados informativos e estado.
- Classe: Representação visual (molde) no domínio do problema de um conjunto de objetos abstraídos do mundo real que possuem a mesma estrutura e comportamento.
- Composição: Uma variação semântica mais forte da agregação, onde o objeto "parte" pertence a um único objeto "todo", possuindo o tempo de vida coincidente com ele (se o todo morre, as partes também morrem).
- Diagrama de Classes: Fornece a visão estática da organização técnica do sistema, permitindo a visualização estrutural e lógica das classes que irão compor a aplicação.
- Instanciação (e Objetos): Instanciação é a criação em si de um objeto a partir do molde de uma classe. Os objetos criados carregam as mesmas estruturas da classe, mas cada um possui seus próprios valores independentes.
- Generalização: Relacionamento de herança indicando que uma classe ou ator "é um tipo de" outro. Ocorre entre itens gerais (superclasses ou pais) e itens mais específicos (subclasses ou filhos), onde os filhos herdam todo o significado e comportamento dos pais.
- Métodos: Representam o conjunto de operações, funções ou comportamentos que um objeto daquela classe tem a capacidade de executar.
- Multiplicidade: Indicador de regra de negócio que define exatamente quantos objetos de uma classe podem se relacionar a um objeto posicionado na classe da outra extremidade da associação.
- Ator: Elementos externos ao sistema (como usuários humanos, equipamentos de hardware ou outros sistemas) que interagem com o software e desempenham papéis durante a execução das funcionalidades. Podem ser Atores Principais (iniciam a interação) ou Atores Secundários (participam como coadjuvantes).
- Casos de Uso: Representam de fato as funções, tarefas ou serviços baseados nos requisitos funcionais que são disponibilizados para os atores. Segundo Jacobson, também é o "documento narrativo que descreve a sequência de eventos de um ator".
- Cenário Principal: Parte da documentação textual que descreve o fluxo normal e exato de execução do caso de uso (o chamado "caminho feliz").
- Diagrama de Casos de Uso: Diagrama de contexto que delimita a fronteira do sistema para apresentar, em alto nível de abstração, a visão geral do que o sistema faz e como os atores externos interagem com essas funções (sem especificar como isso deve ser feito).
- Extensão (<<extend>>): Relacionamento de dependência que descreve uma variação opcional do comportamento de um caso de uso base. Separa as partes obrigatórias das opcionais, pois o caso estendido só será executado sob certas circunstâncias.
- Fronteira do Sistema: Elemento delimitador que define visualmente a área de atuação do software, separando o que faz parte do sistema (interno) do que interage com ele (externo/atores).
- Inclusão (<<include>>): Relacionamento de dependência que indica uma obrigatoriedade. Utilizado para evitar repetição ao isolar/fatorar uma atividade que é comum a dois ou mais casos de uso, obrigando que o caso base execute também o caso incluído.
- Pré-condições: Condições ou estados obrigatórios que devem estar previamente atendidos pelo sistema para que um determinado caso de uso possa começar a ser executado.
- Pós-condições: Condição ou novo estado em que o sistema deve ficar logo após o caso de uso ter sido executado e concluído com sucesso.

  CONJUNTO DE PROMPTS REUTILIZÁVEIS:
  - Crie 3 perguntas rápidas do tipo "Verdadeiro ou Falso" sobre 'diagrama de classes' baseando-se nos textos. Coloque o gabarito no final. (Trocar o tema entre '' para o que quiser revisar).
  - Qual é a diferença exata entre 'ator principal' e 'ator secundário'? (Trocar informações entre '' para os conceitos que quiser revisar).
  - Faça um resumo em tópicos sobre 'os elementos essenciais para documentar um caso de uso' utilizando apenas as informações dos documentos. (Trocar informações entre '' para os conceitos que quiser revisar).
  - Explique de forma simples o que é 'relacionamento de extensão' e dê um exemplo prático citado no texto. (Trocar informações entre '' para os conceitos que quiser revisar).
