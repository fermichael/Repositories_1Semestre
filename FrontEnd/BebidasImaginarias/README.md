# BEBIDAS IMAGINÁRIAS DIFERENTES
Este projeto é um website responsivo desenvolvido com HTML, CSS e Bootstrap que apresenta um cardápio de bebidas imaginárias e únicas. O site possui navegação interativa, design moderno com gradientes, integração com redes sociais e um mapa interativo da localização fictícia do estabelecimento.

## Tecnologias e Recursos Utilizados
**Linguagens:** HTML5, CSS3, JavaScript

**Frameworks e Bibliotecas:**
- Bootstrap 5 — framework CSS responsivo
- Font Awesome 6.5.0 — ícones de redes sociais
- Bootstrap Icons — ícones adicionais
- Leaflet 1.9.4 — biblioteca para mapas interativos

**Recursos CSS:**
- Gradientes lineares (linear-gradient)
- Flexbox e Grid para layout responsivo
- Classes utilitárias do Bootstrap
- Animações e transições suaves

**Estrutura do Site:**
- Navbar responsiva com menu colapsável
- Dropdown para "Poções Especiais"
- Layout de duas colunas
- Rodapé com gradiente e links para redes sociais
- Mapa interativo (Leaflet)

**Páginas:**
- `index.html` — Página inicial
- `chaverdecooler.html` — Detalhes do Chá Verde Cooler
- `framboesageladinha.html` — Detalhes da Framboesa Geladinha
- `elixirdafelicidade.html` — Detalhes do Elixir da Felicidade

## Como usar este projeto?

### 1. Download
Baixe todos os arquivos do repositório, incluindo:
- Arquivos HTML
- Pasta `css/` (bootstrap.min.css, estilos.css)
- Pasta `js/` (bootstrap.bundle.min.js, configuracoes.js)
- Pasta `imagens/` (logo.png, drinks.png, chaverde.png, framboesageladinha.png, elixirfelicidade.png)

### 2. Estrutura de Pastas
```
projeto/
├── index.html
├── chaverdecooler.html
├── framboesageladinha.html
├── elixirdafelicidade.html
├── css/
│   ├── bootstrap.min.css
│   └── estilos.css
├── js/
│   ├── bootstrap.bundle.min.js
│   └── configuracoes.js
└── imagens/
    ├── logo.png
    ├── drinks.png
    ├── chaverde.png
    ├── framboesageladinha.png
    └── elixirfelicidade.png
```

### 3. Abrir no Navegador
- Abra o arquivo `index.html` em qualquer navegador moderno
- Navegue pelas páginas através do menu
- O site é totalmente responsivo (funciona em desktop, tablet e mobile)

## Exemplos de Funcionalidades:

**Exemplo 1: Navegação Responsiva**
```
No desktop: Menu horizontal com todos os links visíveis
No mobile: Menu colapsável com botão hambúrguer
Dropdown funcional para "Poções Especiais"
```

**Exemplo 2: Integração com Redes Sociais**
```html
<a href="https://www.instagram.com" target="_blank">
    <i class="fab fa-instagram fa-lg"></i>
</a>
```
**Resultado:** Links clicáveis para Instagram, Facebook e Twitter no rodapé

**Exemplo 3: Mapa Interativo**
```html
<div id="map" style="height: 400px;"></div>
```
**Resultado:** Mapa da "Cidade Imaginária" usando Leaflet.js

## Informações adicionais:
O projeto utiliza **CDN (Content Delivery Network)** para carregar bibliotecas externas, garantindo carregamento rápido e sempre atualizado:
- Font Awesome (ícones de redes sociais)
- Bootstrap Icons
- Leaflet (mapas interativos)

**Design Responsivo:**
- Menu colapsável em dispositivos móveis
- Grid Bootstrap para layout adaptável
- Imagens responsivas com altura fixa

**Características do Rodapé:**
- Gradiente colorido (rosa → roxo)
- Ícones de redes sociais clicáveis
- Copyright e mensagem temática

**Bebidas do Cardápio:**
1. **Chá Verde Cooler** — Vitaminas, minerais, chá verde, camomila e gengibre
2. **Framboesa Geladinha** — Suco de framboesa, capim-limão, gelo e fruto da roseira-brava
3. **Elixir da Felicidade** — Essência de vacínio, cereja e chá de flores de sabugueiro

**Contexto Acadêmico:**
Projeto desenvolvido para aprendizado de HTML, CSS, Bootstrap e integração com bibliotecas JavaScript externas.
