# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto.

## Links Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)

#### Link do artigo base:arrow_heading_down:

[Artigo do github](https://gist.github.com/leocomelli/2545add34e4fec21ec16#setar-editor)

## Comandos Utéis:desktop_computer:

####  Geral

git help

#### Comando específíco

git help add

git help commit

git help <qualquer_comando_git>

### Configuração:key:

#### Geral

As configurações do GIT são salvas no arquivo do GIT são as configurações localizadas dentro do arquivo do usuário do Sistema Operacional (Ex.: Windows: C:\Users\Documentos and Settings\ **Useronardo** ou *n /home/leondo).

As configurações apresentadas através dos comandos abaixo incluídos no arquivo citado acima.

#### Definir usuário

git config --global user.name "Rodrigo L-Silva"

#### Definir e-mail

git config --global user.email "rodrigolopessilva130102@gmail.com"

#### Editar Setar

git config --global core.editor vim

#### Setar ferramentas de mesclagem

git config merge.tool vimdiff

#### Setar arquivos a serem ignorados

gif config --global core.excludesfile ~/.gitignore

#### Listar configurações

git config --list

#### Ignorar arquivos

Os arquivos de arquivos de arquivos ou arquivos de execução não **foram** adicionados a um repositório de arquivos. Existem dois arquivos .gitignore, são eles:

- Geral: Normalmente armazenado no diretório do usuário do Sistema Operacional. Os arquivos/diretórios dos arquivos/diretores dos arquivos/diretores devem ser descritos por **todos os funcionários** anteriores. O arquivo não precisa ter o nome de **.gitignore** .
- Por: Deve ser listado armazenado no administrador dos governos/diretórios e deve conter uma administração específica dos administradores que devem ser ignorados para o substituto.

## Repositório Local

#### Novo criar recurso

git init

#### Verificar estado dos arquivos/diretórios

git status

### Adicionar arquivo/diretório (área encenada)

#### Adicionar um arquivo especifico

git add meu_arquivo.txt

#### Adicionar um diretório especifico

git add meu_diretorio

#### Adicionar todos os arquivo/diretórios

git add *

#### Adicionar um arquivo que esta na lista no .gitignore (geral ou admenistrador)

git add -f arquivo_no_gitignore.txt

### Comitar arquivo/diretório

#### Comitar um arquivo

git commit meu_arquivo.txt

#### Comitar vários arquivos

git commit meu_arquivo.txt  meu_outro_arquivo.txt

#### Comitar informando mensagem

git commit meuarquivo.txt -m "minha mensagem de commit"

### Remover arquivo/diretório

#### Remover arquivo

git rm meu_arquivo.txt

#### Remover pasta

git rm -r diretorio







