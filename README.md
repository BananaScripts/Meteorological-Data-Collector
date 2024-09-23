<br id="inicio">

<h1 align="center">API 2024.2 - SETH</h1>
 <p align="center">
     <a href="#sobre">Sobre</a> •
     <a href="#comorodar">Como rodar o projeto</a> •
     <a href="#tecnologias">Ferramentas e Tecnologias</a> •
     <a href="#entregas">Entregas</a> • 
     <a href="#backlog">Backlogs e User Stories</a> •
     <a href="#documentacao">Documentação</a> •
     <a href="#equipe">Equipe</a> 
</p>

# 👋Hello! Nós somos o grupo BananaScript
Nós somos estudantes da <a href='https://fatecsjc-prd.azurewebsites.net/'>FATEC de São José dos Campos</a>e estamos no 4º semestre de Desenvolvimento de Software e multiplataformas.



<span id="sobre">

### Sobre o projeto:
<p>A Tecsus é uma startup que se especializa na coleta e processamento de dados utilizando redes de sensores sem fio, também conhecidas como Internet das Coisas (IoT). Esses dados são aplicados em setores como abastecimento de água, distribuição de eletricidade e gás natural. Com o objetivo de diversificar seu portfólio para incluir o monitoramento ambiental e integrar alunos do Ensino Médio em uma abordagem de aprendizagem baseada em problemas, a Tecsus decidiu criar estações meteorológicas acessíveis e de baixo custo.</p>
<p>Para garantir o sucesso desse projeto, é essencial que os dados enviados pelos sensores sejam coletados e processados de forma que possam ser exibidos em um portal, com relatórios e dashboards. Além de fornecer informações e incluir conceitos matemáticos para o cálculo dos parâmetros, o sistema também visa demonstrar a importância do monitoramento ambiental. Isso é feito através da geração de alertas, ajudando a prevenir possíveis desastres naturais.
</p>

## Link dos repositórios
<p>Link do repositório do Front-end: <a href="https://github.com/BananaScripts/Meteorological-Data-Collector-Frontend/tree/main">https://github.com/BananaScripts/Meteorological-Data-Collector-Frontend/tree/main</a></p>

<p>Link do repositório do Back-end: <a href="https://github.com/BananaScripts/Meteorological-Data-Collector-Backend/tree/main">https://github.com/BananaScripts/Meteorological-Data-Collector-Backend/tree/main</a></p>


 #### Status do projeto: Em Desenvolvimento ⏳
  

<a href="/Docs/Comorodar.md">Como rodar o projeto</a>

 <br>
 
 <span id="tecnologias">
 
 ### Ferramentas e Tecnologias⚒️
 
 <p align="center"> 
<img src="https://img.shields.io/badge/Figma-5751D3?style=for-the-badge&logo=figma&logoColor=EDF0F9"/>
<img src="https://img.shields.io/badge/CSS3-5751D3?style=for-the-badge&logo=css3&logoColor=EDF0F9"/> 
<img src="https://img.shields.io/badge/HTML5-5751D3?style=for-the-badge&logo=html5&logoColor=EDF0F9"/> 
<img src="https://img.shields.io/badge/React-5751D3?style=for-the-badge&logo=react&logoColor=EDF0F9"/> 
<br> 
<img src="https://img.shields.io/badge/JavaScript-5751D3?style=for-the-badge&logo=javascript&logoColor=EDF0F9"/>
<img src="https://img.shields.io/badge/Node.js-5751D3?style=for-the-badge&logo=nodedotjs&logoColor=EDF0F9"/>
<img src="https://img.shields.io/badge/TypeScript-5751D3?style=for-the-badge&logo=typescript&logoColor=EDF0F9"/> 
<img src="https://img.shields.io/badge/MySQL-5751D3?style=for-the-badge&logo=mysql&logoColor=EDF0F9"/> 
</p> 
  
<br>

<span id="entregas">

### Entregas✅

Sprint ID | Data | Status |
----------|------| --------|
#1 | 09.09.2024 - 29.09.2024 | ❌
#2 | 30.09.2024 - 20.10.2024 | ❌
#3 | 21.10.2024 - 10.11.2024 | ❌
#4 | 11.11.2024 - 01.12.2024 | ❌

<br>

<span id="backlog">
 
 ## User Stories📖


### Gerenciamento de Estações
1. **Como administrador**, quero poder cadastrar novas estações meteorológicas, fornecendo informações como nome, localização e UUID, para que elas possam começar a enviar dados ao sistema.
2. **Como administrador**, quero uma interface intuitiva onde possa visualizar e gerenciar todas as estações cadastradas, permitindo verificar suas informações.
3. **Como administrador**, quero poder editar as informações de uma estação já cadastrada, como nome ou localização, para manter os dados sempre atualizados e refletir mudanças no ambiente físico.
4. **Como administrador**, quero poder excluir uma estação meteorológica do sistema, para remover estações que não estão mais em uso.

### Gerenciamento de Parâmetros
1. **Como administrador**, quero poder definir e configurar os tipos de parâmetros monitorados por cada estação, para garantir que cada estação colete os dados adequados de forma padronizada.
2. **Como administrador**, quero poder editar os tipos de parâmetros monitorados por cada estação, para ajustar as medições conforme necessário.
3. **Como administrador**, quero poder visualizar uma lista dos tipos de parâmetros com suas unidades de medida, nome e fator, para revisar ou ajustar as configurações conforme necessário.
4. **Como administrador**, quero poder excluir tipos de parâmetros específicos, caso não sejam mais necessários para o monitoramento das estações.

### Gerenciamento de Alertas
1. **Como administrador**, quero poder configurar alertas baseados nos tipos de parâmetros monitorados, para que o sistema me avise quando valores críticos forem atingidos.
2. **Como usuário**, quero receber notificações automáticas quando um alerta for acionado, para que eu possa tomar as medidas necessárias.
3. **Como administrador**, quero que o sistema registre automaticamente os alertas gerados, com informações como o parâmetro que os causou, o valor registrado e a hora do evento.
4. **Como administrador**, quero poder visualizar um histórico dos alertas gerados, para revisar eventos anteriores e identificar padrões ou problemas recorrentes.

### Gerenciamento de Usuários
1. **Como administrador**, quero poder cadastrar novos usuários, fornecendo nome, email e senha, para que o sistema tenha controle de permissões e acesso seguro.
2. **Como administrador**, quero poder visualizar uma lista de todos os usuários cadastrados no sistema, com detalhes como nome e nível de acesso, para monitorar quem tem acesso ao sistema.
3. **Como administrador**, quero poder editar as informações de um usuário já cadastrado, como o nome ou senha, para manter os dados sempre atualizados e garantir a segurança do acesso.
4. **Como administrador**, quero poder excluir usuários do sistema, para remover o acesso de pessoas que não devem mais utilizar a plataforma.

### Recepção dos Dados das Estações Meteorológicas
1. **Como administrador**, quero que o sistema receba os dados enviados pelas estações meteorológicas, para que eles sejam processados e armazenados corretamente.
2. **Como sistema**, preciso identificar corretamente cada estação através de seu UUID e registrar a data e hora do envio dos dados, para garantir a consistência e rastreabilidade das informações.

### Tratamento dos Dados Coletados pelas Estações
1. **Como sistema**, preciso processar e organizar os dados recebidos, descartando informações desnecessárias, para que apenas os parâmetros relevantes sejam armazenados.

### Dashboards para Visualização dos Parâmetros Meteorológicos
1. **Como usuário**, quero visualizar os dados coletados das estações meteorológicas através de dashboards, para monitorar as condições climáticas de forma eficiente.

### Educação para Estudantes
1. **Como usuário**, quero acessar textos que expliquem o significado de cada parâmetro meteorológico, para entender os conceitos monitorados pelas estações.

### Criação das Telas
1. **Como usuário**, quero telas navegáveis que me permitam visualizar explicações sobre os parâmetros meteorológicos e os dados coletados das estações em dashboards, para uma experiência educativa integrada.



<br>

### DoD e DoR
DoR (Definition of Ready) | DoD (Definition of Done) |
-------------------------|---------------------------|
As User Stories devem estar claras, e o design da interface deve estar finalizado.| O sistema permite cadastrar, editar, visualizar e excluir estações. Os dados são validados corretamente, a interface é intuitiva.| 
Parâmetros, unidades de medida e requisitos de validação devem estar definidos, além do design da interface de configuração finalizado. | O sistema permite gerenciar parâmetros com validação adequada. | 
Critérios de alerta, notificações e histórico devem estar especificados, com o design da interface pronto.| O sistema configura alertas, envia notificações automáticas e registra o histórico. |
Campos de cadastro e regras de validação, níveis de acesso e design da interface devem estar definidos. | O sistema permite o gerenciamento de usuários, com validações corretas e interface funcional. | 
Conteúdo educativo (textos explicativos sobre parâmetros meteorológicos) deve estar pronto. Estrutura de navegação e design das telas definidas. | O sistema apresenta textos explicativos de maneira clara e acessível, permitindo que os usuários entendam os conceitos dos parâmetros monitorados. As telas de navegação estão funcionando corretamente, e a documentação foi concluída. |
Estrutura dos dashboards definida| Os dashboards com os dados dos parâmetros monitorados pelas estações devem ser exibidos

<span id="documentacao">
 
 ### Documentação📄
 
<h4>Modelo de Dados</h4>
<br>
<img src="./Docs/Images/ModeloBD_API-Kickoff.png" width="1000"/>
<br>
<h4>Arquitetura do Projeto</h4>
<br>
<img src="./Docs/Images/Arquitetura_BananaScript.png" width="1000"/>
<br>

<br>

<span id="equipe">

### Equipe👨‍💻:

| Nome | LinkedIn | Github |
|:-----:|:----------:|:---------:|
| Bruno Fernandes |<a href='https://www.linkedin.com/in/bruno-campos-97560b231/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://www.github.com/BrunoFerCam'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Douglas Medeiros |<a href='https://www.linkedin.com/in/douglas-ferrini-medeiros-02b735270'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://www.github.com/DouglasMedeiros1'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Gustavo Borges  |<a href='https://www.linkedin.com/in/gustavo-borges-lima-855440243/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://github.com/Miojoguu'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Kaue Riki |<a href='https://www.linkedin.com/in/kau%C3%AA-riki-70b518273/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://github.com/kaueriki'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Lucca Vilela |<a href='https://www.linkedin.com/in/lucca-vilela-b90730232/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://github.com/luccavilela'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Miguel Conde |<a href='https://www.linkedin.com/in/miguel-conde-santos-a67313271/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://github.com/miguelcondesantos'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>
| Gabriel Henrique Siqueira |<a href='https://www.linkedin.com/in/gabriel-siqueira-54b535279/'><img src='https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white'></a>|<a href='https://github.com/GaSiqueira'> <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'></a>


<br>

> Instituição: Fatec São José dos Campos - Prof. Jessen Vidal
> 
> Curso: Desenvolvimento de Software Multiplataforma/4º Semestre
 
<br>
 
<a href="#inicio">[Voltar ao início]</a>
