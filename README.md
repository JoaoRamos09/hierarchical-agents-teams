# **Hierarchical Teams Agents: Organização em Times com Hierarquia**

## Descrição

Este projeto explora a arquitetura de "Hierarchical Teams Agents", onde agentes são organizados em diferentes times com uma hierarquia definida, colaborando para alcançar objetivos complexos. Os times de agentes possuem funções específicas, trabalhando de maneira coordenada e supervisionada por um agente roteador. Essa estrutura hierárquica proporciona maior eficiência na execução de tarefas complexas, com cada time se especializando em diferentes etapas do processo. 

O projeto é dividido em dois principais times: o **WriterTeam** e o **ResearchTeam**, cada um com um conjunto específico de ferramentas. Um agente supervisor roteador gerencia a interação e coordenação entre os times, garantindo um fluxo de trabalho otimizado.

Este exemplo foi inspirado no modelo `hierarchical-teams-agents` apresentado na documentação oficial do LangGraph.

## Organização dos Times

### **Tools WriterTeam**

O **WriterTeam** é responsável pela criação e edição de documentos, trabalhando com ferramentas especializadas para cada etapa do processo. As ferramentas disponíveis incluem:

- **`create_outline`**: Criação de esboços para documentos, definindo a estrutura básica.
- **`read_document`**: Leitura de documentos existentes, facilitando a integração e revisão de informações.
- **`write_document`**: Criação e salvamento de documentos em arquivos específicos.
- **`edit_document`**: Edição de documentos existentes, permitindo ajustes e melhorias.
- **`python_repl`**: Gerador de gráficos para enriquecer documentos com visualizações.

### **Tools ResearchTeam**

O **ResearchTeam** é focado em pesquisa e coleta de informações na internet. Suas ferramentas são:

- **`scrape_webpages`**: Raspagem de páginas web para encontrar dados relevantes.
- **`tavily_tool`**: Realização de buscas online para obter informações precisas e atualizadas.

### **Agente Supervisor Roteador**

Um agente supervisor roteador é responsável pelo gerenciamento do fluxo de trabalho entre os times, roteando tarefas para o time mais adequado conforme o progresso das atividades. Esse agente garante que a colaboração seja eficiente e que cada etapa do processo seja concluída corretamente.

## Funcionalidades Principais

- **Hierarquia e Coordenação**: Os times trabalham de maneira hierárquica, com funções especializadas e coordenação supervisionada.
- **Criação e Edição de Documentos**: O **WriterTeam** é responsável por esboçar, criar, editar e finalizar documentos.
- **Pesquisa e Coleta de Dados**: O **ResearchTeam** realiza buscas online para fornecer informações precisas ao **WriterTeam**.
- **Gerenciamento de Fluxo de Trabalho**: O agente supervisor roteador garante a coordenação eficiente entre os times.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/hierarchical-teams-agents.git

2. Navegue até o diretório do projeto:
   ```bash
   cd hierarchical-teams-agents

3. Execute o notebook ou script, fornecendo uma tarefa para os times colaborarem.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorar o projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.