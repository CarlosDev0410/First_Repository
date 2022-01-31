###      COMANDOS BÁSICOS:

- **cd 'Nome da pasta'**  - Entra no diretório desejado

- **cd ..** - Retorna ao diretório anterior

- **mkdir 'Nome da pasta'** - Cria uma Pasta

- **rmdir /s /q** - Deleta a pasta de destino e todo seu conteúdo

- **del** - deleta apenas os arquivos da pasta

- **echo > 'nome'** - Cria um arquivo

- **ls** - Listar

- **ls -a** - Lista arquivos ocultos

- **clear** - Limpar tela

- **pwd** - Exibir caminho de destino

- **mv 'objeto' 'destino'** - Move arquivos para pasta de destino

  ### CRIANDO CHAVE SHA1:

  ##### *Digite no git bash:*

  **openssl sha1 'nome'**

  **ssh-keygen -t 'emai' -C ** - Gera chave

  

  **eval $ ssh-agent -s** 

  **ssh-add 'Chave gerada' ]** - Habilita Chave

  

  ### COMANDOS PARA COMMIT

  - **git init** - inicializa o repositório

  - **git add * ** - Move para o modo de staging

  - **git status** - Status do Repositório

  - **git commit -m** **"nome"** - Comita Repositório

    

  

  ### COMANDOS LIGADOS COM O REPOSITÓRIO REMOTO "GitHub"

  - **git remote add origin 'link do repositório'** - Seleciona link de destino

  - **git remote -v** - Exibe o link do repositório

  - **git push origin master** - Empurra Repositório local para o remoto

  - **git pull origin master** - Puxa repositório

  - **git clone 'link do repo'** - Clona o repositório remoto para o Local

    

  ### COMANDOS DE CONFIGURAÇÃO GIT

  - **git config --list** - Lista as configurações
  - **git config --global --unset 'opção'** - Remove os dados configurados
  - **git config --global 'opção'** - Edita Configuração

  
