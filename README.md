<h1 align="center">📊 🎯 YOUTAN DASH 📈 📶</h1>
<h3 align="center">Repositório dedicado ao versionamento do projeto API do 5º semestre de Banco de Dados.</h3>

---
<br>

## 📌 Tópicos
- [👥 Membros](https://github.com/manolito-fatec/dashflow-2025-1?tab=readme-ov-file#-team-members)
- [📋 Requisitos](https://github.com/manolito-fatec/dashflow-2025-1?tab=readme-ov-file#-requisitos)
- [📈 Product Backlog](https://github.com/manolito-fatec/dashflow-2025-1?tab=readme-ov-file#-product-backlog)

---
<br>

# 👥 Team Members
|Nome|Função|LinkedIn|  
| -------- | -------- | -------- |
|**Paulo Arantes Machado**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b)|
|**Otavio Calderan Bruguel**|Scrum Master|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/otavio-calderan-578b48239)|
|**André Hideaki Wakugawa**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrewakugawa/)|
|**Beatriz Bonatto**|Desenvolvedora|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://br.linkedin.com/in/beatriz-bonatto-263530156)|
|**Cauê Vieira da Silva**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)|
|**Gabriel Bartolomeu Guska**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabiel-guska-5860a1271/)|
|**Gabriel de Souza Mota**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabriel-mota-4a0816a0/)|

---
<br>

# 📋 Requisitos

### 📌 Requisitos Funcionais
| **ID** | **Persona** | **Descrição** |
| :-------------: | :-------------: | ------------- |
|R1|Operador|Visualizar informações por meio dos indicadores e das quantidades de cards atribuídos. |
|R2|Operador|Visualizar informações com os indicadores e cards elaborados para determinados períodos.|
|R3|Operador|Visualizar informações por meio dos indicadores e dos cards finalizados em um determinado período. |
|R4|Operador|Visualizar informações por meio dos indicadores, conforme o status da tarefa (coluna do Kanban). |
|R5|Operador|Visualizar informações por meio dos indicadores, incluindo o tempo médio de execução de um card.|
|R6|Operador|Visualizar informações com os indicadores, quantidade de projetos que ele participa|
|R7|Gestor|Visualizar informações com os indicadores, quantidade de cards atribuídos.|
|R8|Gestor|Visualizar informações com os indicadores, cards por colaborador.|
|R9|Gestor|Visualizar informações com os indicadores, quantidade de cards criados por um período.|
|R10|Gestor|Visualizar informações com os indicadores, quantidade de cards finalizados em um período.|
|R11|Gestor|Visualizar informações com os indicadores, por status das tarefas(Coluna do Kanban).|
|R12|Gestor|Visualizar informações por meio de indicadores, destacando o tempo médio que os operadores levam para finalizar um card.|
|R13|Gestor|Visualizar informações com os indicadores, cards que foram feitos retrabalhos.|
|R14|Gestor|Visualizar informações com os indicadores, quantidade de issue por projetos.|
|R15|Gestor|Visualizar informações com os indicadores, quantidade de cards por tags.|
|R16|Admin|Visualizar informações com os indicadores, quantidade de cards criados por um período de tempo.|
|R17|Admin|Visualizar informações com os indicadores, quantidade de cards  finalizados em um período.|
|R18|Admin|Visualizar informações com os indicadores, quantidade de projetos.|
|R19|Admin|Visualizar informações com os indicadores, quantidade de issues.|
|R20|Admin|Visualizar informações com os indicadores, a quantidade de cards de todos os projetos.|
|R21|Admin|Visualizar informações como os indicadores, quem é o gestor do projeto.|
|R22|Operador|O operador deverá ser designado para a função ROLE_USER, assegurando que tenha acesso e permissões adequadas dentro do sistema para visualizar informações que lhe são exclusivamente pertinentes.|
|R23|Gestor|O gestor deverá ser designado à função ROLE_MANAGER, garantindo que tenha acesso e permissões adequadas no sistema para visualizar informações pertinentes ao projeto sob sua responsabilidade e a seus próprios dados.|
|R24|Admin|O Administrador terá a função ROLE_ADMIN, o que lhe permitirá acessar informações relacionadas a todos os projetos.|
|R25|Admin| Criar uma api para integração com outro sistema(trello,Jira).|
|R26|Admin,Gestor,Operador| A persona deverá ser capaz de exportar dados do Dashboard para um arquivo CSV.|

---
<br>

### 📝 Requisitos Não Funcionais

| **ID** | **Descrição** |
| :-------------: | ------------- |
|RNF1|Documentação API – Application Programming Interface|
|RNF2|Responsivo |
|RNF3|Manual do Usuário|
|RNF4|Modelagem de banco de dados |
|RNF5|Pipeline CI |
|RNF6|Deploy automático |
|RNF7|Testes automatizados |

---
<br>

# 📈 Product Backlog

| 🏅 Rank| 🔥 Prioridade| 📝 User Story| 🚀 Sprint| 🎯 Requisito do Parceiro|🚨 Estimativa
| :--------: | :--------: | -------- | :--------: | :--------: | :--------: |
|1|Alta|Eu, como operador, desejo visualizar a quantidade de cards atribuídos a mim e filtrar os cards dos meus projetos com base no período de criação e finalização, para acompanhar meu progresso e gerenciar melhor minhas tarefas. Para isso, devo fornecer uma data inicial e uma data final, garantindo que a busca seja realizada conforme esses parâmetros.|1|R1,R2,R3|21|
|2|Alta|Eu, como operador, desejo visualizar todos os cards com base em seu status para acompanhar o andamento das tarefas nos projetos. Para isso, devo fornecer o tipo de projeto como parâmetro, permitindo a filtragem e exibindo a quantidade de cards em cada status.|1|R4|11|
|3|Alta|Eu, como operador, desejo visualizar o tempo médio de conclusão dos cards finalizados e a quantidade de projetos em que estou participando para acompanhar meu desempenho e a eficiência na conclusão das tarefas.|1|R5,R6|18|
|4|Alta|Eu, como gestor, desejo visualizar a quantidade de cards atribuídos a cada operador sob minha gestão, assim como os cards designados a mim, para monitorar a distribuição de tarefas e gerenciar melhor a equipe.|2|R7,R8|A determinar|
|5|Alta|Eu, como gestor, desejo filtrar os cards dos projetos que gerencio e que estão atribuídos a mim, considerando um período específico, para acompanhar a evolução das tarefas e a finalização das atividades. Para isso, devo fornecer uma data inicial e uma data final, garantindo que a busca seja realizada conforme esses parâmetros.|2|R9,R10|A determinar|
|6|Alta|Eu, como gestor, desejo visualizar todos os cards dos operadores que gerencio, filtrando-os com base em seu status, para monitorar o andamento das tarefas e a progressão dos projetos.|2|R11|A determinar|
|7|Alta|Eu, como gestor, desejo visualizar informações por meio de indicadores que destaquem o tempo médio de conclusão dos cards finalizados pela equipe. Quero acompanhar o tempo médio que cada operador da equipe leva para finalizar uma tarefa, para avaliar a produtividade individual e coletiva.|2|R12|A determinar|
|8|Alta|Eu, como gestor, desejo visualizar informações sobre retrabalhos e também obter detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|2|R13,R14|A determinar|
|9|Alta|Eu,como gestor de projetos, quero visualizar o total de cards organizados por tags, para poder analisar rapidamente a distribuição das tarefas e acompanhar o progresso de cada área do projeto de forma mais eficiente.|2|R15|A determinar|
|10|Media|Eu, como Admin, desejo visualizar a quantidade de cards criados e finalizados dentro de um período específico, para monitorar o progresso das tarefas. Para isso, preciso fornecer uma data de início e uma data de término, garantindo que a busca seja realizada com base nesses parâmetros.|3|R16,R17|A determinar|
|11|Media|Eu, como Admin, desejo visualizar informações sobre a quantidade de projetos, o número de cards em cada projeto, suas respectivas issues e o gestor responsável por cada projeto, para ter uma visão abrangente do andamento e da gestão dos projetos.|3|R18,R19,R20,R21|A determinar|
|12|Media|Eu, como operador, gestor ou admin, desejo fazer login na aplicação para acessar meus indicadores, para monitorar o desempenho e os dados relevantes. Para isso, ao fornecer meu username e password corretos, poderei autenticar-me com sucesso.|3|R22,R23,R24|A determinar|
|13|Baixa|Eu, como admin, desejo integrar novas ferramentas ao sistema, permitindo a ampliação das funcionalidades e a interoperabilidade com diferentes plataformas, a fim de melhorar a eficiência e a experiência dos usuários.|3|R25|A determinar|
|14|Baixa|Eu, como operador, gestor ou admin, quero realizar a exportação dos dados do Dashboard para um arquivo CSV, para que eu possa analisar, compartilhar ou arquivar os dados de forma prática e organizada, fora da plataforma.|3|R26|A determinar|
---