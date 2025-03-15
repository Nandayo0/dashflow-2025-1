<h1 align="center">📊 🎯 YOUTAN DASH 📈 📶</h1>
<h3 align="center">Repositório dedicado ao versionamento do projeto API do 5º semestre de Banco de Dados.</h3>

---

## 🎯 Objetivo do Projeto
> [!IMPORTANT]
> O objetivo do projeto é desenvolver uma plataforma integrada a ferramenta de gestão de projetos Taiga, com o intuito de gerar e visualizar indicadores relacionados ao andamento de projetos. A plataforma deve fornecer um dashboard que permita a extração e análise de métricas importantes, como a quantidade de cards criados e finalizados em um período, tempo médio de execução de cards, distribuição de cards por colaborador, e outros indicadores relevantes para a gestão de projetos. A plataforma deve oferecer diferentes níveis de acesso para usuários, como Operador, Gestor e Admin, garantindo que cada perfil tenha acesso apenas às informações pertinentes ao seu papel. O projeto visa facilitar a visualização e o monitoramento do progresso dos projetos, tornando o processo mais eficiente, transparente e acessível para todos os envolvidos.

---

# 🔍 Tópicos
- <a href="#tecnologias">🔌 Tecnologias</a>
- <a href="#requisitos">📋 Requisitos</a>
- <a href="#backlog">📈 Product Backlog</a>
- <a href="#membros">👥 Membros</a>

---

## 🔌Tecnologias <a id="tecnologias"></a>
> [!NOTE]
> Tecnologias utilizadas no desenvolvimento do projeto:

<h4 align="left">
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"></a>
<a href="https://spring.io/projects/spring-security" target="_blank"><img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Security"></a>
<a href="https://github.com/features/actions" target="_blank"><img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"></a>
<a href="https://swagger.io/" target="_blank"><img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white" alt="Swagger"></a>
<a href="https://jwt.io/" target="_blank"><img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT"></a>
<a href="https://junit.org/" target="_blank"><img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"></a>
<a href="https://www.primefaces.org/primevue/" target="_blank"><img src="https://img.shields.io/badge/PrimeVue-4CAF50?style=for-the-badge&logo=vue.js&logoColor=white" alt="PrimeVue"></a>
<a href="https://axios-http.com/" target="_blank"><img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"></a>
<a href="https://www.figma.com/" target="_blank"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma"></a>
<a href="https://vitest.dev/" target="_blank"><img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest"></a>
<a href="https://www.postgresql.org/" target="_blank"><img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"></a>
<a href="https://yarnpkg.com/" target="_blank"><img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white" alt="Yarn"></a>
<a href="https://www.npmjs.com/" target="_blank"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"></a>
</h4>

---

<br>

## 📋 Requisitos <a id="requisitos"></a>

### 📌 Requisitos Funcionais
| **ID** | **Persona** | **Título** | **Descrição** |
| :-------------: | :-------------: | ------------- |------------- |
|R1|Operador|Visualização de indicadores e quantidades de cards por Operador|O sistema deve permitir a visualização das quantidades de cards atribuídos a cada operador, por meio de um gráfico que facilite a interpretação e análise dos dados. |
|R2|Operador|Visualização de indicadores e cards criados  por período|O sistema deve permitir a visualização dos cards elaborados, organizados por períodos específicos (diário, semanal, mensal, etc.), para facilitar a análise e o acompanhamento do desempenho e da produtividade.|
|R3|Operador|Visualização de indicadores e cards finalizados por período|O sistema deve permitir a visualização dos cards finalizados, organizados por um período específico (diário, semanal, mensal, etc.), para facilitar a análise do desempenho e da conclusão de atividades. |
|R4|Operador|Visualização de indicadores por status da tarefa|O sistema deve permitir a visualização dos cards  organizados conforme o status da tarefa (coluna do Kanban ou Sprint), para facilitar o acompanhamento do fluxo de trabalho e a identificação de gargalos. |
|R5|Operador|Visualização de indicadores com tempo Médio de Execução de um Card.|O sistema deve permitir a visualização do tempo médio de execução de um card, para facilitar a análise de eficiência e produtividade no fluxo de trabalho.|
|R6|Operador|Visualização de indicadores, quantidade de projetos por participante|O sistema deve permitir a visualização da quantidade de projetos em que cada operador está envolvido, para facilitar a análise de carga de trabalho e distribuição de atividades.|
|R7|Gestor|visualizar informações com os indicadores, quantidade de cards atribuídos.|O sistema deve permitir a visualização da quantidade de cards atribuídos ao gestor da equipe, para facilitar a análise de distribuição de tarefas e carga de trabalho.|
|R8|Gestor|Visualizar informações com os indicadores, cards por colaborador.|O sistema deve permitir a visualização da quantidade de cards atribuídos a cada colaborador, para facilitar a análise de produtividade, carga de trabalho e distribuição de tarefas.|
|R9|Gestor|Visualizar informações com os indicadores, quantidade de cards criados por um período de todos os projetos que o gestor participa.|O sistema deve permitir a visualização da quantidade de cards criados em um período específico (diário, semanal, mensal, etc.), para facilitar a análise de produtividade e volume de atividades.|
|R10|Gestor|Visualizar informações com os indicadores, quantidade de cards finalizados em um período.|O sistema deve permitir a visualização da quantidade de cards finalizados em um período específico (diário, semanal, mensal, etc.), para facilitar a análise de produtividade e conclusão de atividades.|
|R11|Gestor|Visualizar informações com os indicadores, por status das tarefas(Coluna do Kanban).|O sistema deve permitir a visualização das informações relacionadas aos cards de todos os projetos que o gestor participa, organizados conforme o status das tarefas (coluna do Kanban, ou Sprint), para facilitar o acompanhamento do fluxo de trabalho e a identificação de gargalos.|
|R12|Gestor|Visualizar informações por meio de indicadores, destacando o tempo médio que os operadores levam para finalizar um card.|O sistema deve permitir a visualização das informações relacionadas aos indicadores, destacando o tempo médio que os operadores levam para finalizar um card, com o objetivo de analisar a eficiência e produtividade individual.|
|R13|Gestor|Visualizar informações com os indicadores, cards que foram feitos retrabalho.|O sistema deve permitir a visualização dos cards que passaram por retrabalho, com o objetivo de analisar a eficiência do processo e identificar possíveis melhorias.
|R14|Gestor|Visualizar informações com os indicadores, quantidade de issue por projetos.|O sistema deve permitir a visualização da quantidade de issues (problemas, tarefas ou solicitações) por projeto, para facilitar a análise de volume de trabalho, priorização e alocação de recursos.|
|R15|Gestor|Visualizar informações com os indicadores, quantidade de cards por tags.|O sistema deve permitir a visualização da quantidade de cards associados a cada tag (etiqueta), para facilitar a análise de categorização, priorização e distribuição de tarefas.|
|R16|Admin|Visualizar informações com os indicadores, quantidade de cards criados por um período de tempo.|O sistema deve permitir a visualização da quantidade de cards criados em um período de tempo específico (diário, semanal, mensal, etc.) de todos os projetos, para facilitar a análise de volume de atividades, produtividade e tendências ao longo do tempo.|
|R17|Admin|Visualizar informações com os indicadores, quantidade de cards finalizados em um período.|O sistema deve permitir a visualização da quantidade de cards finalizados em um período de tempo específico (diário, semanal, mensal, etc.) de todos os projetos, para facilitar a análise de volume de atividades, produtividade e tendências ao longo do tempo.|
|R18|Admin|Visualizar informações com os indicadores, quantidade de projetos.|O sistema deve permitir a visualização da quantidade de projetos, para facilitar a análise de volume de trabalho, alocação de recursos e planejamento estratégico.|
|R19|Admin|Visualizar informações com os indicadores, quantidade de issues.|O sistema deve permitir a visualização da quantidade de issues por projetos, para análise de volume de trabalho, priorização e alocação de recursos.|
|R20|Admin|Visualizar informações com os indicadores, a quantidade de cards de todos os projetos.|O sistema deve permitir a visualização da quantidade de cards em todos os projetos, para facilitar a análise de volume de trabalho, distribuição de tarefas e alocação de recursos.|
|R21|Admin|Visualizar informações como os indicadores, quem é o gestor do projeto.|O sistema deve permitir a visualização do gestor responsável por cada projeto, para facilitar a análise de responsabilidades, comunicação e tomada de decisões.|
|R22|Operador|O operador deverá ser designado para a função ROLE_USER para o login da aplicação|O sistema deve garantir que o operador seja designado para a função ROLE_USER, assegurando que ele tenha acesso e permissões adequadas para visualizar e interagir apenas com as informações que são exclusivamente suas.|
|R23|Gestor|O gestor deverá ser designado à função ROLE_MANAGER para o login da aplicação|O sistema deve garantir que o gestor seja designado para a função ROLE_MANAGER, assegurando que ele tenha acesso e permissões adequadas para visualizar e gerenciar informações pertinentes aos projetos sob sua responsabilidade, bem como seus próprios dados, e cards dos operadores.|
|R24|Admin|O Administrador terá a função ROLE_ADMIN para o login da aplicação|O sistema deve garantir que o administrador seja designado para a função ROLE_ADMIN, permitindo-lhe acessar e gerenciar informações relacionadas a todos os projetos, usuários e configurações do sistema.|
|R25|Admin| Criar uma api para integração com outro sistema(trello, Jira).|O sistema deve disponibilizar uma API (Application Programming Interface) para integração com sistemas externos, como Trello e Jira, permitindo a sincronização de dados, como cards, projetos, tarefas e indicadores, entre as plataformas.|
|R26|Admin, Gestor, Operador| A persona deverá ser capaz de exportar dados do Dashboard para um arquivo CSV.|O sistema deve permitir que a persona exporte os dados exibidos no Dashboard para um arquivo CSV, facilitando a análise externa, a geração de relatórios e o compartilhamento de informações.|
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

## 📈 Product Backlog <a id="backlog"></a>

| 🏅 Rank| 🔥 Prioridade| 📝 User Story| 🚀 Sprint| 🎯 Requisito do Parceiro|🚨 Estimativa
| :--------: | :--------: | -------- | :--------: | :--------: | :--------: |
|1|Alta|Eu, como operador, desejo visualizar a quantidade de cards atribuídos a mim e filtrar os cards dos meus projetos com base no período de criação e finalização, para acompanhar meu progresso e gerenciar melhor minhas tarefas.|1|R1,R2,R3|21|
|2|Alta|Eu, como operador, desejo visualizar todos os cards com base em seu status para acompanhar o andamento das tarefas nos projetos.|1|R4|11|
|3|Alta|Eu, como operador, desejo visualizar o tempo médio de conclusão dos cards finalizados e a quantidade de projetos em que estou participando para acompanhar meu desempenho e a eficiência na conclusão das tarefas.|1|R5,R6|18|
|4|Alta|Eu, como gestor, desejo visualizar a quantidade de cards atribuídos a cada operador sob minha gestão, assim como os cards designados a mim, para monitorar a distribuição de tarefas e gerenciar melhor a equipe.|2|R7,R8|A determinar|
|5|Alta|Eu, como gestor, desejo filtrar os cards dos projetos que gerencio e que estão atribuídos a mim, considerando um período específico, para acompanhar a evolução das tarefas e a finalização das atividades.|2|R9,R10|A determinar|
|6|Alta|Eu, como gestor, desejo visualizar todos os cards dos operadores que gerencio, filtrando-os com base em seu status, para monitorar o andamento das tarefas e a progressão dos projetos.|2|R11|A determinar|
|7|Alta|Eu, como gestor, desejo visualizar informações por meio de indicadores que destaquem o tempo médio de conclusão dos cards finalizados pela equipe. Quero acompanhar o tempo médio que cada operador da equipe leva para finalizar uma tarefa, para avaliar a produtividade individual e coletiva.|2|R12|A determinar|
|8|Alta|Eu, como gestor, desejo visualizar informações sobre retrabalhos e também obter detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|2|R13,R14|A determinar|
|9|Alta|Eu,como gestor de projetos, quero visualizar o total de cards organizados por tags, para poder analisar rapidamente a distribuição das tarefas e acompanhar o progresso de cada área do projeto de forma mais eficiente.|2|R15|A determinar|
|10|Media|Eu, como Admin, desejo visualizar a quantidade de cards criados e finalizados dentro de um período específico, para monitorar o progresso das tarefas.|3|R16,R17|A determinar|
|11|Media|Eu, como Admin, desejo visualizar informações sobre a quantidade de projetos, o número de cards em cada projeto, suas respectivas issues e o gestor responsável por cada projeto, para ter uma visão abrangente do andamento e da gestão dos projetos.|3|R18,R19,R20,R21|A determinar|
|12|Media|Eu, como operador, gestor ou admin, desejo fazer login na aplicação para acessar meus indicadores, para monitorar o desempenho e os dados relevantes.|3|R22,R23,R24|A determinar|
|13|Baixa|Eu, como admin, desejo integrar novas ferramentas ao sistema, permitindo a ampliação das funcionalidades e a interoperabilidade com diferentes plataformas, a fim de melhorar a eficiência e a experiência dos usuários.|3|R25|A determinar|
|14|Baixa|Eu, como operador, gestor ou admin, quero realizar a exportação dos dados do Dashboard para um arquivo CSV, para que eu possa analisar, compartilhar ou arquivar os dados de forma prática e organizada, fora da plataforma.|3|R26|A determinar|

---
<br>

## 👥 Team Members <a id="membros"></a>
|Nome|Função|LinkedIn|  
| -------- | -------- | -------- |
|**Paulo Arantes Machado**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b)|
|**Otavio Calderan Bruguel**|Scrum Master|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/otavio-calderan-578b48239)|
|**André Hideaki Wakugawa**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrewakugawa/)|
|**Beatriz Bonatto**|Desenvolvedora|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://br.linkedin.com/in/beatriz-bonatto-263530156)|
|**Cauê Vieira da Silva**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)|
|**Gabriel Bartolomeu Guska**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabiel-guska-5860a1271/)|
|**Gabriel de Souza Mota**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabriel-mota-4a0816a0/)|
