# Cheatsheet de Comandos que eu uso no meu dia a dia

> Este README contém tabelas com comandos essenciais para mim, útil para referência rápida.

## Índice

- [Cheatsheet de Bash](#cheatsheet-de-bash)
- [Cheatsheet de Git](#cheatsheet-de-git)
- [Cheatsheet do Vim](#cheatsheet-do-vim)

## Cheatsheet de Bash

| Categoria               | Comando                           | Descrição                                                              |
|:------------------------|:----------------------------------|:-----------------------------------------------------------------------|
| Comandos Básicos        | pwd                               | Mostra o diretório atual.                                              |
| Comandos Básicos        | ls                                | Lista arquivos e diretórios.                                           |
| Comandos Básicos        | ls -l                             | Listagem detalhada.                                                    |
| Comandos Básicos        | ls -a                             | Mostra arquivos ocultos.                                               |
| Comandos Básicos        | cd [diretório]                    | Navega até o diretório especificado.                                   |
| Comandos Básicos        | cd ..                             | Volta ao diretório anterior.                                           |
| Comandos Básicos        | cd ~                              | Vai para o diretório home do usuário.                                  |
| Comandos Básicos        | mkdir [nome]                      | Cria um novo diretório.                                                |
| Comandos Básicos        | rmdir [nome]                      | Remove um diretório vazio.                                             |
| Comandos Básicos        | rm [arquivo]                      | Remove um arquivo.                                                     |
| Comandos Básicos        | !!                                | Repete o último comando executado.                                     |
| Manipulação de Arquivos | cp [origem] [destino]             | Copia arquivos ou diretórios.                                          |
| Manipulação de Arquivos | cp -r [origem] [destino]          | Copia diretórios recursivamente.                                       |
| Manipulação de Arquivos | mv [origem] [destino]             | Move ou renomeia arquivos ou diretórios.                               |
| Manipulação de Arquivos | touch [nome]                      | Cria um arquivo vazio ou atualiza a data de modificação de um arquivo. |
| Manipulação de Arquivos | cat [arquivo]                     | Exibe o conteúdo de um arquivo.                                        |
| Manipulação de Arquivos | head [arquivo]                    | Mostra as primeiras linhas de um arquivo.                              |
| Manipulação de Arquivos | head -n 5 [arquivo]               | Mostra as primeiras 5 linhas.                                          |
| Manipulação de Arquivos | tail [arquivo]                    | Mostra as últimas linhas de um arquivo.                                |
| Manipulação de Arquivos | tail -n 5 [arquivo]               | Mostra as últimas 5 linhas.                                            |
| Manipulação de Arquivos | rm -r [diretório]                 | Remove um diretório e seu conteúdo.                                    |
| Permissões              | chmod [permissões] [arquivo]      | Altera as permissões de um arquivo.                                    |
| Permissões              | chown [usuário]:[grupo] [arquivo] | Altera o dono de um arquivo.                                           |
| Permissões              | chgrp [grupo] [arquivo]           | Altera o grupo de um arquivo.                                          |
| Processos               | ps                                | Mostra processos em execução.                                          |
| Processos               | top                               | Exibe processos em tempo real.                                         |
| Processos               | kill [PID]                        | Encerra um processo com o PID especificado.                            |
| Processos               | killall [nome]                    | Encerra todos os processos com o nome especificado.                    |
| Redirecionamento        | >                                 | Redireciona a saída para um arquivo (sobrescreve).                     |
| Redirecionamento        | >>                                | Redireciona a saída para um arquivo (acrescenta).                      |
| Redirecionamento        | <                                 | Usa um arquivo como entrada para um comando.                           |
| Redirecionamento        | \|                                | Redireciona a saída de um comando para a entrada de outro.             |
| Pesquisa                | grep [padrão] [arquivo]           | Pesquisa por um padrão dentro de um arquivo.                           |
| Pesquisa                | grep -r [padrão] [diretório]      | Pesquisa recursivamente.                                               |
| Pesquisa                | grep -i [padrão] [arquivo]        | Pesquisa ignorando diferenças de maiúsculas/minúsculas.                |
| Informações do Sistema  | df                                | Exibe o espaço em disco.                                               |
| Informações do Sistema  | du                                | Exibe o uso de espaço em disco por arquivo/diretório.                  |
| Informações do Sistema  | du -sh [diretório]                | Exibe o tamanho de um diretório de forma legível.                      |
| Informações do Sistema  | free                              | Exibe o uso de memória.                                                |
| Compressão              | tar -cvf [arquivo.tar] [arquivos] | Cria um arquivo .tar.                                                  |
| Compressão              | tar -xvf [arquivo.tar]            | Extrai um arquivo .tar.                                                |
| Compressão              | gzip [arquivo]                    | Comprime um arquivo.                                                   |
| Compressão              | gunzip [arquivo.gz]               | Descomprime um arquivo .gz.                                            |
| Outros Comandos Úteis   | alias [atalho]='[comando]'        | Cria um atalho para um comando.                                        |
| Outros Comandos Úteis   | history                           | Exibe o histórico de comandos.                                         |

## Cheatsheet de Git

| Categoria               | Comando                                  | Descrição                                               |
|-------------------------|------------------------------------------|---------------------------------------------------------|
| Configuração            | git config --global user.name '[nome]'   | Configura o nome do usuário.                            |
| Configuração            | git config --global user.email '[email]' | Configura o e-mail do usuário.                          |
| Inicialização           | git init                                 | Inicia um novo repositório Git.                         |
| Inicialização           | git clone [url]                          | Clona um repositório remoto.                            |
| Repositórios Remotos    | git remote add origin [url]              | Adiciona um repositório remoto.                         |
| Repositórios Remotos    | git remote -v                            | Lista repositórios remotos.                             |
| Repositórios Remotos    | git remote remove [nome]                 | Remove um repositório remoto.                           |
| Repositórios Remotos    | git fetch [remote]                       | Baixa conteúdo de um repositório remoto.                |
| Commit e Histórico      | git status                               | Verifica o status das mudanças no repositório.          |
| Commit e Histórico      | git add [arquivo]                        | Adiciona mudanças ao staging.                           |
| Commit e Histórico      | git commit -m '[mensagem]'               | Realiza um commit com uma mensagem.                     |
| Commit e Histórico      | git log                                  | Mostra o histórico de commits.                          |
| Commit e Histórico      | git diff                                 | Mostra diferenças entre commits.                        |
| Branches                | git branch                               | Lista todas as branches.                                |
| Branches                | git branch [nome]                        | Cria uma nova branch.                                   |
| Branches                | git checkout [nome]                      | Muda para uma branch específica.                        |
| Branches                | git merge [branch]                       | Faz merge de uma branch na branch atual.                |
| Branches                | git branch -d [nome]                     | Deleta uma branch.                                      |
| Sincronização           | git pull                                 | Atualiza o repositório local com mudanças do remoto.    |
| Sincronização           | git push                                 | Envia commits locais para o repositório remoto.         |
| Sincronização           | git push origin [branch]                 | Envia uma branch específica para o repositório remoto.  |
| Sincronização           | git push -u origin [branch]              | Envia uma branch específica e define upstream.          |
| Desfazendo Mudanças     | git reset --hard                         | Desfaz mudanças no repositório.                         |
| Desfazendo Mudanças     | git revert [commit]                      | Reverte um commit específico.                           |
| Desfazendo Mudanças     | git checkout -- [arquivo]                | Desfaz mudanças em um arquivo no working directory.     |
| Tags                    | git tag                                  | Lista todas as tags.                                    |
| Tags                    | git tag [nome]                           | Cria uma nova tag.                                      |
| Rebase                  | git rebase [branch]                      | Rebase de uma branch em outra.                          |
| Rebase                  | git rebase --abort                       | Aborta um processo de rebase em andamento.              |
| Stash                   | git stash                                | Salva mudanças temporariamente.                         |
| Stash                   | git stash pop                            | Aplica mudanças do stash.                               |
| Stash                   | git stash list                           | Lista todas as entradas no stash.                       |

## Cheatsheet do Vim

| **Modo**          | **Comando**             | **Descrição**                                                        |
|-------------------|-------------------------|----------------------------------------------------------------------|
| **Navegação**     | `h`, `j`, `k`, `l`      | Movem o cursor para a esquerda, baixo, cima e direita, respectivamente. |
| **Normal**        | `i`                     | Entra no modo de inserção à esquerda do cursor.                     |
| **Normal**        | `a`                     | Entra no modo de inserção à direita do cursor.                      |
| **Normal**        | `o`                     | Abre uma nova linha abaixo da linha atual e entra no modo de inserção. |
| **Normal**        | `:w`                    | Salva o arquivo atual.                                              |
| **Normal**        | `:q`                    | Sai do Vim.                                                         |
| **Normal**        | `:wq`                   | Salva e sai do Vim.                                                 |
| **Normal**        | `dd`                    | Apaga a linha atual e copia para o clipboard.                       |
| **Normal**        | `yy`                    | Copia a linha atual para o clipboard.                               |
| **Normal**        | `p`                     | Cola o conteúdo do clipboard abaixo do cursor.                      |
| **Normal**        | `u`                     | Desfaz a última ação.                                               |
| **Normal**        | `Ctrl + r`              | Refaz a última ação desfeita.                                       |
| **Normal**        | `x`                     | Apaga o caractere sob o cursor.                                     |
| **Normal**        | `/texto`                | Procura por "texto" no arquivo.                                     |
| **Normal**        | `n`                     | Vai para a próxima ocorrência do texto procurado.                   |
| **Normal**        | `:%s/antigo/novo/g`     | Substitui todas as ocorrências de "antigo" por "novo" no arquivo.   |
| **Inserção**      | `Esc`                   | Sai do modo de inserção e volta ao modo normal.                     |
| **Visual**        | `v`                     | Entra no modo visual, permitindo seleção de texto.                  |
| **Visual**        | `V`                     | Entra no modo visual linha, selecionando linhas inteiras.           |
| **Visual**        | `y`                     | Copia o texto selecionado para o clipboard.                         |
| **Visual**        | `d`                     | Apaga o texto selecionado.                                          |
| **Visual**        | `>`                     | Indenta o texto selecionado à direita.                              |
| **Visual**        | `<`                     | Indenta o texto selecionado à esquerda.                             |
| **Linha de Comando** | `:help comando`      | Exibe ajuda sobre o comando especificado.                            |
| **Linha de Comando** | `:e nome_do_arquivo`  | Abre o arquivo especificado.                                        |
| **Linha de Comando** | `:split nome_do_arquivo` | Divide a janela e abre um novo arquivo na parte dividida.           |
| **Linha de Comando** | `:vsplit nome_do_arquivo` | Divide a janela verticalmente e abre um novo arquivo.               |
| **Linha de Comando** | `:tabnew nome_do_arquivo` | Abre um novo arquivo em uma nova aba.                               |
| **Linha de Comando** | `:buffers`           | Lista todos os buffers abertos.                                     |
| **Linha de Comando** | `:bnext`             | Vai para o próximo buffer.                                          |
| **Linha de Comando** | `:bprev`             | Vai para o buffer anterior.                                         |

