# Atividade 2 - SEO

## Palavras-chave escolhidas
- cenário br de e-sports
- setup competitivo e-sports
- counter-strike 2 e valorant brasil

## O que foi feito no projeto
- **Title, description e canonical:** cada página (`index.html` e `setup.html`) recebeu um `title` e uma `meta description` próprios voltados para as palavras-chave, além da tag `canonical` com a URL completa.
- **Open Graph e favicon:** adicionei as meta tags `og:type`, `og:title`, `og:description`, `og:url`, `og:locale` e `og:image`, junto com um `favicon.svg` na raiz.
- **Dados estruturados:** inseri o JSON-LD do tipo `WebSite` no `<head>` da página inicial e validei no Schema Markup Validator.
- **Segunda página e links internos:** criei a página `setup.html` para detalhar a parte de equipamentos e treino, ligando as duas páginas com textos de link descritivos.
- **Imagens:** mantive `alt`, `width` e `height` em todas e coloquei `loading="lazy"` nas imagens que ficam abaixo da primeira dobra.
- **Indexação:** adicionei `robots.txt` e `sitemap.xml` na raiz do repositório.

## Notas do Lighthouse (Celular)

| Categoria      | Antes | Depois |
| Desempenho     | 88    | 99     |
| Acessibilidade | 100   | 100    | 
| Boas práticas  | 96    | 100    |
| SEO            | 91    | 100    |