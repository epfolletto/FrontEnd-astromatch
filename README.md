# `Projeto`
Projeto Astromatch

# `Link`
[Clique aqui!](https://folletto-astromatch.surge.sh)

# `Descrição`
[Projeto desenvolvido na semana 10 do curso Labenu]. </br>
O Projeto Astromatch foi desenvolvido como uma atividade dentro do curso Full-Stack Web Developer da Labenu, o qual consiste em requisições para a API* desenvolvida pela equipe da Labenu, via axios. </br>
Trata-se de uma ferramenta baseada no aplicativo de encontros Tinder, onde o usuário escolhe entre as opções "like" e "dislike" e então lhe é mostrada uma lista de perfis que deram "match". </br>
Os métodos utilizados para realizar este projeto foram: </br>
**Get Profile To Choose:** retorna um perfil que ainda não foi visto por você. </br>
**Get Matches:** retorna um array de perfis que deram match com você. </br>
**Choose Person:** envia a informação que você deu like em um determinado perfil. </br>
**Clear:** limpa todos os matches e perfis vistos. </br>

*https://documenter.getpostman.com/view/7549981/SW12yx56?version=latest </br>

# `Modo de usar`
Ao iniciar a ferramenta, o usuário pode escolher entre as opções "Sobre" e "Astromatch". Na opção "Sobre" é mostrada uma breve descrição do projeto. Já a opção "Astromatch" leva o usuário para a aplicação em si, onde são listados perfis (com as informações de nome, foto, idade e descrição) um de cada vez para o usuário, que tem a opção de dar "like" ou "disklike":
- Caso o usuário optar por "dislike", nada ocorre e um novo perfil é mostrado na tela.
- Caso o usuário optar por "like" e o perfil atual também deu "like" para o usuário (essa informação vem da API), uma mensagem de "match" é exibida na tela e este perfil é inserido em uma lista de matches (tarefa também feita pela API). </br>

No canto superior direito existe um ícone que leva o usuário para a tela de matches e lá é exibida uma lista de matches. Caso a lista esteja vazia, uma mensagem indicando tal situação é mostrada. </br>
Ao finalizar a lista de perfis disponíveis, uma mensagem é exibida e o usuário deve resertar a lista e pode iniciar novamente o processo de "likes" e "dislikes", para isso, um botão "Resetar" é apresentado no lugar do botões de "like" e "dislike".

# `Instalando e rodando o projeto`
Fazer o clone do projeto:
- git clone link-do-repositório

Instalar as dependências:
- npm install

Rodar o projeto:
- npm run start

# `Tecnologias utilizadas`
<div>
<img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white">
  <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white">
</div>

# `Autor`
Evandro Paulo Folletto
</br>
<a href="https://www.linkedin.com/in/evandrofolletto/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> <a href="https://github.com/epfolletto"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> 
</br>

# `Imagens`

### Tela inicial:
<img src="./src/assets/img/readme/site1.png"/>

### Tela Sobre:
<img src="./src/assets/img/readme/site2.png"/>

### Tela Perfis:
<img src="./src/assets/img/readme/site3.png"/>

### Tela Matches:
<img src="./src/assets/img/readme/site4.png"/>
