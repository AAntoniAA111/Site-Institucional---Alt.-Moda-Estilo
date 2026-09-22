# Alt. Moda & Estilo — Site Institucional

Este repositório contém o código-fonte e os recursos visuais do site institucional da **Alt. Moda**, um projeto focado em moda alternativa, atitude e expressão pessoal[cite: 2, 4].

## 📄 Páginas do Projeto

* **Início (`index.html`)**: Apresentação principal da marca com mensagem de boas-vindas e imagem temática da vitrine[cite: 2].
* **Sobre Nós (`sobre.html`)**: Apresenta a história da marca fundada em 2020 e o compromisso com tecidos sustentáveis e durabilidade[cite: 4].
* **Produtos (`produtos.html`)**: Catálogo da coleção em destaque exibindo itens em formato de cartões (Jaqueta Couro Classic, Vestido Preto, Corset minimalista e Saia Preta Longa) com descrições e preços[cite: 3].
* **Contato (`contato.html`)**: Informações de atendimento local na Av. Paulista, telefones, e-mail, redes sociais e horário de funcionamento[cite: 1].

## 🎨 Estilização e Design (CSS)

A folha de estilo `css/style.css` organiza o visual do site utilizando conceitos básicos e eficientes de CSS3[cite: 5]:

* **Paleta Dark/Gótica**: Fundo escuro em `#1a1a1a`[cite: 5], cabeçalho e rodapé em preto `#000000`[cite: 5] e detalhes/destaques em vermelho escuro `#8b0000`[cite: 5].
* **Tipografia**: Utilização da família de fontes `Georgia, serif` para reforçar a estética clássica e alternativa[cite: 5].
* **Interatividade**: Efeito `:hover` que altera a cor dos links do menu ao passar o ponteiro do mouse[cite: 5].
* **Layout de Produtos**: Organização dos itens em cartões (`.card`) com bordas em destaque, cantos arredondados (`border-radius`) e fundo contrastante `#2b2b2b`[cite: 5].
* **Ajuste de Mídia**: Regras de dimensionamento responsivo (`max-width: 100%`) com bordas temáticas aplicadas às imagens[cite: 5].

## 🖼️ Mídias e Imagens (`assets/`)

* `alt.jpg`: Fotografia de capa temática utilizada na página inicial e na seção "Sobre"[cite: 2, 4].
* `jaqueta.jpg`: Imagem do produto Jaqueta Couro Classic[cite: 3].
* `vestidoPreto.jpg`: Imagem do produto Vestido Preto[cite: 3].
* `corset.jpg`: Imagem do produto Corset minimalista[cite: 3].

---

## 🚀 Atualização Recente: Módulo de Avaliação da Loja

Foi adicionada a funcionalidade de **Feedback e Avaliação da Loja**, permitindo que os clientes enviem suas opiniões, sugestões e dados de contato.

### 📌 O que foi implementado:

* **Nova Página (`satisfacao.html`):**
  - Criação da página dedicada para recepção de feedback dos usuários.
  - Integração completa com o cabeçalho, menu de navegação e rodapé do site.
  - Adição da classe `.active` no item de menu *"Avalie nossa loja"* para indicar a página atual.

* **Identidade Visual e Estilização (CSS):**
  - **Estética Dark/Gothic:** Manutenção da paleta oficial com fundo preto (`#000000`), superfícies cinza escuro (`#1a1a1a`) e detalhes em vermelho escuro (`#8b0000`).
  - **Efeito Neon Red Glow:** Aplicação de `box-shadow` estilizado com brilho vermelho na caixa do formulário e botões.
  - **Acessibilidade e Contraste:**
    - Ajuste de cores nas tags `<legend>` e `<label>` para garantir alta visibilidade sobre o fundo escuro.
    - Estilização do `<textarea>` e `<input>` com texto em branco (`#ffffff`) e indicação de foco visual (`:focus`).
  - **Separação de Ações nos Botões:**
    - `.btn-enviar`: Botão principal com preenchimento em vermelho escuro.
    - `.btn-apagar`: Botão secundário em fundo preto com bordas e sombra neon vermelha.

---

## 📂 Estrutura de Arquivos

```text
meu-site/
│
├── index.html       # Página Inicial[cite: 2]
├── sobre.html       # Página Sobre a empresa[cite: 4]
├── produtos.html    # Página do catálogo de produtos[cite: 3]
├── contato.html     # Página com dados de contato[cite: 1]
│
├── css/
│   └── style.css    # Estilização geral em CSS[cite: 5]
│
└── assets/          # Imagens locais do projeto[cite: 2, 3, 4]
    ├── alt.jpg
    ├── jaqueta.jpg
    ├── vestidoPreto.jpg
    └── corset.jpg

---
