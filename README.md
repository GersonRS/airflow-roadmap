# Airflow Roadmap

![Airflow Roadmap](./Airflow%20Roadmap.svg)

```
Airflow Roadmap
├── Learn the Fundamentals
│   ├── Airflow UI
│   ├── Core Concepts
│   ├── Connections
│   ├── Variables
│   ├── Database
│   ├── Executor
│   └── Dependencies
├── Installation
│   ├── Local
│   ├── Container
│   ├── Cloud
│   └── Custom
├── Building
│   ├── Building images
│   ├── Extending the image
│   └── Customizing the image
├── Dags
│   ├── Params
│   ├── Task Lifecycle
│   ├── DAG Operator
│   ├── Pass data between tasks
│   ├── Data Sharing via XComs
│   ├── Task Flow API
│   ├── Catch-Up and Backfill
│   ├── Scheduler with Cron Expression
│   ├── Jinja templates
│   ├── Dynamic tasks
│   └── Task groups
├── Sensors and Hooks
│   ├── Custom hook
│   └── Custom Sensor
├── Advanced
│   ├── Best Practices
│   ├── Setting Configuration
│   ├── Airflow logging
│   ├── Isolated Environments
│   ├── Pools
│   ├── Sharing code between multiple projects
│   ├── Git sync
│   ├── Setup/ teardown tasks
│   ├── Plugins
│   ├── KubernetesPodOperator
│   ├── Airflow CLI
│   ├── Integration
│   └── Astro: SDK
└── Tests
    ├── DAG validation
    ├── Data or files for local testing
    ├── Debug interactively
    ├── Unit testing
    ├── Mocking
    └── Data quality checks
```

# Descrição dos topicos do roadmap

Descrições de cada um dos tópicos do roadmap do Airflow:

01. **Learn the Fundamentals**
    - **Airflow UI**: Explore a interface do usuário do Airflow para monitorar e gerenciar tarefas e fluxos de trabalho.
    - **Core Concepts**: Entenda os conceitos fundamentais do Airflow, como DAGs, Operators e Tasks.
    - **Connections**: Aprenda a configurar conexões com sistemas externos, como bancos de dados e serviços de nuvem.
    - **Variables**: Descubra como utilizar variáveis para armazenar e compartilhar informações entre tarefas.
    - **Database**: Explore a configuração e utilização de bancos de dados para armazenar metadados e estado das tarefas.
    - **Executor**: Entenda os diferentes executores disponíveis no Airflow e como escolher o mais adequado para o seu ambiente.
    - **Dependencies**: Aprenda sobre as dependências entre tarefas e como o Airflow gerencia a execução em paralelo.

02. **Installation**
    - **Local**: Instale o Airflow em um ambiente local para desenvolvimento e teste.
    - **Container**: Explore opções para executar o Airflow em contêineres, facilitando a implantação e escalabilidade.
    - **Cloud**: Descubra como instalar o Airflow em serviços de nuvem como AWS, Google Cloud e Azure.
    - **Custom**: Aprenda a personalizar a instalação do Airflow para atender às necessidades específicas do seu ambiente.

03. **Building**
    - **Building images**: Crie imagens Docker personalizadas para executar o Airflow.
    - **Extending the image**: Estenda as imagens padrão do Airflow para incluir bibliotecas e dependências adicionais.
    - **Customizing the image**: Personalize as imagens do Airflow com configurações específicas do seu ambiente.

04. **DAGs**
    - **Params**: Utilize parâmetros para tornar seus DAGs mais flexíveis e reutilizáveis.
    - **Task Lifecycle**: Entenda o ciclo de vida das tarefas no Airflow, desde o agendamento até a conclusão.
    - **DAG Operator**: Explore diferentes tipos de operadores para definir tarefas dentro de um DAG.
    - **Pass data between tasks**: Aprenda a passar dados entre tarefas usando XComs.
    - **Data Sharing via XComs**: Compartilhe dados entre tarefas de forma eficiente utilizando XComs.
    - **Task Flow API**: Utilize a Task Flow API para definir fluxos de trabalho complexos dentro dos seus DAGs.
    - **Catch-Up and Backfill**: Saiba como lidar com a execução retroativa de tarefas e backfilling de dados.
    - **Scheduler with Cron Expression**: Agende a execução de DAGs usando expressões de cron.
    - **Jinja templates**: Aprenda a utilizar templates Jinja para parametrizar suas DAGs de forma dinâmica.
    - **Dynamic tasks**: Crie tarefas dinâmicas que se adaptam a diferentes cenários de execução.
    - **Task groups**: Agrupe tarefas relacionadas em grupos para facilitar o gerenciamento e a manutenção dos DAGs.

05. **Sensors and Hooks**
    - **Custom hook**: Implemente hooks personalizados para interagir com sistemas externos.
    - **Custom Sensor**: Desenvolva sensores personalizados para monitorar condições de espera antes da execução de tarefas.

06. **Advanced**
    - **Best Practices**: Explore as melhores práticas para desenvolver e gerenciar DAGs no Airflow.
    - **Setting Configuration**: Configure o Airflow para atender às necessidades específicas do seu ambiente.
    - **Airflow logging**: Entenda como o Airflow registra informações sobre a execução de tarefas e fluxos de trabalho.
    - **Isolated Environments**: Implemente ambientes isolados para execução de DAGs, garantindo a integridade e segurança do sistema.
    - **Pools**: Gerencie recursos compartilhados entre tarefas usando pools no Airflow.
    - **Sharing code between multiple projects**: Compartilhe código entre projetos do Airflow para promover a reutilização e a consistência.
    - **Git sync**: Sincronize seus DAGs com repositórios Git para facilitar o gerenciamento de versões.
    - **Setup/ teardown tasks**: Defina tarefas de configuração e limpeza para preparar e finalizar ambientes de execução.
    - **Plugins**: Desenvolva e utilize plugins para estender a funcionalidade do Airflow.
    - **KubernetesPodOperator**: Execute tarefas em pods do Kubernetes utilizando o KubernetesPodOperator.
    - **Airflow CLI**: Utilize a linha de comando do Airflow para realizar tarefas administrativas e operacionais.
    - **Integration**: Integre o Airflow com outras ferramentas e sistemas para criar pipelines de dados robustos.
    - **Astro: SDK**: Explore o SDK Astro para desenvolver e gerenciar DAGs de forma programática.

07. **Tests**
    - **DAG validation**: Valide a estrutura e configuração dos seus DAGs para garantir a consistência e correção.
    - **Data or files for local testing**: Prepare dados e arquivos para testes locais de seus DAGs e tarefas.
    - **Debug interactively**: Depure e teste suas DAGs interativamente para identificar e corrigir problemas.
    - **Unit testing**: Escreva testes unitários para garantir o comportamento correto das suas tarefas.
    - **Mocking**: Utilize mocks para simular o comportamento de componentes externos durante os testes.
    - **Data quality checks**: Implemente verificações de qualidade de dados para garantir a integridade e consistência dos dados processados pelo Airflow.
# Detalhe das Aulas

A descrições das aula abaixo, contemplam um ou mais topicos abordados no roadmap.

01. **Introdução ao Airflow**: Uma visão geral do que é o Airflow e como ele pode ser usado para orquestrar fluxos de trabalho de dados, componentes fundamentais do Airflow, incluindo o MetaStore, Scheduler, Executor, Worker, Web Server e Banco de Dados, entendendo o papel de cada um na execução de DAGs.

02. **Conceitos Fundamentais do Airflow**: Uma explicação dos conceitos básicos do Airflow, incluindo DAGs, Operators e Tasks.

03. **Explorando a Interface do Usuário do Airflow**: Uma análise detalhada da interface do usuário do Airflow para monitorar e gerenciar DAGs e tarefas.

04. **Configurando Conexões no Airflow**: Como configurar conexões com sistemas externos, como bancos de dados e serviços de nuvem.

05. **Utilizando Variáveis no Airflow**: Aprenda a usar variáveis para armazenar e compartilhar informações entre tarefas no Airflow.

06. **Trabalhando com Banco de Dados no Airflow**: Como configurar e usar bancos de dados no Airflow para armazenar metadados e estado das tarefas.

07. **Entendendo os Diferentes Executores no Airflow**: Uma explicação dos diferentes executores disponíveis no Airflow e como escolher o mais adequado para o seu ambiente.

08. **Gerenciando Dependências entre Tarefas no Airflow**: Uma análise sobre como o Airflow gerencia as dependências entre tarefas em um fluxo de trabalho.

09. **Instalação Local do Airflow**: Passos detalhados para instalar o Airflow em um ambiente local para desenvolvimento e teste.

10. **Implantando o Airflow em Contêineres**: Como implantar o Airflow em contêineres para facilitar a escalabilidade e a implantação.

11. **Instalando o Airflow na Nuvem**: Guia passo a passo para instalar o Airflow em serviços de nuvem como AWS, Google Cloud e Azure.

12. **Personalizando a Instalação do Airflow**: Aprenda a personalizar a instalação do Airflow para atender às necessidades específicas do seu ambiente.

13. **Criando Imagens Docker Personalizadas para o Airflow**: Como criar e personalizar imagens Docker para executar o Airflow.

14. **Estendendo Imagens do Airflow**: Expanda as imagens padrão do Airflow para incluir bibliotecas e dependências adicionais.

15. **Personalizando Imagens do Airflow**: Personalize as imagens do Airflow com configurações específicas do seu ambiente.

16. **Utilizando Parâmetros em DAGs do Airflow**: Aprenda a usar parâmetros para tornar seus DAGs mais flexíveis e reutilizáveis.

17. **Ciclo de Vida das Tarefas no Airflow**: Entenda o ciclo de vida das tarefas no Airflow, desde o agendamento até a conclusão.

18. **Definindo Tarefas com o Operador DAG no Airflow**: Como definir tarefas dentro de um DAG usando o operador DAG no Airflow.

19. **Passando Dados entre Tarefas no Airflow**: Aprenda a passar dados entre tarefas no Airflow.

20. **Compartilhando Dados entre Tarefas no Airflow com XCom**: Utilize XComs para compartilhar dados entre tarefas de forma eficiente no Airflow.

21. **Utilizando a API Task Flow no Airflow**: Como utilizar a API Task Flow para definir fluxos de trabalho complexos dentro dos seus DAGs no Airflow.

22. **Execução Retroativa e Backfill no Airflow**: Saiba como lidar com a execução retroativa de tarefas e backfilling de dados no Airflow.

23. **Agendamento de Tarefas com Expressões de Cron no Airflow**: Agende a execução de DAGs no Airflow usando expressões de cron.

24. **Utilizando Templates Jinja no Airflow**: Aprenda a utilizar templates Jinja para parametrizar suas DAGs de forma dinâmica no Airflow.

25. **Criando Tarefas Dinâmicas no Airflow**: Crie tarefas dinâmicas que se adaptam a diferentes cenários de execução no Airflow.

26. **Agrupando Tarefas no Airflow**: Agrupe tarefas relacionadas em grupos para facilitar o gerenciamento e a manutenção dos DAGs no Airflow.

27. **Desenvolvendo Hooks Personalizados no Airflow**: Implemente hooks personalizados para interagir com sistemas externos no Airflow.

28. **Criando Sensores Personalizados no Airflow**: Desenvolva sensores personalizados para monitorar condições de espera antes da execução de tarefas no Airflow.

29. **Melhores Práticas de Desenvolvimento no Airflow**: Explore as melhores práticas para desenvolver e gerenciar DAGs no Airflow.

30. **Configuração do Airflow**: Configure o Airflow para atender às necessidades específicas do seu ambiente.

31. **Logging no Airflow**: Entenda como o Airflow registra informações sobre a execução de tarefas e fluxos de trabalho.

32. **Ambientes Isolados no Airflow**: Implemente ambientes isolados para execução de DAGs, garantindo a integridade e segurança do sistema no Airflow.

33. **Gerenciamento de Recursos com Pools no Airflow**: Gerencie recursos compartilhados entre tarefas usando pools no Airflow.

34. **Compartilhando Código entre Projetos no Airflow**: Compartilhe código entre projetos do Airflow para promover a reutilização e a consistência.

35. **Sincronização com Git no Airflow**: Sincronize seus DAGs com repositórios Git para facilitar o gerenciamento de versões no Airflow.

36. **Configurando e Finalizando Tarefas no Airflow**: Defina tarefas de configuração e limpeza para preparar e finalizar ambientes de execução no Airflow.

37. **Desenvolvimento de Plugins no Airflow**: Desenvolva e utilize plugins para estender a funcionalidade do Airflow.

38. **Executando Tarefas em Pods do Kubernetes no Airflow**: Utilize o KubernetesPodOperator para executar tarefas em pods do Kubernetes no Airflow.

39. **Utilizando a Linha de Comando do Airflow**: Explore a linha de comando do Airflow para realizar tarefas administrativas e operacionais.

40. **Integração do Airflow com Outras Ferramentas**: Integre o Airflow com outras ferramentas e sistemas para criar pipelines de dados robustos.

41. **SDK Astro no Airflow**: Explore o SDK Astro para desenvolver e gerenciar DAGs de forma programática no Airflow.

42. **Validação de DAGs no Airflow**: Valide a estrutura e configuração dos seus DAGs para garantir a consistência e correção no Airflow.

43. **Preparação de Dados para Testes Locais no Airflow**: Prepare dados e arquivos para testes locais de seus DAGs e tarefas no Airflow.

44. **Depuração Interativa no Airflow**: Depure e teste suas DAGs interativamente para identificar e corrigir problemas no Airflow.

45. **Testes Unitários no Airflow**: Escreva testes unitários para garantir o comportamento correto das suas tarefas no Airflow.

46. **Simulação de Comportamento de Componentes Externos no Airflow**: Utilize mocks para simular o comportamento de componentes externos durante os testes no Airflow.

47. **Verificação de Qualidade de Dados no Airflow**: Implemente verificações de qualidade de dados para garantir a integridade e consistência dos dados processados pelo Airflow.

48. **Integração Contínua com Airflow**: Configure integração contínua para seus DAGs no Airflow.

49. **Implantação Contínua com Airflow**: Configure implantação contínua com argos para o Airflow.

50. **Escalabilidade e Tolerância a Falhas no Airflow**: Como garantir a escalabilidade e tolerância a falhas em ambientes de produção no Airflow.
