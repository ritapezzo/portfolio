# Portfólio Profissional — Rita Pezzo

**Aluna:** Rita de Cássia Pezzo de Magalhães  
**Curso:** Desenvolvimento de Sistemas - Centro Paula Souza 

**Link do site publicado:** https://ritapezzo.github.io/portfolio/ 🚀

## Descrição do portfólio 🌞

Desenvolvi este portfólio como parte da Atividade da Agenda 15 para apresentar meu perfil, as tecnologias que estudo e os projetos que realizei durante o curso. A página se adapta a telas de computadores e celulares.
Projeto realizado com o auxlio do ChatGpt.

## 🛠️Tecnologias utilizadas 🛠️

- **HTML5:** estrutura da página, das seções e dos links.
- **CSS3:** personalização de cores e ajuste das imagens.
- **Bootstrap 5.3.3:** menu responsivo, carrossel, cards e botões.
- **JavaScript:** fechamento do menu no celular e tratamento de erros no carregamento das imagens.
- **Devicon:** ícones das tecnologias.

## Como o projeto funciona 🪄

A barra de navegação leva às seções **Perfil**, **Projetos** e **Contato**. Em telas menores, os links ficam dentro de um menu que pode ser aberto por um botão. Logo abaixo da barra, o carrossel alterna três banners automaticamente e também pode ser controlado pelas setas e pelos indicadores.

Na seção **Perfil**, apresento minha formação, meus interesses e as ferramentas que utilizo. A seção **Projetos** reúne o próprio portfólio, o sistema de monitoramento do nível de água em Python e o Portal de Entretenimento Digital. O botão do portfólio volta ao carrossel, e os outros dois botões abrem os respectivos repositórios no GitHub. A seção **Contato** tem links para e-mail, GitHub e LinkedIn. O rodapé fecha a página com os créditos do projeto.

## Recurso novo: conteúdo alternativo para imagens 🕵️

Adicionei um recurso com o auxilio da IA para evitar que o carrossel, o perfil e os cards de projetos fiquem com uma imagem quebrada. Se uma imagem não carregar, o carrossel mostra um bloco colorido com o número do slide, o perfil mostra minhas iniciais e os cards exibem um ícone.

## Como implementei o recurso

Logo depois de cada imagem no HTML, coloquei um elemento alternativo com o atributo `hidden`. Quando ocorre um erro de carregamento, o evento `onerror` oculta a imagem e revela o elemento seguinte usando `nextElementSibling`. O CSS mantém o espaço reservado para a imagem e centraliza o conteúdo alternativo.

## Correções feitas a partir da apostila

- **Menu responsivo (p. 12):** escrevi `data-bs-target="#menu"` sem a quebra no nome do atributo. Assim, o botão aponta para o menu correto.
- **Link de contato (p. 15):** corrigi `href="#contatos"` para `href="#contato"`, que corresponde ao `id` da seção.
- **Indicadores do carrossel (p. 16):** reuni o atributo `data-bs-slide-to`, que aparecia partido em duas linhas. Os valores `0`, `1` e `2` selecionam os três slides.
- **Cards do perfil (p. 22):** corrigi `<<div` para `<div` na abertura da linha que agrupa os cards.
- **Estrutura da página (p. 10 e 18):** mantive uma única abertura `<body class="bg-light">` e incluí o JavaScript do Bootstrap antes de `</body>`, conforme a etapa do carrossel.
<br>
<br>


![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge)
![ChatGPT](https://img.shields.io/badge/ChatGPT-10A37F?style=for-the-badge)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://ritapezzo.github.io/portfolio/)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)