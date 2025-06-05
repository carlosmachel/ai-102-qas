**Pergunta 1:**    
O que é um agente de IA no contexto do kernel semântico?  
    
**Resposta:**    
Um agente de IA é um programa que usa IA generativa para interpretar dados, tomar decisões e executar tarefas em nome de usuários ou outros aplicativos, funcionando de forma autônoma para lidar com fluxos de trabalho complexos e automatizar processos.  
   
---  
   
**Pergunta 2:**    
Que ferramentas podem ser usadas para desenvolver agentes de IA, segundo o texto?  
   
**Resposta:**    
Podem ser usadas muitas ferramentas e plataformas diferentes, incluindo o SDK do Kernel Semântico, que é um SDK de código aberto para integrar modelos de IA em aplicações.  
   
---  
   
**Pergunta 3:**    
Quais são os componentes principais do kernel semântico?  
   
**Resposta:**    
Os componentes principais incluem: conectores de serviços de IA, conectores de memória, funções e plugins, modelos de prompt e filtros.  
   
---  
   
**Pergunta 4:**    
Qual o papel dos conectores de serviços de IA no kernel semântico?  
   
**Resposta:**    
Eles conectam o código a serviços de IA de diferentes provedores sob uma interface comum, suportando funcionalidades como conclusão de chat e geração de texto.  
   
---  
   
**Pergunta 5:**    
O que fazem os filtros no kernel semântico?  
   
**Resposta:**    
Os filtros permitem executar ações personalizadas antes e depois da invocação de uma função ou prompt, atuando como camadas que envolvem essas chamadas para modificar ou controlar seu comportamento.  
   
---  
   
**Pergunta 6:**    
Que tipos de agentes a estrutura do agente do Semantic Kernel suporta?  
   
**Resposta:**    
Suporta diferentes tipos de agentes, incluindo ChatCompletionAgent, OpenAIAssistantAgent e AzureAIAgent.  
   
---  
   
**Pergunta 7:**    
O que é o AzureAIAgent?  
   
**Resposta:**    
É uma classe dentro do Semantic Kernel que facilita a criação e interação com agentes de IA usando o Foundry Agent Service da Azure, abstraindo a complexidade do gerenciamento e integrando funcionalidades como chamadas automáticas a ferramentas e gerenciamento de conversas.  
   
---  
   
**Pergunta 8:**    
Quais são os benefícios principais da classe AzureAIAgent?  
   
**Resposta:**    
Incluem criação simplificada de agentes com configuração mínima, invocação automática de ferramentas (como Azure AI Search e Azure Functions), gerenciamento interno de threads e conversas, e integração segura e compatível com autenticação sem chave.  
   
---  
   
**Pergunta 9:**    
O que são “threads do agente” na estrutura do agente?  
   
**Resposta:**    
Threads do agente gerenciam o estado da conversa e armazenam as conversas para manter a continuidade e contexto das interações.  
   
---  
   
**Pergunta 10:**    
Como a estrutura do agente gerencia as interações entre vários agentes?  
   
**Resposta:**    
Por meio do recurso Chat do agente, que possibilita conversas estruturadas e colaboração entre múltiplos agentes.  
   
---  
   
**Pergunta 11:**    
Para que serve o canal do agente?  
   
**Resposta:**    
O canal do agente é usado para o desenvolvimento de agentes personalizados e permite que diferentes tipos de agentes participem do AgentChat.  
   
---  
   
**Pergunta 12:**    
Como as funções e plug-ins estendem os recursos dos agentes?  
   
**Resposta:**    
Eles permitem que os desenvolvedores incorporem funções personalizadas, estendendo as capacidades dos agentes a partir da estrutura básica.  
   
---  
   
**Pergunta 13:**    
De que forma a estrutura do agente do Kernel Semântico suporta soluções multiagentes?  
   
**Resposta:**    
Ela mantém a consistência com o design do Kernel Semântico, permitindo a criação de comportamentos autônomos e a colaboração entre múltiplos agentes, facilitando sistemas de IA inteligentes e adaptáveis.  
   
---  
   
**Pergunta 14:**    
Qual componente do kernel semântico permite combinar instruções, entrada do usuário e saídas de função em um formato reutilizável?    
a) Conectores de memória    
b) Modelos de prompt    
c) Filtros    
d) Plugins  
   
**Resposta:**    
b) Modelos de prompt  
   
---  
   
**Pergunta 15:**    
O que a classe AzureAIAgent abstrai para o desenvolvedor?    
a) Gerenciamento manual dos modelos de linguagem    
b) Complexidade do gerenciamento de infraestrutura e agentes    
c) Criação de interfaces gráficas para usuários    
d) Implantação em servidores locais  
   
**Resposta:**    
b) Complexidade do gerenciamento de infraestrutura e agentes  
   
---  
   
**Pergunta 16:**    
Como os threads do agente contribuem para o funcionamento dos agentes?    
a) Realizam a autenticação dos usuários    
b) Monitoram uso de memória dos agentes    
c) Gerenciam o estado da conversa e armazenam histórico    
d) Controlam a execução das APIs externas  
   
**Resposta:**    
c) Gerenciam o estado da conversa e armazenam histórico  
   
---  
   
**Pergunta 17:**    
Quais serviços o AzureAIAgent pode invocar automaticamente para estender suas funcionalidades?    
a) Azure AI Search, Bing, Azure Functions    
b) GitHub, Docker    
c) Google Drive, Dropbox    
d) Slack, Telegram  
   
**Resposta:**    
a) Azure AI Search, Bing, Azure Functions  
   
---  
   
**Pergunta 18:**    
Em que cenário o recurso GroupChat do Semantic Kernel seria mais útil?    
a) Para criar uma interface gráfica amigável    
b) Para orquestrar a comunicação e colaboração entre múltiplos agentes    
c) Para armazenar dados em bancos relacionais    
d) Para treinar novos modelos de linguagem  
   
**Resposta:**    
b) Para orquestrar a comunicação e colaboração entre múltiplos agentes  
   
---  
   
**Pergunta 19:**    
Qual é a principal vantagem do uso de conectores de serviços de IA?    
a) Permitir a criação de interfaces customizadas    
b) Conectar o código a diferentes provedores sob uma única interface comum    
c) Eliminar a necessidade de programação    
d) Gerenciar o armazenamento de dados  
   
**Resposta:**    
b) Conectar o código a diferentes provedores sob uma única interface comum  
   
---  


### 1. What is the question answering capability in Azure AI Language?

The question answering capability in Azure AI Language enables you to define a knowledge base of question and answer pairs that can be queried using natural language input.  
This knowledge base can be published to a REST endpoint and consumed by client applications, such as bots.

---

### 2. What sources can be used to create a knowledge base for question answering?

You can create a knowledge base from various sources, including:
- Websites containing frequently asked question (FAQ) documentation.
- Files with structured text, such as brochures or user guides.
- Built-in chit chat question and answer pairs that encapsulate common conversational exchanges.

---

### 3. How can client applications interact with the question answering knowledge base?

Once the knowledge base is published to a REST endpoint, client applications, such as bots, can send natural language queries to this endpoint and receive appropriate answers based on the defined question and answer pairs.

---

### 4. How does the question answering capability in Azure AI Language relate to the previous QnA Maker service?

The question answering capability in Azure AI Language is a newer version of the QnA Maker service.  
While QnA Maker still exists as a standalone service, Azure AI Language offers enhanced features and integration.  
For migrating a QnA Maker knowledge base to Azure AI Language, refer to the migration guide provided by Microsoft.

---

### 1. What is the primary difference between question answering and language understanding in Azure AI Language?

**Answer:**  
The primary difference lies in their usage patterns:  
- **Question answering** is designed for scenarios where a user submits a question and expects a specific answer. It uses natural language understanding to match the question to an answer in a predefined knowledge base.  
- **Language understanding** is geared towards interpreting user utterances to determine the user's intent and extract relevant entities, enabling the application to perform appropriate actions based on this interpretation.

---

### 2. How does query processing differ between question answering and language understanding?

**Answer:**  
- **Question answering** processes the user's question by matching it to the most relevant answer in the knowledge base using natural language understanding techniques.  
- **Language understanding** analyzes the user's utterance to identify the intended action (intent) and any pertinent information (entities) required to execute that action.

---

### 3. What type of response does each service provide?

**Answer:**  
- **Question answering** provides a static answer retrieved from the knowledge base that directly addresses the user's question.  
- **Language understanding** returns the identified intent and any extracted entities, leaving it to the client application to determine and perform the appropriate response or action.

---

### 4. How does the client application's role differ when using question answering versus language understanding?

**Answer:**  
- With **question answering**, the client application typically presents the retrieved answer directly to the user.  
- With **language understanding**, the client application interprets the identified intent and entities to decide on and execute the appropriate action or response.

---

### 5. Can question answering and language understanding be used together?

**Answer:**  
Yes, they are complementary services.  
By combining language understanding models and question answering knowledge bases, developers can build comprehensive natural language solutions that handle both intent-driven actions and provide specific answers to user questions.

---

