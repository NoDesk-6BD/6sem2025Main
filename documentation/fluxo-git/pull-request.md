## Objetivo
Este documento visa padronizar as práticas de desenvolvimento em todos os repositórios do projeto, promovendo consistência, legibilidade e colaboração eficiente entre os membros da equipe. As diretrizes se aplicam a todas as partes interessadas, incluindo as equipes de Frontend e Backend.

<br>

## Padrão de Pull Request
O Pull Request (PR) é um recurso que permite à equipe revisar e integrar alterações de código de forma colaborativa, garantindo qualidade e evitando impactos negativos no que já está estável.

### Formato:

~~~shell
{tipo} ({código-card-jira}): {Breve descrição}
~~~

### Tipos permitidos:
- `Feature` – Implementação de nova funcionalidade.
- `Fix` – Correção de bugs em desenvolvimento ou produção.
- `Hotfix` – Correção urgente de bugs críticos em produção.
- `Docs` – Alterações ou adições de documentação.
- `Refactor` – Alterações no código que não modificam funcionalidade.
- `Chore` – Tarefas de manutenção ou ajustes sem impacto direto no código-fonte.

### Exemplo:

~~~shell
Feature (ND-1): Criação da estrutura inicial do backend
~~~

> Usar sempre inicial maiúscula nos tipos (Feature, Fix, etc.) para consistência.

<br>

## Diretrizes para abertura de PR:
- Cada nova funcionalidade ou correção deve ser submetida via Pull Request.
- Marque pelo menos um revisor da equipe.
- Adicione o link da tarefa no Jira.
- Descreva de forma clara o que foi alterado.
- Certifique-se de que sua branch esteja atualizada com a branch da sprint antes do envio.

<br>

## Revisão de Código
- Cada PR deve ser revisada por pelo menos **um membro da equipe**.

#### O revisor deve verificar:
- Clareza e legibilidade do código.
- Cobertura de testes (se aplicável).
- Impacto em outras partes do sistema.
- Aderência às boas práticas e padrões definidos neste repositório.

> Nenhuma PR deve ser mesclada sem aprovação e sem `sucesso` no fluxo de trabalho de CI.

<br>

## Definition of Done (DoD) para PRs

Uma PR só será considerada concluída (Done) se atender aos seguintes critérios:
- O código foi revisado por pelo menos um membro da equipe.
- Todos os testes existentes passaram com sucesso.
- Novos testes foram criados (quando aplicável).
- A documentação foi atualizada (se necessário).
- Não há conflitos com a branch principal da sprint.
- O fluxo de CI/CD executou com sucesso.
- A PR contém descrição clara e link para o card no Jira.
- Os critérios de aceitação da tarefa (do Jira) foram atendidos.
