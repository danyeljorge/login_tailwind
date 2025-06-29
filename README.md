# Landing Page de Login com Tailwind CSS

Este projeto apresenta uma landing page moderna e responsiva com um formulário de login integrado, desenvolvida utilizando HTML e estilizada com **Tailwind CSS**.

---

### 🚀 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica da página.
* **Tailwind CSS:** Framework CSS utilitário para estilização rápida e responsiva.

---

### ✨ Funcionalidades

* **Design Responsivo:** A página se adapta a diferentes tamanhos de tela (desktop, tablet, mobile).
* **Seção de Landing Page:** Área dedicada com título, descrição e um botão de call-to-action ("Saiba Mais").
* **Formulário de Login:**
    * Campos para "Seu melhor e-mail" e "Senha".
    * Botão "Entrar".
    * Link para "Não tem Cadastro? Cadastre-se".
* **Navegação Superior:** Barra de navegação com links para "Home", "Sobre", "Serviços", "FAQ" e "Contatos", além de uma barra de pesquisa.
* **Estilo Moderno:** Cores gradientes, tipografia limpa e layout organizado, proporcionando uma experiência de usuário agradável.

---

### 🛠️ Como Executar o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/danyeljorge/login_tailwind.git
    cd login_tailwind # Substitua pelo nome da pasta do seu projeto
    ```

2.  **Instale as dependências do Tailwind CSS:**
    Certifique-se de ter o [Node.js](https://nodejs.org/en/download/) e o [npm](https://www.npmjs.com/get-npm) (ou [yarn](https://yarnpkg.com/getting-started/install)) instalados em sua máquina.
    ```bash
    npm install -D tailwindcss postcss autoprefixer
    ```

3.  **Compile o CSS do Tailwind:**
    O Tailwind CSS precisa ser compilado para gerar o arquivo CSS final que o seu HTML irá utilizar.

    **Primeiro, certifique-se de que seu `package.json` possui um script para compilar o Tailwind.** Se você seguiu as instruções básicas de instalação do Tailwind, ele pode se parecer com isto:

    ```json
    // package.json (exemplo de seção de scripts)
    "scripts": {
      "dev": "tailwindcss -i ./src/input.css -o ./src/output.css --watch"
    }

    ```
       **Então, execute o script para compilar o CSS:**
    ```bash
    npm run build:css
    ```
  ---

### 📷 Screenshot

![Landing Page de Login](/src/tailwind.jpg)

---

### 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, encontrar bugs ou quiser adicionar novas funcionalidades, sinta-se à vontade para:

1.  Abrir uma [Issue](https://github.com/danyeljorge/login_tailwind) descrevendo o problema ou a sugestão.
2.  Criar um [Pull Request](https://github.com/danyeljorge/login_tailwind/pulls) com suas alterações.

---

### 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
