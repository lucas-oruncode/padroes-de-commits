# Guia de Padrões de Commits 📜

Este guia segue o padrão **[Conventional Commits](https://www.conventionalcommits.org/pt-br)**, fornecendo regras claras para mensagens de commit padronizadas e organizadas.

## Tipos de Commit 🦄

- **`feat`**: Adiciona um novo recurso.
- **`fix`**: Corrige um bug.
- **`docs`**: Atualiza a documentação (sem alterações no código).
- **`test`**: Cria ou altera testes.
- **`build`**: Modifica arquivos de build ou dependências.
- **`perf`**: Melhora a performance do código.
- **`style`**: Altera formatação do código (ex.: espaços, ponto e vírgula).
- **`refactor`**: Refatora código sem alterar funcionalidades.
- **`chore`**: Realiza tarefas administrativas (ex.: atualizações de pacotes).
- **`ci`**: Faz mudanças na integração contínua.
- **`cleanup`**: Remove código desnecessário ou comentado.
- **`remove`**: Exclui arquivos ou funcionalidades obsoletas.

## Boas Práticas 🎉

- Use um título direto (até 4 palavras).
- Forneça detalhes no corpo do commit, quando necessário.
- Inclua emojis para facilitar a identificação.
- Não utilize links encurtados ou afiliados.

## Estrutura do Commit 💻

1. **Título**: Tipo e descrição sucinta.
2. **Corpo**: Detalhes sobre impactos e razões das mudanças.
3. **Rodapé**: Informações adicionais, como revisores ou referências (ex.: `Reviewed-by: Nome Refs #123`).

## Exemplos de Commits

| Comando Git                                      | Resultado                                  |
|-------------------------------------------------|-------------------------------------------|
| `git commit -m ":tada: Commit inicial"`         | Commit inicial                            |
| `git commit -m ":bug: fix: Corrige bug"`        | fix: Corrige bug                          |
| `git commit -m ":sparkles: feat: Adiciona login"` | feat: Adiciona login                     |
| `git commit -m ":zap: perf: Otimiza performance"` | perf: Otimiza performance                |
| `git commit -m ":recycle: refactor: Refatora código"` | refactor: Refatora código              |
| `git commit -m ":broom: cleanup: Remove código comentado"` | cleanup: Remove código comentado      |

## Comandos Git Essenciais 📂

- **`git clone [url]`**: Clona um repositório remoto.
- **`git init`**: Inicializa um novo repositório.
- **`git add .`**: Adiciona arquivos ao stage.
- **`git commit -m "mensagem"`**: Registra mudanças no repositório local.
- **`git push -u origin main`**: Envia commits para o repositório remoto.
- **`git pull origin main`**: Atualiza a branch local.
- **`git revert [id]`**: Cria um commit que desfaz alterações de um commit anterior.
- **`git reset --hard [id]`**: Restaura o repositório para um commit específico.

## Glossário 📖

- **Fork**: Cópia de um repositório para sua conta no GitHub.
- **Issues**: Ferramenta para gerenciar tarefas ou bugs.
- **Pull Request**: Solicitação para revisão e integração de alterações.
- **Gist**: Compartilhamento rápido de trechos de código.

Com este guia, você garantirá um fluxo de commits claro, organizado e colaborativo! 🚀
