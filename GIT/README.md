# GIT *overview* 🤖

| Comando                        | Descrição                                                                 |
|--------------------------------|---------------------------------------------------------------------------|
| `git config --global user.name "John Doe"` | Configura o nome do usuário para todos os repositórios locais.            |
| `git config --global user.email johndoe@example.com` | Configura o email do usuário para todos os repositórios locais.           |
| `git init`                     | Inicializa um novo repositório Git.                                       |
| `.gitignore`                   | Arquivo que especifica quais arquivos ou diretórios devem ser ignorados.  |
| `git clone`                    | Clona um repositório existente.                                           |
| `git add {file}`               | Adiciona arquivos ao índice (staging area).                               |
| `git status`                   | Mostra o estado dos arquivos no índice e no diretório de trabalho.        |
| `git commit -m "message"`      | Confirma as mudanças no índice com uma mensagem descritiva.               |
| `git rm --cached {file}`       | Remove arquivos do índice sem deletá-los do diretório de trabalho.        |
| `git diff`                     | Mostra as diferenças entre os arquivos modificados e o último commit.     |
| `git log (--oneline)`          | Exibe o histórico de commits.                                             |
| `git rm {file}`                | Remove arquivos do índice e do diretório de trabalho.                     |
| `git restore (--staged) {file}`| Restaura arquivos do índice ou do diretório de trabalho.                  |
| `git mv {file_name} {new_file_name}` | Move ou renomeia um arquivo.                                             |
| `git commit -m {message} --amend` | Modifica o último commit.                                                  |
| `git reset`                    | Reseta o índice e o diretório de trabalho para um estado anterior.        |
| `--soft`                        | volta para o commit anterior e Mantém o commit seguinte em staged                                     |
| `--mixed`                       | volta para o commit anterior e Mantém o commit seguinte em unstaged(para comitar)                                              |
| `--hard`                        | volta para o commit anterior e apaga o commit seguinte                         |
| `Git alias`                    | Cria atalhos para comandos Git.                                           |
| `git branch`                   | Gerencia branches (ramificações) no repositório.                         |
| `git merge (-m)`               | Mescla branches.                                                          |
| `git branch -d`                | Deleta uma branch.                                                        |
| `git push`                     | Envia commits para um repositório remoto.                                 |
| `issues (GitHub)`              | Ferramenta do GitHub para rastreamento de problemas e tarefas.            |
| `releases (GitHub)`            | Ferramenta do GitHub para gerenciar versões de software.                  |
| `git pull`                     | Puxa mudanças de um repositório remoto e as mescla no repositório local.  |
