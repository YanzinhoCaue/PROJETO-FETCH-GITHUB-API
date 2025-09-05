# Projeto Github API

# 🐙 Buscador de Perfis do GitHub

Este é um projeto de front-end que utiliza a API do GitHub para buscar e exibir informações de perfis de usuários. A aplicação foi desenvolvida com **HTML5, CSS3 e JavaScript puro e moderno (ES6+)**, com foco em criar um código modular, organizado e de fácil manutenção.

---

### **🎬 Demonstração**

![githubapi](https://github.com/YanzinhoCaue/PROJETO-FETCH-GITHUB-API/assets/127339610/8a57f284-4363-46fb-bcb7-329a2645228d)

---

### **✨ Features e Destaques Técnicos**

* **JavaScript Moderno e Modular (ES6+)**:
    * O código foi totalmente estruturado com **Módulos ES6** (`import`/`export`), separando as responsabilidades em diferentes arquivos (serviços, objetos de tela, variáveis, etc.).
    * As chamadas de API são feitas com **`async/await`**, a forma mais moderna e legível de lidar com código assíncrono em JavaScript.

* **Arquitetura com Separação de Responsabilidades**:
    * **`services`**: Módulos responsáveis exclusivamente por fazer a comunicação com a API do GitHub.
    * **`objects`**: Módulos que gerenciam o estado e a renderização dos dados na tela (DOM).
    * **`index.js`**: Arquivo principal que orquestra a aplicação, lidando com os eventos do usuário (clique e Enter).

* **Integração com a API do GitHub**:
    * A aplicação consome os endpoints da API do GitHub para buscar dados do perfil do usuário e a lista de seus repositórios públicos.

* **Interface Responsiva**:
    * O layout foi construído com **Flexbox** e se adapta a diferentes tamanhos de tela através de **Media Queries**, garantindo uma boa experiência tanto em desktops quanto em dispositivos móveis.

---

### **🛠️ Tecnologias Utilizadas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style-for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

### **▶️ Como Executar o Projeto**

Por utilizar Módulos ES6, o ideal é executar o projeto através de um servidor local simples.

**1. Usando a extensão Live Server (VS Code):**
* Clone o repositório.
* Abra a pasta no VS Code.
* Clique com o botão direito no arquivo `index.html` e selecione "Open with Live Server".

**2. Abertura Direta (Pode não funcionar em todos os navegadores):**
```bash
git clone [https://github.com/YanzinhoCaue/nome-do-repositorio.git](https://github.com/YanzinhoCaue/nome-do-repositorio.git)
cd nome-do-repositorio
# Abra o arquivo index.html no navegador

(Nota: Abrir o index.html diretamente pode causar um erro de CORS em alguns navegadores devido ao uso de import de arquivos locais. O uso do Live Server é recomendado.)
🧠 Principais Aprendizados
 * Estruturação de uma aplicação vanilla JS com Módulos ES6.
 * Consumo de uma API REST de forma assíncrona com fetch e async/await.
 * Separação de responsabilidades no código (API, DOM, Eventos).
 * Criação de uma interface responsiva do zero com Flexbox e Media Queries.
💬 Contato
Yan Cauê
LinkedIn: linkedin.com/in/yancaue
GitHub: github.com/YanzinhoCaue

