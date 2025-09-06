<div align="center">

# API 6º Semestre BD - NoDesk

</div>

<p align="center">
  <img src="./documentation/images/equipe-nodesk-sem-fundo.png" alt="Equipe NoDesk" width="300">
</p>

<p align="center">
  | <a href ="#desafio">Desafio</a>  |
  <a href ="#solucao">Solução</a>  |
  <a href ="#requisitos">Requisitos</a>  |
  <a href ="#backlog">Backlog do Produto</a>  |
  <a href ="#dor">DoR</a>  |
  <a href ="#dod">DoD</a>  |
  <a href ="#sprint">Cronograma de Sprints</a>  |
  <a href ="#tecnologias">Tecnologias</a> |
  <a href ="#manual">Manual de Instalação</a>  |
  <a href ="#equipe">Equipe</a> |
</p>

<br>

> Status do Projeto: Em desenvolvimento 🚧
>
> Pasta de Documentação: [Link](documentation) 📄
>
> Video do Projeto: 📽️

<br>

## 🎯 Desafio <a id="desafio"></a>

A área de suporte da Pro4tech enfrenta dificuldades para tomar decisões estratégicas por falta de uma análise clara e consolidada dos dados de chamados. A equipe lida com problemas como lentidão no atendimento e respostas repetitivas, sem conseguir identificar facilmente as causas-raiz para implementar melhorias eficazes. A ausência de uma ferramenta centralizada para gerar insights obriga os gestores a basearem suas ações em intuição, em vez de dados concretos, dificultando a prevenção de problemas e a otimização de recursos.

<br>

## 💡 Solução <a id="solucao"></a>

Desenvolver a plataforma <**_>, uma ferramenta de Business Intelligence (BI) que se conecta ao banco de dados da Pro4tech para modernizar e analisar os dados de suporte. A solução irá transformar dados brutos em insights visuais e acionáveis através de dashboards interativos. Com o <_**>, os tomadores de decisão poderão identificar rapidamente os projetos e categorias mais problemáticos, acompanhar a evolução dos chamados, monitorar a eficiência da equipe e agir proativamente para melhorar a satisfação do cliente, tudo em conformidade com a LGPD.

<br>

## 📋 Requisitos Funcionais <span id="requisitos">

<table>
    <tr>
        <th>ID</th>
        <th>Requisitos Funcionais</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>RF01</td>
        <td>Tela Principal com Gráficos (Dashboard)</td>
        <td>O sistema deve ter uma tela inicial que mostra de forma visual os gráficos e as informações mais importantes retiradas dos chamados.</td>
    </tr>
    <tr>
        <td>RF02</td>
        <td>Pontuar Aplicações Críticas</td>
        <td>O usuário precisa ver de forma fácil quais aplicações geram mais chamados, para identificar qualidade aquém do esperado.</td>
    </tr>
    <tr>
        <td>RF03</td>
        <td>Ver a Evolução dos Chamados</td>
        <td>A ferramenta deve mostrar um gráfico de como o número de chamados aumenta ou diminui com o passar do tempo.</td>
    </tr>
    <tr>
        <td>RF04</td>
        <td>Gerenciamento de Acessos</td>
        <td>Permitir que um usuário administrador possa cadastrar, editar e remover o acesso de outros usuários à plataforma.</td>
    </tr>
    <tr>
        <td>RF05</td>
        <td>Mostrar Chamados Atrasados</td>
        <td>O sistema precisa mostrar quantos chamados já passaram do prazo de entrega (SLA), para identificar falhas nas performance da equipe de suporte.</td>
    </tr>
    <tr>
        <td>RF06</td>
        <td>Pontuar Categorias Críticas</td>
        <td>O usuário precisa identificar quais categorias geram mais chamados, para saber quais equipes acionar a fim de mudar estratégias.</td>
    </tr>
</table>

## 📋 Requisitos Não-Funcionais

<table>
    <tr>
        <th>ID</th>
        <th>Requisitos Não-Funcionais</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>RNF01</td>
        <td>Conformidade com a LGPD</td>
        <td>O sistema deve tratar os dados em conformidade com a Lei Geral de Proteção de Dados (LGPD).</td>
    </tr>
    <tr>
        <tr>
        <td>RNF02</td>
        <td>Arquitetura de Persistência</td>
        <td>A solução deverá utilizar um banco de dados não relacional (NoSQL) para armazenamento e consulta dos dados processados, garantindo escalabilidade e flexibilidade.</td>
    </tr>
    <tr>
        <tr>
        <td>RNF03</td>
        <td>Uso de Inteligência Artificial</td>
        <td>O sistema deve empregar algoritmos ou serviços de IA para a geração de insights.</td>
    </tr>
    <tr>
        <tr>
        <td>RNF04</td>
        <td>Segurança no Acesso</td>
        <td>O sistema deve garantir que apenas usuários autenticados e com as devidas permissões tenham acesso aos dados e funcionalidades da plataforma.</td>
    </tr>
    <tr>
        <tr>
        <td>RNF05</td>
        <td>Usabilidade e Documentação</td>
        <td>A plataforma deve possuir uma interface intuitiva para usuários de negócio e ser acompanhada de um manual que detalhe suas funcionalidades (Manual de Usuário).</td>
    </tr>
</table>

<br>

## 📋 Backlog do Produto <a id="backlog"></a>

<table>
    <tr>
        <th>Rank</th>
        <th>Prioridade</th>
        <th>User Story</th>
        <th>Story Points</th>
        <th>Sprint</th>
        <th>Requisito do Cliente</th>
        <th>Status</th>
    </tr>
    <tr align="center">
        <td>1</td>
        <td>Alta</td>
        <td align="left">Como tomador de decisão, eu quero saber os projetos com maior número de chamados, para priorizar ações de melhoria.</td>
        <td>8</td>
        <td>1</td>
        <td>RF01, RF02</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>2</td>
        <td>Alta</td>
        <td align="left">Como tomador de decisão, eu quero identificar as categorias com maior número de chamados, para revisar os planos de ação e realocar recursos nos setores mais críticos.</td>
        <td>6</td>
        <td>1</td>
        <td>RF01, RF02</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>3</td>
        <td>Alta</td>
        <td align="left">Como tomador de decisão, eu quero analisar a evolução do número de chamados nos últimos meses, segmentados por categoria, para medir o impacto das ações implementadas e ajustar a estratégia quando necessário.</td>
        <td>8</td>
        <td>1</td>
        <td>RF01, RF03</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>4</td>
        <td>Alta</td>
        <td align="left">Como cliente, eu quero que meus funcionários usem uma aplicação que atenda à LGPD, para evitar problemas jurídicos.</td>
        <td>10</td>
        <td>1 e 2</td>
        <td>RNF01</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>5</td>
        <td>Média</td>
        <td align="left">Como tomador de decisão, eu quero visualizar o número de chamados vencidos, para avaliar a eficiência da equipe de suporte e identificar possíveis gargalos no atendimento.</td>
        <td>2</td>
        <td>2</td>
        <td>RF01, RF05</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>6</td>
        <td>Média</td>
        <td align="left">Como tomador de decisão, eu quero visualizar em um dashboard o nível de satisfação de um cliente específico, para agir de forma proativa na sua retenção.</td>
        <td>20</td>
        <td>3</td>
        <td>RF01, RF06</td>
        <td>🚧</td>
    </tr>
    <tr align="center">
        <td>7</td>
        <td>Baixa</td>
        <td align="left">Como gerente do setor de relacionamento, quero cadastrar os usuários da aplicação para ter controle de quais funcionários têm acesso aos insights.</td>
        <td>5</td>
        <td>3</td>
        <td>RF04</td>
        <td>🚧</td>
    </tr>
</table>

<br>

## 🏃‍ DoR - Definition of Ready <a id="dor"></a>

- User Stories com **Critérios de Aceitação**
- Subtarefas divididas **a partir das User Story**
- Design no **Figma**
- Modelagem do **Banco de Dados**
- Dependências externas **estão resolvidas ou mapeadas**

## 🏆 DoD - Definition of Done <a id="dod"></a>

- Manual de Usuário
- Manual da Aplicação
- Documentação da API (Application Programming Interface)
- Código completo
- Vídeos de cada etapa de entrega

<br>

## 📅 Cronograma de Sprints <a id="sprint"></a>

<table>
    <tr>
        <th>SPRINT</th>
        <th>PERÍODO</th>
        <th>DESCRIÇÃO</th>
    </tr>
    <tr>
        <td>Kick-off</td>
        <td>25/08/2025 à 29/08/2025</td>
        <td>Alinhamento inicial da equipe, apresentação do tema do projeto e definição de papéis e responsabilidades.</td>
    </tr>
    <tr>
        <td>Sprint 1</td>
        <td>08/09/2025 à 28/09/2025</td>
        <td>Desenvolver a estrutura principal do dashboard. Implementar as visualizações de ranking de projetos e categorias com mais chamados. Criar o gráfico de análise da evolução do número de chamados ao longo do tempo. Iniciar a estruturação do tratamento de dados, garantindo a conformidade com a LGPD.</td>
    </tr>
    <tr>
        <td>Sprint 2</td>
        <td>06/10/2025 à 26/10/2025</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Sprint 3</td>
        <td>03/11/2025 à 23/11/2025</td>
        <td>-</td>
    </tr>
    <tr>
        <td>Feira de Soluções</td>
        <td>04/12/2025</td>
        <td>Apresentação da versão final do projeto desenvolvido pela equipe.</td>
    </tr>
</table>

<br>

## 💻 Tecnologias <a id="tecnologias"></a>

<h4 align="center">
 <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
 <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/></a>
 <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"></a>
 <a href="https://vuejs.org/"><img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D"/></a>
 <a href="https://nuxt.com/"><img src="https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxtdotjs&logoColor=white"/></a>
 <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/Postgres-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"></a>
 <a href="https://www.mongodb.com/"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"></a>
 <a href="https://www.atlassian.com/software/jira"><img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/></a>
 <a href="https://github.com/"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/></a>
 <a href="https://github.com/features/actions"><img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/></a>
 <a href="https://www.figma.com/"><img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/></a>
</h4>

<br>

## 📖 Manual de Instalação <a id="manual"></a>

### 🛠 Pré-requisitos

- Git ([Download](https://git-scm.com/downloads))
- Python 3.13+ ([Download](https://www.python.org/downloads))
- Node.js 20+ ([Download](https://nodejs.org/en/download))
- Poetry ([Documentação](https://python-poetry.org/))

### 1. Clonar o Repositório Principal

```bash
git clone https://github.com/NoDesk-6BD/6sem2025Main.git
cd 6sem2025Main
```

### 2. Configuração do Backend

1. Clone o repositório:

   ```bash
   git clone https://github.com/NoDesk-6BD/6sem2025Backend.git
   cd 6sem2025Backend
   ```

2. Instale e prepare o ambiente Python com Poetry:

   ```bash
   poetry config virtualenvs.in-project true
   poetry install
   cp -n .env.example .env
   source .venv/bin/activate
   ```

3. Gere um APP_SECRET para o arquivo `.env`:

   ```bash
   python -c "import secrets; print(secrets.token_urlsafe(64))"
   ```

4. Execute o backend em modo desenvolvimento:

   ```bash
   uvicorn nodesk:app --reload --port 8000
   ```

   **Saída Esperada:**

   - Health: [http://127.0.0.1:8000/health](http://127.0.0.1:8000/health)
   - Docs: [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)

5. Para rodar testes:

   ```bash
   pytest
   ```

6. Qualidade de código:

   ```bash
   ruff format .
   ruff check .
   ```

### 3. Configuração do Frontend

1. Clone o repositório:

   ```bash
   git clone https://github.com/NoDesk-6BD/6sem2025Frontend.git
   cd 6sem2025Frontend
   ```

2. Instale as dependências do projeto Nuxt:

   ```bash
   npm install
   ```

3. Execute o frontend em modo desenvolvimento:

   ```bash
   npm run dev
   ```

   **Saída Esperada:**

   - App: [http://localhost:3000](http://localhost:3000)

4. Para rodar testes:

   ```bash
   npm run test
   ```

5. Qualidade de código:

   ```bash
   npm run lint
   npm run format
   ```

<br>

## 👥 Equipe <a id="equipe"></a>

<table>
    <tr>
        <th>IDENTIFICAÇÃO</th>
        <th>NOME</th>
        <th>FUNÇÃO</th>
        <th>MÍDIAS SOCIAIS</th>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/79020769?v=4" width="60"></td>
        <td>Tânia Cruz</td>
        <td>Product Owner</td>
        <td><a href="https://www.linkedin.com/in/t%C3%A2nia-cruz-30ab5812a/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/taniacruzz"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/81196630?v=4" width="60"></td>
        <td>Lucas Henrique</td>
        <td>Scrum Master</td>
        <td><a href="https://www.linkedin.com/in/lucas-henrique-9a557620b/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/LucasHCOliveira7"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/109988937?v=4" width="60"></td>
        <td>Willian Caboski</td>
        <td>Desenvolvedor</td>
        <td><a href="https://www.linkedin.com/in/willian-caboski/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/DankoCaboski"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/122806886?v=4" width="60"></td>
        <td>Jhonny Dutra</td>
        <td>Desenvolvedor</td>
        <td><a href="https://www.linkedin.com/in/dutrajy/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/dutrajy"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/53319211?v=4" width="60"></td>
        <td>Wallace Caetano</td>
        <td>Desenvolvedor</td>
        <td><a href="https://www.linkedin.com/in/wallace-caetano/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/UeresWally"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/u/62269345?v=4" width="60"></td>
        <td>William Antoniazzi</td>
        <td>Desenvolvedor</td>
        <td><a href="https://www.linkedin.com/in/williamantoniazzi/"><img src="https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white" alt="Linkedin Badge"></a>
<a href="https://github.com/williamantoniazzi"><img src="https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white" alt="GitHub Badge"></a></td>
    </tr>
</table>
