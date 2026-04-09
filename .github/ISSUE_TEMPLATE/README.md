# Templates GitHub — Etapa 1

Este pacote contém os arquivos iniciais para um fluxo de desenvolvimento orientado a **Issues + Pull Requests + IA** no GitHub.

## Estrutura

```text
.github/
  ISSUE_TEMPLATE/
    epic.md
    feature.md
    task.md
    bug.md
    tech_debt.md
  pull_request_template.md
```

## Como usar

1. Copie a pasta `.github` para a raiz do seu repositório.
2. Faça commit dos arquivos.
3. No GitHub, ao criar uma nova issue, escolha o template adequado.
4. Ao abrir um Pull Request, o template de PR será aplicado automaticamente.

## Objetivo de cada template

- **epic.md**: visão macro de uma grande entrega.
- **feature.md**: funcionalidade derivada de um épico.
- **task.md**: tarefa técnica pequena e objetiva, ideal para delegação à IA.
- **bug.md**: correção de defeito.
- **tech_debt.md**: melhoria técnica, refatoração, padronização ou saneamento.
- **pull_request_template.md**: padroniza revisão, testes, risco e rastreabilidade.

## Sugestões de uso com IA

- Use **Task** para trabalho pequeno, objetivo e com critérios de aceite claros.
- Escreva o problema com contexto suficiente para que o Copilot ou outro agente consiga propor código útil.
- Evite issues vagas como “melhorar autenticação”. Prefira algo como:
  - “Criar endpoint POST /auth/login”
  - “Validar payload com Bean Validation”
  - “Retornar 401 para credenciais inválidas”
  - “Cobrir serviço com testes unitários”

## Próximos passos recomendados

Depois desta etapa, vale adicionar:

- labels padronizadas
- convenção de branches
- padrão de commits
- `copilot-instructions.md`
- campos do GitHub Projects

