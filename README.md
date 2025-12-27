# Site Institucional - Landing Page

## 📋 Índice

- [Introdução](#introdução)
- [Anatomia do Projeto](#anatomia-do-projeto)
- [Estrutura de Pastas](#estrutura-de-pastas)
- [Componentes Principais](#componentes-principais)
- [Fluxo de Trabalho](#fluxo-de-trabalho)
- [Detalhes dos Componentes](#detalhes-dos-componentes)
- [Deployment](#deployment)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## 🎯 Introdução

Bem-vindo ao repositório do **Site Institucional - Landing Page**! Este projeto é uma página de destino moderna e responsiva, desenvolvida para apresentar uma instituição ou empresa de forma profissional e atrativa. 

### Objetivo Principal

O projeto foi concebido para criar uma presença digital impactante, oferecendo aos visitantes uma experiência intuitiva e visualmente atraente que comunique efetivamente os valores, serviços e diferenciais da instituição.

### Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização avançada com Flexbox e Grid
- **JavaScript**: Interatividade e funcionalidades dinâmicas
- **Design Responsivo**: Suporte total para dispositivos móveis, tablets e desktop

### Características Principais

✨ Interface moderna e limpa  
📱 Totalmente responsiva (mobile-first)  
⚡ Performance otimizada  
♿ Acessibilidade WCAG 2.1  
🎨 Design profissional e customizável  
📈 SEO-friendly  

---

## 🏗️ Anatomia do Projeto

### O que é Anatomia?

A anatomia do projeto descreve os diferentes sistemas e componentes que trabalham juntos para formar a aplicação. Cada elemento foi cuidadosamente estruturado para garantir:

- **Manutenibilidade**: Código organizado e fácil de compreender
- **Escalabilidade**: Capacidade de adicionar novas funcionalidades
- **Reutilização**: Componentes modulares e reutilizáveis
- **Performance**: Otimização de recursos e carregamento rápido

### Pilares Estruturais

#### 1. **Camada de Apresentação (HTML)**
- Estrutura semântica do conteúdo
- Marcação acessível e bem organizada
- Tags HTML5 modernas

#### 2. **Camada de Estilo (CSS)**
- Design system consistente
- Variáveis CSS para temas e cores
- Media queries para responsividade
- Animações e transições suaves

#### 3. **Camada de Interatividade (JavaScript)**
- Funcionalidades dinâmicas
- Manipulação do DOM
- Eventos do usuário
- Validações e integrações

#### 4. **Camada de Recursos (Assets)**
- Imagens otimizadas
- Ícones e fontes
- Mídia e vídeos
- Arquivos de configuração

---

## 📂 Estrutura de Pastas

```
landing-page-site-institucional/
│
├── 📄 index.html                 # Página principal
├── 📄 README.md                  # Este arquivo
├── 📄 .gitignore                 # Configuração Git
│
├── 📁 assets/                    # Recursos estáticos
│   ├── 📁 images/               # Imagens do projeto
│   │   ├── logo.png
│   │   ├── banner.jpg
│   │   ├── team/                # Fotos da equipe
│   │   └── services/            # Ícones de serviços
│   │
│   ├── 📁 icons/                # Ícones SVG
│   │   ├── menu.svg
│   │   ├── search.svg
│   │   └── social/              # Ícones de redes sociais
│   │
│   ├── 📁 fonts/                # Fontes personalizadas
│   │   ├── roboto-regular.woff2
│   │   └── opensans-bold.woff2
│   │
│   └── 📁 videos/               # Vídeos e animações
│       └── intro.mp4
│
├── 📁 css/                      # Estilos CSS
│   ├── style.css                # Arquivo principal
│   ├── variables.css            # Variáveis e temas
│   ├── responsive.css           # Media queries
│   ├── animations.css           # Keyframes e transições
│   │
│   └── 📁 components/           # Estilos por componente
│       ├── header.css
│       ├── hero.css
│       ├── services.css
│       ├── team.css
│       ├── testimonials.css
│       ├── contact.css
│       └── footer.css
│
├── 📁 js/                       # Scripts JavaScript
│   ├── main.js                  # Script principal
│   ├── utils.js                 # Funções auxiliares
│   │
│   └── 📁 modules/              # Módulos específicos
│       ├── navbar.js            # Navegação
│       ├── slider.js            # Carrossel/slider
│       ├── form.js              # Validação de formulário
│       ├── scroll.js            # Efeitos de scroll
│       └── analytics.js         # Rastreamento
│
└── 📁 docs/                     # Documentação adicional
    ├── guia-contribuicao.md
    ├── guia-estilo.md
    └── changelog.md
```

### Descrição das Pastas Principais

| Pasta | Descrição |
|-------|-----------|
| **assets/** | Contém todos os recursos estáticos (imagens, ícones, fontes, vídeos) |
| **css/** | Todos os arquivos de estilo, organizados por componente |
| **js/** | Scripts JavaScript, divididos em módulos reutilizáveis |
| **docs/** | Documentação adicional e guias de desenvolvimento |

---

## 🧩 Componentes Principais

### 1. **Header / Navbar**
- Logotipo da instituição
- Menu de navegação responsivo
- Ícone de menu mobile (hamburger)
- Informações de contato rápido

### 2. **Hero Section**
- Banner principal com imagem/vídeo de fundo
- Título impactante e subtítulo
- Call-to-action (CTA) principal
- Animações de entrada

### 3. **Sobre (About)**
- Breve história da instituição
- Missão, Visão e Valores
- Imagens representativas
- Estatísticas principais

### 4. **Serviços**
- Grid de serviços oferecidos
- Descrição breve de cada serviço
- Ícones representativos
- Links para detalhes

### 5. **Equipe**
- Cards com membros da equipe
- Foto, nome, cargo e bio
- Links de redes sociais
- Efeitos hover

### 6. **Depoimentos / Testimonials**
- Carrossel de depoimentos de clientes
- Foto do cliente, nome e empresa
- Classificação por estrelas
- Transições suaves

### 7. **Formulário de Contato**
- Campos de entrada validados
- Validação HTML5 e JavaScript
- Feedback visual de erros
- Integração com serviço de e-mail

### 8. **Footer**
- Links rápidos
- Informações de contato
- Redes sociais
- Copyright e política de privacidade

---

## 🔄 Fluxo de Trabalho

### Fluxo do Usuário

```
Usuário Visita a Página
        ↓
   [Header/Navbar]
        ↓
   [Hero Section]
   (Primeiro contato)
        ↓
   [Sobre]
   (Conhecer a instituição)
        ↓
   [Serviços]
   (Entender ofertas)
        ↓
   [Equipe]
   (Conhecer as pessoas)
        ↓
   [Depoimentos]
   (Ganhar confiança)
        ↓
   [Contato]
   (Ação desejada)
        ↓
   [Footer]
   (Informações adicionais)
```

### Fluxo de Desenvolvimento

1. **Planejamento**: Definição de requisitos e design
2. **Estrutura**: Criação do HTML semântico
3. **Estilo**: Implementação do CSS e responsividade
4. **Interatividade**: Adição de JavaScript
5. **Otimização**: Performance e SEO
6. **Testes**: Validação em diferentes navegadores
7. **Deploy**: Publicação da aplicação

---

## 🔍 Detalhes dos Componentes

### Componente: Header/Navbar

**Arquivo Principal**: `css/components/header.css` + `js/modules/navbar.js`

**Funcionalidades**:
- Menu responsivo com animação
- Submenu ativo baseado em scroll
- Toggle mobile com animação smooth
- Classes dinâmicas baseadas em scroll

**HTML Estrutura**:
```html
<header class="header">
  <nav class="navbar">
    <div class="navbar-container">
      <a href="#home" class="logo">Logo</a>
      <ul class="nav-menu">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">Sobre</a></li>
        <li><a href="#services">Serviços</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
      <div class="hamburger">
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
  </nav>
</header>
```

---

### Componente: Hero Section

**Arquivo Principal**: `css/components/hero.css`

**Funcionalidades**:
- Background image/video responsivo
- Overlay com opacidade controlável
- Animação de entrada do conteúdo
- CTA animado com hover

**Características Visuais**:
- Altura 100vh em desktop
- Ajustável em mobile
- Gradiente overlay
- Texto centralizado

---

### Componente: Serviços

**Arquivo Principal**: `css/components/services.css` + `js/modules/scroll.js`

**Funcionalidades**:
- Grid responsivo (3 colunas em desktop, 1 em mobile)
- Cards com efeito hover
- Animação de entrada ao scroll
- Ícones SVG escaláveis

**Estrutura**:
```html
<section class="services" id="services">
  <h2>Nossos Serviços</h2>
  <div class="services-grid">
    <div class="service-card">
      <img src="assets/icons/service.svg" alt="Serviço">
      <h3>Serviço 1</h3>
      <p>Descrição do serviço</p>
    </div>
  </div>
</section>
```

---

### Componente: Formulário de Contato

**Arquivo Principal**: `css/components/contact.css` + `js/modules/form.js`

**Funcionalidades**:
- Validação HTML5 + JavaScript
- Feedback visual de erro/sucesso
- Sanitização de dados
- Integração com API de e-mail
- Proteção contra spam (reCAPTCHA)

**Validações**:
- Nome: Mínimo 3 caracteres
- E-mail: Formato válido
- Mensagem: Mínimo 10 caracteres
- Campos obrigatórios

---

### Componente: Carrossel de Depoimentos

**Arquivo Principal**: `js/modules/slider.js` + `css/components/testimonials.css`

**Funcionalidades**:
- Navegação anterior/próximo
- Indicadores (dots)
- Auto-play opcional
- Transições suaves
- Responsivo

**Controles**:
```javascript
// Exemplo de uso
const slider = new Slider({
  container: '.testimonials-slider',
  interval: 5000, // 5 segundos
  autoplay: true
});
```

---

## 🚀 Deployment

### Opções de Deployment

#### 1. **GitHub Pages**

**Vantagens**:
- Gratuito
- Fácil de configurar
- Integrado com Git

**Passos**:
1. Fazer push para a branch `gh-pages`
2. Ativar GitHub Pages nas configurações do repositório
3. URL: `https://seu-usuario.github.io/landing-page-site-institucional`

#### 2. **Netlify**

**Vantagens**:
- Deploy automático via Git
- Suporte a serverless functions
- Certificado SSL gratuito

**Passos**:
1. Conectar repositório ao Netlify
2. Configurar build settings (se necessário)
3. Deploy automático a cada push

#### 3. **Vercel**

**Vantagens**:
- Performance otimizada
- CDN global
- Deploy instantâneo

**Passos**:
1. Importar projeto no Vercel
2. Configurações automáticas
3. Deploy com um clique

#### 4. **Hospedagem Compartilhada / Dedicada**

**Vantagens**:
- Domínio personalizado
- Controle total do servidor
- Suporte técnico

**Passos**:
1. Contratar plano de hospedagem
2. FTP/SFTP ou Git deploy
3. Configurar DNS e certificado SSL

### Checklist de Pré-Deploy

- [ ] Validar HTML com W3C Validator
- [ ] Testar CSS em navegadores principais
- [ ] Otimizar imagens
- [ ] Minificar CSS/JS
- [ ] Verificar links internos
- [ ] Testar formulário
- [ ] Configurar meta tags SEO
- [ ] Adicionar robots.txt
- [ ] Gerar sitemap.xml
- [ ] Testar em dispositivos móveis
- [ ] Verificar performance com PageSpeed Insights
- [ ] Configurar Google Analytics
- [ ] Configurar certificado SSL

---

## 🤝 Contribuição

### Como Contribuir

Agradecemos por considerar contribuir para este projeto! Aqui está como você pode ajudar:

### Passo 1: Fork o Repositório

```bash
# Clique no botão "Fork" no GitHub
```

### Passo 2: Clone o Repositório

```bash
git clone https://github.com/seu-usuario/landing-page-site-institucional.git
cd landing-page-site-institucional
```

### Passo 3: Crie uma Branch

```bash
git checkout -b feature/sua-funcionalidade
# ou
git checkout -b fix/seu-bug-fix
```

### Passo 4: Faça suas Alterações

- Mantenha o código limpo e bem organizado
- Siga o guia de estilo do projeto
- Adicione comentários explicativos quando necessário

### Passo 5: Teste suas Alterações

```bash
# Abra o arquivo index.html em seu navegador
# ou use um servidor local:
python -m http.server 8000
# Acesse: http://localhost:8000
```

### Passo 6: Commit e Push

```bash
git add .
git commit -m "feat: descrição clara da mudança"
git push origin feature/sua-funcionalidade
```

### Passo 7: Abra um Pull Request

1. Vá para seu fork no GitHub
2. Clique em "New Pull Request"
3. Descreva suas alterações
4. Aguarde review

### Diretrizes de Contribuição

#### Commits

- Use mensagens claras e descritivas
- Use prefixos: `feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `test:`
- Exemplo: `feat: adicionar seção de testimonials`

#### Código

- Indentação: 2 espaços
- Nomes descritivos para classes e variáveis
- Evite variáveis globais
- Comente código complexo

#### HTML

```html
<!-- ✅ BOM -->
<section class="services" id="services">
  <div class="services-container">
    <h2>Nossos Serviços</h2>
  </div>
</section>

<!-- ❌ RUIM -->
<div class="main">
  <div class="s1">
    <h2>Services</h2>
  </div>
</div>
```

#### CSS

```css
/* ✅ BOM */
.button {
  display: inline-block;
  padding: 10px 20px;
  background-color: var(--primary-color);
  transition: all 0.3s ease;
}

.button:hover {
  transform: translateY(-2px);
}

/* ❌ RUIM */
.btn { padding: 10px 20px; background: blue; }
.btn:hover { transform: scale(1.05); }
```

#### JavaScript

```javascript
// ✅ BOM
function initializeSlider(element) {
  // Inicializa o slider
  const slider = new Slider(element);
  return slider;
}

// ❌ RUIM
function init(el) {
  // inicia
  let s = new Slider(el);
}
```

### Padrões de Branch

- `main` - Branch de produção (estável)
- `develop` - Branch de desenvolvimento
- `feature/*` - Novas funcionalidades
- `fix/*` - Correções de bugs
- `docs/*` - Atualizações de documentação

### Processo de Review

Todos os Pull Requests serão:
1. Revisados quanto à qualidade do código
2. Testados em múltiplos navegadores
3. Verificados quanto à performance
4. Validados quanto à acessibilidade

### Reportar Bugs

Se encontrar um bug:

1. Verifique se o bug já foi reportado
2. Abra uma Issue com:
   - Descrição clara do problema
   - Passos para reproduzir
   - Comportamento esperado
   - Seu ambiente (navegador, sistema operacional)
   - Screenshots/prints

### Sugestões de Melhoria

Tem uma ideia? Abra uma Issue com a tag `enhancement` descrevendo:
- O problema que resolve
- Sua solução proposta
- Benefícios esperados

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 📞 Contato e Suporte

- **Issues**: Use a seção de Issues para reportar problemas
- **Discussions**: Participe de discussões no repositório
- **Email**: Entre em contato através do formulário no site

---

## 🙏 Agradecimentos

Agradecimentos especiais a todos os contribuidores, designers e desenvolvedores que tornaram este projeto possível!

---

## 📚 Recursos Adicionais

- [Guia de Contribuição Detalhado](docs/guia-contribuicao.md)
- [Guia de Estilo](docs/guia-estilo.md)
- [Changelog](docs/changelog.md)
- [W3C HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- [PageSpeed Insights](https://pagespeed.web.dev/)

---

**Última atualização**: 27 de dezembro de 2025

**Mantido com ❤️ por [Adriano1976](https://github.com/Adriano1976)**
