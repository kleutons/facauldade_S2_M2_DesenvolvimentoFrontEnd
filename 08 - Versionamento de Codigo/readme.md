# Versionamento de código:
-  É um processo que permite controlar e gerenciar mudanças em um projeto, mantendo um histórico completo de todas as alterações no código-fonte.

## As vantagens do versionamento de código incluem:
- *Rastreabilidade:* você pode manter um histórico de todas as mudanças que fez.
- *Organização:* facilita a manutenção do seu código.
- *Colaboração:* permite o trabalho em conjunto com outras pessoas.
- *Segurança:* reduz o risco de perda de mudanças importantes.

## Ferramentas de versionamento de código disponíveis. Três das mais famosas são:
- *Subversion* (mantida pela Apache Foundation)
- *Mercurial e Git* (desenvolvido por Linus Torvalds, criador do kernel do Linux).

## Algumas Plataformas baseadas em Git:
- GitHub (mantido pela Microsoft)
- GitLab
- BitBucket

## Configuração do usuário Git
- Para trabalhar com projetos Git, é importante configurar o seu nome de usuário e e-mail. Isso ajuda a identificar quem fez modificações específicas em um projeto.
- No terminal do VS Code, digite os seguintes comandos:
- Para configurar o nome de usuário, digite:
  > git config --global user.name “seu nome”

- Para configurar o e-mail, digite:
  > git config --global user.email “seu e-mail”

Nota: Substitua “seu nome” e “seu e-mail” pelos seus dados reais.

# Abertura do Projeto no VS Code
- Abra o Visual Studio Code. Clique em “File” (Arquivo), depois “Open Folder” (Abrir Pasta). Navegue até a pasta do seu projeto e selecione-a. O projeto agora está aberto no VS Code.

## Iniciar o Git no Projeto
- Abra o terminal do VS Code (Menu “View” > “Terminal” ou use o atalho Ctrl + ). Digite git init. Isso inicia o versionamento de código do Git para o seu projeto. - Ao executar o comando git init, uma pasta oculta chamada .git é criada na pasta do projeto. Essa pasta armazena todo o histórico de versões do seu projeto.

## Adicionar Arquivos ao Git
- No terminal do VS Code, digite git add … Esse comando adiciona todos os arquivos e pastas do projeto ao Git para serem monitorados. O comando git add . não é o mais apropriado para todos os casos. Por exemplo, diretórios como o vendor, que normalmente contêm bibliotecas, não são versionados. Mas, para fins didáticos, usaremos esse comando para adicionar todos os arquivos neste momento.

## Verificar o Status do Git: 
- No terminal do VS Code, digite git status. Este comando exibe o status atual do projeto no Git. Seus arquivos agora estão listados como “new file”, pois foram adicionados ao Git.

## Fazer o Primeiro Commit
- No terminal do VS Code, digite git commit -m “commit inicial”. O comando git commit persiste todas as alterações rastreadas. O parâmetro -m é seguido pela mensagem do commit entre aspas, que descreve as mudanças feitas. Você agora criou a primeira versão do seu projeto.

## Fazer Alterações no Projeto e Rastreá-las
- Faça algumas alterações em seus arquivos. Por exemplo, você pode mudar o texto de algumas seções. Após fazer as alterações, digite git status novamente para ver o status atual. Seus arquivos modificados agora estão listados como “modificados”. Você pode usar git diff nome_do_arquivo para ver exatamente o que foi modificado em cada arquivo. Quando estiver satisfeito com as alterações, digite git add nome_do_arquivo para rastrear as alterações. 
Digite:
> git commit -m “descrição das alterações” para persistir as alterações.

## Verificar o Histórico do Git
- No terminal do VS Code, digite git log. Este comando exibe o histórico de todos os commits feitos no projeto.
- Lembre-se, os comandos mais importantes para iniciar o rastreamento do seu projeto são git init, git add, git commit e git status. Utilize git log para revisar o histórico do projeto.