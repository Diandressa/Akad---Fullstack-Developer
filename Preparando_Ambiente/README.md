## NodeJS

Assistente que permite que o JavaScript funcione fora do navegador, como em um computador ou servidor.
Utiliza o mecanismo V8, motor que executa o código JS (mesmo que o Google Chrome usa).

## Formatar o Prettier

Comando:

`Control + Shift + P`

Pesquisar: Format Document with Prettier

`Shift + alt + F` para formatar

Formatar a cada save:

`Control + Shift + P` 

Pesquisar:

`Preferences: Open User Settings`

Pesquisar `save`

✅ Editor: Format On Save

## Instalar as dependências

`npm install`

## Rodar o script dev : vite

`npm run dev`

## Instalar dependências - NPM

Comando que instala as dependências.

`npm install nomeDep @16.0.0(versão)`

## Desinstalar

`npm uninstall nomeDep`

## Executar pacotes - NPX

Comando npx executa pacotes sem instalá-los permanentemente

`npx create-vite nomeProjeto --template react`

Executa o vite para criar o projeto, não instalamos a dependência do Vite (pode pedir instalação temporária de alguns pacotes).

Ainda rodamos o projeto com `npm run dev` para rodar o script.

## Yarn

Gerenciador de pacotes alternativo ao npm.

Comando para instalar o yarn no projeto:

`yarn`

Iniciar servidor vite (script: dev):

`yarn dev`

Instalar dependência com yarn ou atualizar dependência:

`yarn add nomePacote`

Remover/desinstalar pacote:

`yarn remove nomePacote`

## pNpm

Gerenciador de pacotes alternativo ao npm.

Instala pacotes em nível global, para todos os pacotes armazenadas em uma única pasta local. Os projetos consomem dessa pasta.

Documentação: https://pnpm.io/pt/installation 

No PowerShell (Como administrador):

`Invoke-WebRequest https://get.pnpm.io/install.ps1 -UseBasicParsing | Invoke-Expression`

ou

Ativar o Corepack: Corepack é uma ferramenta que vem junto com o Node.js (a partir do Node 16.13+).
👉 Ele serve para gerenciar gerenciadores de pacotes. Em vez de você instalar manualmente.

```
corepack enable
corepack prepare pnpm@latest --activate
```

Feche TODOS os terminais

Verificar a versão:

`pnpm -v`

Ir na documentação > Usage > pnpm CLI 

Ver os comando pnpm

| npm command        | pnpm equivalent |
|--------------------|-----------------|
| npm install        | pnpm install    |
| npm i <pkg>        | pnpm add <pkg>  |
| npm run <cmd>      | pnpm <cmd>      |

Para instalar pacote:

`pnpm add nomePacote -D`

pnpm comando de add: https://pnpm.io/pt/cli/add

-D - Dependência de desenvolvimento
-g - Instalar globalmente

Comandos - Desinstalar pacotes:

Documentação > Comandos > Gerenciar dependências > pnpm remove

`pnpm uninstall nomePacote`


