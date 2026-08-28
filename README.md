# Steam Madness — Landing Page

Landing page responsiva para apresentação do projeto **Steam Madness**, construída em HTML, CSS e JavaScript puro e preparada para hospedagem no GitHub Pages.

## Estrutura de pastas

```text
steam-madness-landing/
├── index.html
├── README.md
├── .gitignore
├── assets/
│   └── images/
├── css/
│   └── style.css
└── js/
    └── script.js
```

## Conteúdo implementado

- Menu de navegação com âncoras para todas as seções;
- Apresentação do jogo, contexto e diferenciais;
- Seção de personagens;
- Seção do cenário / Brasshaven;
- Carrossel funcional com materiais visuais do projeto;
- Seção de integrantes e redes sociais;
- Rodapé com o nome do game e links sociais;
- Layout responsivo para desktop, tablet e celular;
- Paleta consistente baseada na documentação visual da equipe;
- Menu mobile, animações leves e suporte a `prefers-reduced-motion`.

## Antes da entrega

A seção **Equipe** usa campos de exemplo porque os nomes e URLs dos integrantes não estavam disponíveis. Troque `Nome do integrante` e os links `href="#"` pelos dados reais.

## Como testar localmente

Você pode abrir `index.html` diretamente no navegador. Para simular uma hospedagem local:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub, por exemplo `steam-madness-landing`.
2. Dentro desta pasta, execute:

```bash
git init
git add .
git commit -m "Landing page Steam Madness"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/steam-madness-landing.git
git push -u origin main
```

3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Clique em **Save**.
7. Após o deploy, a URL terá o formato:

```text
https://SEU-USUARIO.github.io/steam-madness-landing/
```

## Paleta da equipe aplicada

- Verde: `#346739`
- Vermelho: `#7F2020`
- Laranja: `#DD8535`
- Marrom: `#5A2F16`
- Turquesa: `#0B7376`
- Cinza: `#929292`
- Amarelo: `#FFBF00`
