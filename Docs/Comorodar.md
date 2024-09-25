## Como rodar o projeto
>[!WARNING]
>Tecnologias necessárias para o projeto:<br/>
>  - Node.js
## Baixar os arquivos dos repositórios
### Baixar arquivos com o _Git_
No caso de preferir usar o _Git_ para baixar os arquivos, siga o seguinte passo:
Em uma pasta, use o seguinte comando no _cmd_ para baixar os arquivos do repositório _frontend_:
```
git clone https://github.com/BananaScripts/Meteorological-Data-Collector-Frontend.git .
```
Em outra pasta, use o seguinte comando no _cmd_ para baixar os arquivos do repositório _backend_:
```
git clone https://github.com/BananaScripts/Meteorological-Data-Collector-Backend.git .
```
 
### Baixar arquivos compactados
No caso de preferir baixar os arquivos compactados:

Frontend: [⬇️](https://github.com/BananaScripts/Meteorological-Data-Collector-Frontend/archive/refs/heads/main.zip)<br/> 
Backend: [⬇️](https://github.com/BananaScripts/Meteorological-Data-Collector-Backend/archive/refs/heads/main.zip)<br/>

Após isso basta extrair os arquivos em pastas separadas.
 
## Frontend
### Instalar dependências do projeto
Use o seguinte comando na raiz do projeto (seth/):
```
npm install
```
**AVISO**: Use o comando acima na pasta que se encontra o arquivo com as dependências (package.json)
 
## Rodar a aplicação
 
Para rodar a aplicação use o seguinte comando:
```
npm start
```
A aplicação será hospedada localmente na porta 3000 ou 3001.
 
>[!WARNING]
>*Para que algumas funcionalidades funcionem, é necessário seguir os próximos passos!.*
 
### Backend
 
### Instalar dependências do projeto
Use o seguinte comando na pasta que foi extraido ou baixado os arquivos do backend:
```
npm install
```
 
**AVISO**: Use o comando acima na pasta que se encontra o arquivo com as dependências (package.json)
 
### Rodar o servidor de controle de rotas
Na raiz do projeto, use o comando:
```
npx ts-node-dev ./server.ts
```
