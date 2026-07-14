# 🤖 Explicação sobre o Bootcamp AWS AI Agents

## 📖 Sobre o bootcamp
Este repositório reúne os estudos e aprendizados durante o evento "Bootcamp AWS - Agentes de IA em Campo" promovido pela DIO em parceiria com a AWS.
O curso mostra os principais conceitos de IA Generativa e demonstra como criar agentes inteligentes utilizando os serviços da AWS (Amazon Bedrock, além das ferramentas como Amazon Nova, AgentCore e Step Functions).

## ☁️ O que aprendi?
### O que é IA Generativa
É uma evolução dos modelos de Machine Learning, ela possui capacidade de produzir novos conteúdos, como:
* Textos;
* Imagens;
* Códigos;
* Documentos;
* Respostas contextualizadas;
* Análises.

Tudo graças ao Large Language Models (LLMs), modelos treinados com enormes volumes de dados que aprendedm padrões da linguagem humana.
Em minha experiência já configurei e fiz integrações com o Copilot Studio, o estudo do AWS agregou ao meu conhecimento.

### 🤖 Amazon Bedrock
-> Um dos principais serviços apresentados durante o bootcamp.
Ele funciona como uma plataforma que reúne diversos modelos fundacionais (Foundation Models) em um único ambiente, disponibilizando APIs prontas para consumo.
Suas principais vantagens estão:
* Ambiente totalmente gerenciado pela AWS;
* Integração simples através de APIs;
* Suporte para diferentes modelos de IA;
* Segurança corporativa;
* Escalabilidade automática;
* Facilidade para criar aplicações com IA Generativa.

### ⚙️ Foundation Models
São modelos extremamente grandes, treinados previamente em enormes bases de dados. Executam tarefas como:
* Responder perguntas;
* Resumem textos;
* Traduz idiomas;
* Geram código;
* Interpretam documentos;
* Produzem conteúdos criativos.

Ao utilizar o Amazon Bedrock, não é necessário construir esses modelos do zero, apenas enviar prompts adequados para obter os resultados.

### 📚 Engenharia de Prompt
A qualidade da resposta depende diretamente da qualidade do prompt, que deve possuir um bom contexto, com objetivos claros, com restrições definidas, um formato esperado da resposta e exemplos quando for necessário.
Pequenas mudanças na forma de escrever uma instrução podem alterar completamente a qualidade da resposta produzida pela IA.

### 📚 Agentes Inteligentes
| Chatbot != Agente 

Um chatbot normalmente responde perguntas. O agente consegue:
* Interpretar objetivos;
* Planejar etapas;
* Utilizar ferramentas;
* Acessar APIs;
* Consultar bancos de dados;
* Executar ações;
* Retornar resultados.

### ⚙️ Amazon Nova
Esses modelos fazem parte de uma estratégia recente da AWS para disponibilizar modelos próprios de IA Generativa. Eles foram desenvolvidos para oferecer:
* Alta velocidade;
* Menor custo;
* Boa qualidade de resposta;
* Integração nativa com o Bedrock.

Escolher o modelo certo influencia diretamente no desempenho e custo da solução.

### ⚙️ AgentCore
O objetivo é facilitar a construção de agentes capazes de executar fluxos completos de trabalho. Sendo assim, ao invés de apenas responder perguntas, um agente pode:
* Interpretar solicitações;
* Decidir qual ação executar;
* Chamar ferramentas externas;
* Manter contexto;
* Entregar respostas mais inteligentes.

### ⚙️ AWS Step Functions
Esse serviço permite criar fluxos de execução utilizando estados, etapas e decisões. Com ele é possível orquestrar processos inteiros sem precisar escrever toda a lógica manualmente. Algumas aplicações incluem:
* Automações;
* Processamento de documentos;
* Integração entre serviços;
* Execução de agentes;
* Workflows empresariais.

### 📚 Arquitetura Serverless
Nesse modelo, não é necessário administrar servidores diretamente. O AWS fica responsável pelo provisionamento, escalabilidade, disponibilidade e manutenção da infraestrutura. Dessa forma, o desenvolvedor foca apenas na lógica de negócio.

### 📚 Integração entre serviços
O agente dificilmente trabalha sozinho, na prática ele pode se integrar com diversos serviços da AWS, como:
* Amazon Bedrock;
* AWS Lambda;
* Step Functions;
* Amazon S3;
* Amazon DynamoDB;
* APIs externas.

### 📚 Casos de uso
Durante o bootcamp foram apresentados exemplos de aplicações utilizando agentes de IA, como:
* Assistentes virtuais;
* Atendimento automatizado;
* Análise de documentos;
* Recomendações inteligentes;
* Automação de processos;
* Análise de dados;
* Geração automática de conteúdo.

## 💡 Conclusão
Esse bootcamp ampliou bastante minha visão sobre IA Generativa e principalmente sobre o ecossistema da AWS.
Após o curso, consegui enxergar oportunidades de aplicar agentes de IA em processos corporativos, principalmente na automação de atividades repetitivas, interpretação de documentos, apoio à homologação de sistemas, geração automática de evidências de testes e assistência na análise de dados. Como já atuo com automações utilizando Power Automate e ferramentas Microsoft, vejo a integração entre esses recursos e os serviços da AWS como um caminho promissor para construir soluções mais inteligentes e escaláveis.


