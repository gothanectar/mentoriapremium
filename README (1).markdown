# Gotha Nectar Consultoria - Mentoria Premium em Cosméticos

Bem-vindo ao repositório do site oficial da **Gotha Nectar Consultoria**, hospedado em [https://gothanectar.github.io/consultoriamentoria/](https://gothanectar.github.io/consultoriamentoria/). Este site promove mentoria premium em cosméticos, guiando empreendedores na criação de marcas únicas com inovação e conformidade Anvisa.

## Sobre o Projeto

O site foi redesenhado para um visual luxuoso e dinâmico, com paleta escura (#1a1a1a, #2e4a3b, #d4af37), bordas douradas em cards e botões, animações suaves (fade-in e hover), e fotos pré-inseridas de alta qualidade. É mobile-first, usa Tailwind CSS, Google Fonts (Playfair Display, Roboto), e é otimizado para SEO e conversão via botões WhatsApp (#25D366).

### Funcionalidades
- **Seções**: Hero, Sobre Thiago Nectar, Mentoria, Diferenciais, Soluções, Segmentos, CTA, Footer.
- **SEO**: Meta tags, schema markup (JSON-LD), sitemap.xml, robots.txt.
- **Interatividade**: Botões WhatsApp com animações, smooth scroll, efeitos hover em imagens.
- **Design**: Paleta escura com bordas douradas, gradientes vibrantes, fotos pré-inseridas.
- **Fotos**: Imagens de bancos livres (Unsplash) com instruções para substituição manual.

## Estrutura do Repositório

```plaintext
/consultoriamentoria/
├── index.html          # Página principal
├── sitemap.xml         # Sitemap para SEO
├── robots.txt          # Configuração para crawlers
├── images/             # Pasta para imagens (adicione suas imagens aqui)
│   ├── logo.png        # Placeholder para logo (substitua)
│   ├── thiago.jpg      # Placeholder para foto de Thiago Nectar
│   ├── mentoria.jpg    # Placeholder para foto da mentoria
│   ├── conexao.jpg     # Placeholder para Conexão Estratégica
│   ├── formulacao.jpg  # Placeholder para Formulação Personalizada
│   ├── terceirizacao.jpg # Placeholder para Terceirização
│   ├── fullservice.jpg # Placeholder para Full Service
│   ├── mediumservice.jpg # Placeholder para Medium Service
└── README.md           # Este arquivo
```

## Configuração e Hospedagem

### Pré-requisitos
- Conta no GitHub.
- GitHub Pages configurado para `gothanectar/consultoriamentoria`.
- Editor de texto (ex.: VS Code).

### Passos para Hospedagem
1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/gothanectar/consultoriamentoria.git
   cd consultoriamentoria
   ```
2. **Faça Upload dos Arquivos**:
   - Adicione `index.html`, `sitemap.xml`, `robots.txt`, e imagens em `/images/`.
   - Commit e push:
     ```bash
     git add .
     git commit -m "Atualiza site com novo design e fotos"
     git push origin main
     ```
3. **Configure o GitHub Pages**:
   - Em "Settings" > "Pages", selecione a branch `main` e pasta `/root`.
   - Verifique: https://gothanectar.github.io/consultoriamentoria/.

### Configuração de SEO no Google Search Console
1. **Adicione a Propriedade**:
   - Acesse https://search.google.com/search-console.
   - Adicione https://gothanectar.github.io/consultoriamentoria/ (Prefixo de URL).
   - Verifique com meta tag no `<head>` do `index.html` ou outro método.
2. **Submeta o Sitemap**:
   - Em "Sitemaps", insira: `https://gothanectar.github.io/consultoriamentoria/sitemap.xml`.
   - Envie e verifique o status.
3. **Valide o Robots.txt**:
   - Em "Configurações" > "Verificador de robots.txt", confirme acesso a https://gothanectar.github.io/consultoriamentoria/robots.txt.
4. **Inspeção de URL**:
   - Use "Inspeção de URL" para verificar indexação e solicitar, se necessário.

## Otimização de SEO
- **Palavras-Chave**: "mentoria cosméticos", "consultoria cosméticos", "terceirização cosméticos", "Thiago Nectar", "full service cosméticos", "medium service cosméticos", "formulação cosméticos", "criar marca cosméticos".
- **Meta Tags**: Otimizadas para CTR e relevância.
- **Schema Markup**: JSON-LD para "Organization" com dados de contato.
- **Monitoramento**: Use "Resultados de Pesquisa" no GSC para ajustar palavras-chave.

## Personalização
1. **Substituir Imagens**:
   - As imagens atuais são placeholders do Unsplash. Para substituir:
     - Faça upload das suas imagens na pasta `/images/` (ex.: `thiago.jpg`, `mentoria.jpg`).
     - Atualize os caminhos no `index.html`. Exemplo:
       ```html
       <img src="https://gothanectar.github.io/consultoriamentoria/images/thiago.jpg" alt="Thiago Nectar Consultoria Cosméticos" class="w-full h-64 object-cover rounded-lg">
       ```
     - Imagens incluídas:
       - Thiago Nectar: https://images.unsplash.com/photo-1544717305-996b08c7a4f7
       - Mentoria: https://images.unsplash.com/photo-1576765607924-3a916f2181c1
       - Conexão Estratégica: https://images.unsplash.com/photo-1620331294259-87c0ebb3a99d
       - Formulação: https://images.unsplash.com/photo-1596462502278-27bfdc403348
       - Terceirização: https://images.unsplash.com/photo-1580870060932-8d2a39b09899
       - Full Service: https://images.unsplash.com/photo-1600585154340-be6161a56a0c
       - Medium Service: https://images.unsplash.com/photo-1583394833716-3b6a0a7b8f69
     - Commit as mudanças:
       ```bash
       git add images/
       git commit -m "Atualiza imagens personalizadas"
       git push origin main
       ```
   - Atualize o logo no schema markup:
     ```json
     "logo": "https://gothanectar.github.io/consultoriamentoria/images/logo.png"
     ```
2. **Cores**:
   - Paleta: #1a1a1a, #2e4a3b, #d4af37. Ajuste no `<style>` do `index.html`.
3. **Conteúdo**:
   - Edite o texto da mentoria ou seções no `index.html`.
   - Considere páginas adicionais (ex.: `/mentoria`) para mais palavras-chave.

## Atualizações
- **Conteúdo**: Atualize `index.html` e `<lastmod>` no `sitemap.xml`.
- **Sitemap**: Ressuba no GSC após alterações.
- **Imagens**: Comprima para melhor velocidade (teste em https://pagespeed.web.dev/).

## Contato
- **WhatsApp**: (41) 99823-3408
- **Endereço**: Rua Presidente Castelo Branco, 707, Colombo, PR, CEP 83412-580

© 2025 Thiago Nectar Cosméticos. Todos os direitos reservados.