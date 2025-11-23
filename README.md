# ☁️ ClimaTS

## Aplicativo de Previsão do Tempo com OpenWeatherMap API

Projeto desenvolvido durante a **Imersão Dev com Alura e Google**, focado na integração e consumo de dados de uma API de serviços meteorológicos em tempo real.

O **ClimaTS** é uma aplicação simples e eficiente que permite ao usuário buscar a previsão do tempo para diversas cidades, exibindo informações como temperatura, umidade e condições climáticas atuais, utilizando a API **OpenWeatherMap**.

---

## ✨ Tecnologias Utilizadas

* **HTML5:** Estrutura base da interface do usuário.
* **CSS3:** Estilização e design responsivo.
* **JavaScript (Vanilla JS):** Lógica principal, requisições HTTP assíncronas e manipulação de dados em JSON.
* **OpenWeatherMap API:** Fonte de dados para a busca e recuperação das informações meteorológicas.

---

## 🚀 Como Funciona

1.  O usuário insere o nome da cidade no campo de busca.
2.  O JavaScript constrói a URL da requisição, incluindo o nome da cidade e a chave da API (necessária para acesso à OpenWeatherMap).
3.  É realizada uma requisição assíncrona (`fetch`) para a API.
4.  A resposta (JSON) é processada para extrair os dados relevantes (temperatura, descrição, ícone, etc.).
5.  Os resultados são formatados e exibidos dinamicamente na tela, fornecendo a previsão atualizada.

---

## 🔗 Acessar o Projeto

Você pode interagir e testar a aplicação online através do Google Sites:

* **Demonstração Online (Google Sites):**
    [https://sites.google.com/view/imersaodevalura2025aula3/aula-3](https://sites.google.com/view/imersaodevalura2025aula3/aula-3)

> **⚠️ Observação sobre Hospedagem:** O projeto está hospedado no Google Sites porque o GitHub Pages pode impor restrições (políticas de CORS) ao tentar fazer requisições diretas a APIs externas como a OpenWeatherMap. O código fonte, no entanto, está completo e funcional neste repositório.

---

## 🛠️ Como Executar Localmente

Para rodar o projeto em sua máquina:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/lleonardo553/imersao-dev-alura-2025-aula-3.git](https://github.com/lleonardo553/imersao-dev-alura-2025-aula-3.git)
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd imersao-dev-alura-2025-aula-3
    ```
3.  Abra o arquivo `index.html` em seu navegador.
    *(**Importante:** Dependendo do seu navegador, pode ser necessário rodar o projeto usando um servidor local, como a extensão Live Server do VS Code, para evitar bloqueios de segurança ao fazer requisições de API.)*

---

## 🙋 Contribuidor

**Lleonardo 553** - [@lleonardo553](https://github.com/lleonardo553)

---

## 🙏 Agradecimentos

Este projeto foi desenvolvido como parte do aprendizado da **Imersão Dev** da **Alura** em colaboração com o **Google**.
