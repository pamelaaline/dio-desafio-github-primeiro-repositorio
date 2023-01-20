**Material foi encontrado em: https://training.github.com/**

Git é um sistema de controle de versão distribuído open source que facilita ações com o GitHub em seu notebook ou
desktop. Esta folha de dicas resume instruções comumente usadas via linha de comando do Git para referência
rápida.

**INSTALE O GIT**

GitHub fornece clientes desktop que incluem uma interface gráfica
para as ações mais comuns em um repositório e atualiza automaticamente para a linha de comando do Git para cenários avançados.

GitHub para Windows
hps://windows.github.com

GitHub para Mac
hps://mac.github.com

Distribuições do Git para Linux e sistemas POSIX são disponíveis no
site oficial do Git SCM.

Git para todas plataformas
hp://git-scm.com

**CONFIGURE A FERRAMENTA**

Configure informações de usuário para todos os repositórios locais

$ git config --global user.name "[nome]"
Configura o nome que você quer ligado as suas transações de
commit

$ git config --global user.email "[endereco-de-email]"
Configura o email que você quer ligado as suas transações de commit

$ git config --global color.ui auto
Configura o email que você quer ligado as suas transações de commit

**CRIE REPOSITÓRIOS**

Inicie um novo repositório ou obtenha de uma URL existente

$ git init [nome-do-projeto]
Cria um novo repositório local com um nome específico

$ git clone [url]
Baixa um projeto e seu histórico de versão inteiro

**FAÇA MUDANÇAS**

Revise edições e crie uma transação de commit

$ git status
Lista todos os arquivos novos ou modificados para serem commitados

$ git add [arquivo]
Faz o snapshot de um arquivo na preparação para versionamento

$ git reset [arquivo]
Deseleciona o arquivo, mas preserva seu conteúdo

$ git diff
Mostra diferenças no arquivo que não foram realizadas

$ git diff --staged
Mostra a diferença entre arquivos selecionados e a suas últimas
versões

$ git commit -m "[mensagem descritiva]"
Grava o snapshot permanentemente do arquivo no histórico de versão