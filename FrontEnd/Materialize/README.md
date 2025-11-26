# MATERIALIZE CSS
Este projeto é um website responsivo desenvolvido com Materialize CSS que utiliza efeito parallax (rolagem com profundidade) para criar uma experiência visual moderna e dinâmica. O site possui navegação responsiva, ícones do Material Design, seções informativas e rodapé organizado.

## Tecnologias e Recursos Utilizados
**Linguagens:** HTML5, CSS3, JavaScript

**Frameworks e Bibliotecas:**
- Materialize CSS — framework CSS baseado em Material Design
- Google Material Icons — ícones do Google
- jQuery 2.1.1 — biblioteca JavaScript

**Recursos do Materialize:**
- Grid System responsivo (s12, m4, l6, l3)
- Navbar responsiva com sidenav (menu lateral)
- Efeito Parallax em imagens de fundo
- Sistema de cores do Material Design
- Componentes pré-estilizados

**Estrutura do Site:**
- Navbar branca responsiva com menu lateral
- 3 seções parallax com imagens de fundo
- Seção com 3 cards de ícones
- Seção "Sobre Nós"
- Rodapé com múltiplas colunas

**Efeitos Visuais:**
- Parallax scrolling (imagens se movem em velocidade diferente)
- Animações de waves (ondulação nos botões)
- Transições suaves

## Como usar este projeto?

### 1. Download
Baixe todos os arquivos do repositório, incluindo:
- `index.html`
- Pasta `css/` (materialize.min.css, estilos.css)
- Pasta `js/` (materialize.min.js, configuracao.js)
- Pasta `imagens/` (imagen01.jpg, imagen02.jpg, imagen03.jpg)

### 2. Estrutura de Pastas
```
projeto/
├── index.html
├── css/
│   ├── materialize.min.css
│   └── estilos.css
├── js/
│   ├── materialize.min.js
│   └── configuracao.js
└── imagens/
    ├── imagen01.jpg
    ├── imagen02.jpg
    └── imagen03.jpg
```

### 3. Abrir no Navegador
- Abra o arquivo `index.html` em qualquer navegador moderno
- Role a página para ver o efeito parallax
- Teste a responsividade redimensionando a janela
- No mobile, clique no ícone de menu (☰) para abrir o sidenav

## Exemplos de Funcionalidades:

**Exemplo 1: Efeito Parallax**
```html
<div class="parallax-container">
    <div class="parallax">
        <img src="imagens/imagen01.jpg" alt="Imagen 01">
    </div>
</div>
```
**Resultado:** Imagem de fundo com efeito de profundidade ao rolar a página

**Exemplo 2: Grid Responsivo**
```html
<div class="col s12 m4">
    <h2 class="center brown-text">
        <i class="material-icons">flash_on</i>
    </h2>
    <h5 class="center">Título do Ícone 1</h5>
    <p class="light">Descrição...</p>
</div>
```
**Resultado:** 
```
Mobile (s12): 1 coluna (100% da largura)
Tablet (m4): 3 colunas por linha (33% cada)
```

**Exemplo 3: Navegação Responsiva**
```html
<!-- Desktop -->
<ul class="hide-on-med-and-down right">
    <li><a href="#">Link 1</a></li>
</ul>

<!-- Mobile -->
<ul id="nav-mobile" class="sidenav">
    <li><a href="#">Link 1</a></li>
</ul>
<a href="#" data-target="nav-mobile" class="sidenav-trigger">
    <i class="material-icons">menu</i>
</a>
```
**Resultado:** Menu horizontal no desktop, menu lateral deslizante no mobile

## Informações adicionais:
O projeto utiliza o **Materialize CSS**, um framework moderno baseado nos princípios do Material Design do Google, oferecendo:
- Componentes prontos e estilizados
- Sistema de grid flexível (12 colunas)
- Animações e transições fluidas
- Design responsivo por padrão

**Sistema de Grid:**
- `s` (small) — dispositivos pequenos (mobile)
- `m` (medium) — tablets
- `l` (large) — desktops

**Ícones Utilizados:**
1. **flash_on** — Representa velocidade/rapidez
2. **group** — Representa equipe/comunidade
3. **settings** — Representa configurações/ferramentas

**Seções do Layout:**
1. **Hero Section** — Banner principal com parallax e botão CTA
2. **Features Section** — 3 cards com ícones e descrições
3. **Second Parallax** — Imagem de destaque intermediária
4. **About Section** — Texto sobre a empresa/projeto
5. **Third Parallax** — Terceira imagem de fundo
6. **Footer** — Rodapé organizado em 3 colunas

Projeto desenvolvido para aprendizado do framework Materialize CSS, efeitos parallax e design responsivo baseado em Material Design.
