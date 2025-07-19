# 📰 Portal de Notícias

![HTML](https://img.shields.io/badge/language-HTML-orange?style=for-the-badge)
![CSS](https://img.shields.io/badge/language-CSS-blue?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow?style=for-the-badge)
![React](https://img.shields.io/badge/framework-React-61DAFB?style=for-the-badge)
![IDE](https://img.shields.io/badge/IDE-VSCode-007ACC?style=for-the-badge&logo=visualstudiocode)
![Platform](https://img.shields.io/badge/platform-Web-brightgreen?style=for-the-badge)
![Build](https://img.shields.io/badge/build-Vite-646CFF?style=for-the-badge)

---

## 📌 Visão Geral

Este é um projeto colaborativo de um portal de notícias online. A proposta é criar uma plataforma moderna, responsiva e funcional onde usuários possam acessar conteúdos atualizados sobre diversos temas. Nosso foco é a cidade de Rio Pomba.

---

## 🎯 Objetivos iniciais

- Criar um site de fácil navegação e leitura.
- Aplicar práticas de desenvolvimento ágil com Git e GitHub.
- Trabalhar com versionamento organizado (branches, PRs, revisões).
- Envolver time multidisciplinar (dev, design, financeiro).

---

## 👥 Equipe

- Product Owner (PO): Guilherme Bernardino Reis
- Devs: Andrei, Guilherme, João Matheus, Richard, **Vinícius**  (Lead Developer).
- Designers: Andrei, Guilherme, **Luan** (Lead Design), Richard, Vinícius.
- Financeiro: **Andrei** (Lead Design), Henrique, José Márcio.

---

## 🚀 Primeiros passos para colaboradores

1. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/portal-noticias.git
   cd portal-noticias
   ````

2. Crie uma branch para sua tarefa:

   ```bash
   git checkout -b nome-da-branch
   ```
3. Faça alterações, commit e push:

   ```bash
   git add .
   git commit -m "descrição da alteração"
   git push origin nome-da-branch
   ```
4. Abra um **Pull Request** no GitHub para revisão e aguarde **aprovação**.

---

## ✅ Tecnologias previstas

* HTML, CSS, JavaScript
* Frameworks front-end (React)
* Integração com APIs de notícias
* Firebase, PHP
* Figma

---

## 📂 Estrutura do Projeto

workspace/portal  
│  
├── public/                  # Arquivos públicos (ícones, imagens, favicon, etc.)  
│   ├── images/  
│   ├── icons/  
│   └── index.html  
│  
├── src/  
│   ├── assets/              # Fontes, imagens e recursos estáticos  
│   ├── components/          # Componentes reutilizáveis React  
│   ├── pages/               # Páginas da aplicação  
│   ├── services/            # APIs, Firebase, etc.  
│   ├── styles/              # Estilos  
│   ├── utils/               # Funções utilitárias  
│   ├── App.jsx              # Componente principal  
│   ├── index.js             # Ponto de entrada  
│   └── routes.jsx           # Configuração de rotas  
│  
├── .gitignore               # Arquivo para ignorar arquivos/pastas no Git (não é necessário se preocupar agora)  
└── README.md                # Este documento

---

## 🧩 Padrões de Código

* **Metodologia CSS**:
  Utilizar o padrão **BEM** (Block Element Modifier) para nomeação de classes.

* **Organização de pastas**:
  Estrutura inicial recomendada: `components/`, `pages/`, `assets/`, `services/`, `styles/`, `utils/`.

* **Padrão Mobile-First**:
  O layout deve ser construído primeiro para dispositivos móveis e adaptado para telas maiores.

* **Acessibilidade**:
  Uso de boas práticas como:

  * Contraste adequado de cores
  * Texto legível
  * Uso de `alt` em imagens
  * Navegação por teclado
  * Testes com ferramentas como WAVE

* **Boas práticas de código**:

  * HTML semântico
  * CSS modularizado e reaproveitável
  * Responsividade e clareza visual
  * Componentização no React
  * Um arquivo CSS para cada arquivo .jsx

---

## 📘 Padrão de Git (Commits e Branches)

- **Criar branch**:

  ```bash
  git branch nome-da-branch
  git checkout nome-da-branch
  git checkout -b nome-da-branch # para criar e mudar de uma vez
  ```

- **Commit**:

  ```bash
  git add .
  git commit -m "mensagem clara do que foi feito"
  ```

- **Push e pull**:

  ```bash
  git push origin nome-da-branch
  git pull
  ```

- **Outras boas práticas**:

  - `git log` — histórico  
  - `git diff` — comparação de alterações  
  - `git reset` — remover do stage  
  - `git merge` — mesclar branches  
  - `git branch -d nome` — deletar branch local  
  - `git remote add origin <url>` — adicionar remoto  
  - `git remote -v` — ver remotos configurados

---

## 🔌 Extensões recomendadas no VS Code e navegador

### ✅ **Obrigatórias (VS Code)**

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Ajuda a manter o código limpo, identificando erros e padrões de má prática em JavaScript/React.

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Formata automaticamente seu código, mantendo uma padronização visual (espaços, quebras de linha, etc.).

> Estas extensões são OBRIGATÓRIAS e essenciais para garantir qualidade, organização e padronização do código.


### 🧩 **Opcionais (VS Code)**

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): Autocompleta automaticamente caminhos de arquivos e diretórios ao importar imagens, componentes, estilos e outros arquivos.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag): Renomeia automaticamente a tag de fechamento ao alterar a tag de abertura em arquivos HTML ou JSX.

- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2): Destaca colchetes, chaves e parênteses com cores distintas, facilitando a leitura de blocos de código aninhados.

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Exibe informações avançadas de Git, como autores de linha, histórico de commits, comparações entre branches e muito mais diretamente no editor.

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Mostra erros e avisos inline, com destaque visual direto nas linhas afetadas, agilizando a identificação de problemas no código.

> Estas extensões são recomendadas para melhorar produtividade e experiência no desenvolvimento, mas NÃO são obrigatórias.


### 🌐 **Extensões de navegador**

- [Responsive Viewer](https://chromewebstore.google.com/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb?hl=pt-BR&utm_source=ext_sidebar): Simula visualizações de diferentes dispositivos ao mesmo tempo (celular, tablet, desktop), ideal para testar o layout responsivo.

- [Material Icons for GitHub](https://chromewebstore.google.com/detail/material-icons-for-github/bggfcpfjbdkhfhfmkjpbhnkhnpjjeomc?hl=pt-BR&utm_source=ext_sidebar): Adiciona ícones visuais aos repositórios no GitHub, facilitando a navegação e identificação de arquivos e pastas.

- [Retire.js](https://chromewebstore.google.com/detail/retirejs/djkbihbnjhkjdocoafobidefhephglfd): Detecta bibliotecas JavaScript desatualizadas ou vulneráveis no código de páginas web. Útil para análise e segurança durante o desenvolvimento.

> Estas extensões de navegador são OPCIONAIS e visam facilitar testes e análises durante o desenvolvimento.

---

## 🔗 Links úteis 
   * Códigos prontos: https://github.com/WebdevShefali/Web-Dev-Resources?tab=readme-ov-file#web-development-resources
---

## 🎨 Padrão de Cores

Este projeto utiliza as seguintes cores principais, conforme definido no arquivo [`cores.png`](https://github.com/Guilherme-ber/Portal-de-Noticias/blob/main/cores.png):

| Código Hex | Cor Visual                                                                       |
|------------|----------------------------------------------------------------------------------|
| `#0A0A0A`  | ![#0A0A0A](https://placehold.co/15x15/0A0A0A/000000/png?text=+) Preto            |
| `#38332E`  | ![#38332E](https://placehold.co/15x15/38332E/000000/png?text=+) Cinza escuro     |
| `#FFFFFF`  | ![#FFFFFF](https://placehold.co/15x15/FFFFFF/000000/png?text=+) Branco           |
| `#FF4000`  | ![#FF4000](https://placehold.co/15x15/FF4000/000000/png?text=+) Laranja vibrante |
| `#FDDD0D`  | ![#FDDD0D](https://placehold.co/15x15/FDDD0D/000000/png?text=+) Amarelo forte    |

---

> 🛠️ Este README está em construção e será atualizado conforme o projeto evoluir.
