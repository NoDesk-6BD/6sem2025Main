## Objetivo
Este documento visa padronizar as práticas de desenvolvimento em todos os repositórios do projeto, promovendo consistência, legibilidade e colaboração eficiente entre os membros da equipe. As diretrizes se aplicam a todas as partes interessadas, incluindo as equipes de Frontend e Backend.

<br>

## Padrão de Branch
A branch é um recurso que permite à equipe trabalhar em diferentes versões do código ao mesmo tempo, sem interferir no que já está estável e funcionando.

### Branches Principais:
- `main`: Contém a versão estável e pronta para produção do projeto.<br>
- `sprint-{número}`: Branch usada como base para as tarefas de sprint em andamento.

> Exemplo: `sprint-1`, `sprint-2`, `sprint-3`

### Formato:

~~~shell
{tipo}/{código-card-jira}-{breve-descrição}
~~~

### Tipos permitidos:
- `feature` - Nova funcionalidade.
- `fix` - Correção de bugs em desenvolvimento.
- `bugfix` - Correção de bugs encontrados em produção.
- `hotfix` - Correção urgente em produção.
- `chore` - Tarefas de manutenção ou ajustes sem impacto direto no código-fonte.

### Exemplo:

~~~shell
feature/ND-1-criacao-estrutura-inicial-backend
~~~

> Use letras minúsculas e hífens em vez de espaços. O código do card deve vir da ferramenta de gerenciamento (Jira).

<br>

## Padrão de Commit
A padronização de mensagens de commits é uma prática importante, pois, além de ajudar na compreensão do histórico de commits, facilita a criação de ferramentas automatizadas baseadas na especificação.<br>
Saiba mais clicando aqui: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

### Formato:

~~~shell
{tipo} ({código-card-jira}): {descrição curta}
~~~

### Tipos permitidos:
- `feat` - Implementação de nova funcionalidade.
- `fix` - Correção de bugs ou problemas no código.
- `doc` - Alterações na documentação.
- `style` - Ajuste de formatação (sem impacto funcional).
- `refactor` - Refatoração de código.
- `test` - Adição ou atualização de testes.
- `chore` - Tarefa sem impacto direto no código-fonte, ferramentas ou bibliotecas.

### Exemplo:

~~~shell
feat (ND-1): Criação da estrutura inicial do backend
~~~
