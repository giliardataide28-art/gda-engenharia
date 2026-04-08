# GDA Engenharia Digital — Pendências para o Site 100% Pronto

> Atualizado em: 06/04/2026
> Status geral: Site estruturado e funcional. Faltam conteúdo real e integrações.

---

## 1. CONTEÚDO REAL

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Número do WhatsApp | Substituir `[SEU_NUMERO]` (9× no arquivo) pelo número real com DDD: ex. `32999998888` | **ALTA** |
| [ ] | E-mail de contato | Substituir `[SEU_EMAIL]` pelo e-mail real: ex. `giliard@gdaengenharia.com.br` | **ALTA** |
| [ ] | Número CREA-MG | Substituir `[NÚMERO_CREA]` pelo registro real no CREA-MG | **ALTA** |
| [ ] | Nomes dos clientes (depoimentos) | Substituir `[NOME DO CLIENTE]` (3×) por nomes reais de clientes satisfeitos | **ALTA** |
| [ ] | Textos dos depoimentos | Reescrever os 3 depoimentos com falas reais de clientes | **ALTA** |
| [ ] | Foto dos clientes (depoimentos) | Substituir avatares iniciais por fotos reais dos clientes (44×44px, círculo) | **MÉDIA** |
| [ ] | Número de projetos entregues | Substituir `data-target="47"` pelo número real de projetos entregues | **MÉDIA** |
| [ ] | Preços reais | Conferir e ajustar os preços exibidos nos cards de serviço e parcerias | **MÉDIA** |
| [ ] | Valores da calculadora | Ajustar taxas `{simples:65, medio:90, alto:130}` com base nos preços praticados em JF/MG | **MÉDIA** |

---

## 2. PORTFÓLIO

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Imagens reais dos projetos | Substituir os placeholders `portfolio-placeholder` por imagens/renders reais dos projetos | **ALTA** |
| [ ] | Projeto: Casa Residencial | Render isométrico ou foto do projeto arquitetônico/elétrico entregue | **ALTA** |
| [ ] | Projeto: Estabelecimento Comercial | Imagem real do projeto BIM | **ALTA** |
| [ ] | Projeto: Edifício Multi-familiar | Imagem real do projeto | **ALTA** |
| [ ] | Projeto: Galpão Industrial | Imagem real do projeto | **MÉDIA** |
| [ ] | Projeto: Área de Lazer | Imagem real do projeto | **MÉDIA** |
| [ ] | Projeto: Projeto Executivo | Imagem real do projeto | **MÉDIA** |
| [ ] | Tamanho das imagens | Otimizar para 800×600px, JPG, máximo 200KB cada | **ALTA** |

---

## 3. INTEGRAÇÕES

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Link Hotmart — Checklist da Obra | Substituir `[LINK_HOTMART_CHECKLIST]` pelo link real do produto no Hotmart | **ALTA** |
| [ ] | Link Hotmart — Relatório Calculadora | Substituir `[LINK_HOTMART_RELATORIO]` pelo link real do produto | **ALTA** |
| [ ] | Link Hotmart — Projetos Prontos | Substituir `[LINK_HOTMART_PROJETO_PRONTO]` pelo link real do produto | **ALTA** |
| [ ] | Backend do formulário | O formulário abre o WhatsApp — se quiser e-mail também, integrar Formspree, EmailJS ou similar | **MÉDIA** |
| [ ] | Google Analytics 4 | Adicionar tag GA4 no `<head>` para rastrear visitas, origem e conversões | **ALTA** |
| [ ] | Meta Pixel (Facebook/Instagram) | Adicionar pixel para rodar anúncios e rastrear conversões | **MÉDIA** |
| [ ] | Google Search Console | Verificar propriedade após publicar para monitorar indexação | **MÉDIA** |

---

## 4. SEO

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Imagem OG (Open Graph) | Criar imagem 1200×630px para preview no WhatsApp e redes sociais | **ALTA** |
| [ ] | Meta og:image | Adicionar `<meta property="og:image" content="URL_DA_IMAGEM" />` no `<head>` | **ALTA** |
| [ ] | Sitemap.xml | Criar `sitemap.xml` e submeter no Google Search Console | **MÉDIA** |
| [ ] | Robots.txt | Criar `robots.txt` básico permitindo indexação | **MÉDIA** |
| [ ] | Palavras-chave locais | Revisar textos para incluir "Juiz de Fora", "MG", "CREA" naturalmente | **MÉDIA** |
| [ ] | URL personalizada | Publicar em domínio próprio (ex: `gdaengenharia.com.br`) em vez do GitHub Pages | **ALTA** |

---

## 5. ANALYTICS E MONITORAMENTO

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Google Analytics 4 | Ver seção Integrações — rastrear sessões, páginas vistas, conversões | **ALTA** |
| [ ] | Evento de clique no WhatsApp | Configurar evento GA4 quando usuário clica no botão flutuante ou CTAs | **MÉDIA** |
| [ ] | Evento de abertura da calculadora | Rastrear uso da calculadora interativa como engajamento | **BAIXA** |
| [ ] | Hotjar ou Microsoft Clarity | Mapas de calor e gravação de sessões para entender comportamento | **BAIXA** |

---

## 6. LEGAL

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Política de Privacidade | Criar página ou modal com política de privacidade (LGPD) | **ALTA** |
| [ ] | Banner de cookies | Adicionar aviso de cookies compatível com LGPD | **MÉDIA** |
| [ ] | Termos de uso | Opcional: termos para os produtos digitais (Hotmart exige) | **BAIXA** |

---

## 7. REDES SOCIAIS

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Instagram | Atualizar link no footer: `https://instagram.com/SEU_PERFIL` | **ALTA** |
| [ ] | LinkedIn | Atualizar link no footer: `https://linkedin.com/in/SEU_PERFIL` | **ALTA** |
| [ ] | YouTube | Atualizar link no footer: `https://youtube.com/@SEU_CANAL` | **MÉDIA** |
| [ ] | Perfil Instagram ativo | Criar e manter perfil com fotos de projetos e bastidores | **ALTA** |
| [ ] | Perfil LinkedIn ativo | Publicar artigos técnicos e cases para autoridade | **MÉDIA** |

---

## 8. PERFORMANCE E QUALIDADE

| # | Item | Descrição | Prioridade |
|---|------|-----------|-----------|
| [ ] | Compressão de imagens | Usar TinyPNG ou Squoosh nas imagens do portfólio antes de subir | **ALTA** |
| [ ] | Teste PageSpeed Insights | Rodar Google PageSpeed após publicar e corrigir pontos críticos | **ALTA** |
| [ ] | Teste mobile real | Testar no celular (Android e iOS) — verificar navegação, calculadora e formulário | **ALTA** |
| [ ] | Teste cross-browser | Verificar Chrome, Firefox, Edge, Safari | **MÉDIA** |
| [ ] | HTTPS obrigatório | GitHub Pages já oferece HTTPS — confirmar após publicação | **ALTA** |
| [ ] | CDN para imagens | Se portfólio crescer, mover imagens para Cloudinary ou similar | **BAIXA** |

---

## RESUMO EXECUTIVO

| Categoria | Itens ALTA | Itens MÉDIA | Itens BAIXA |
|-----------|-----------|-------------|-------------|
| Conteúdo real | 4 | 5 | 0 |
| Portfólio | 4 | 3 | 0 |
| Integrações | 4 | 3 | 0 |
| SEO | 3 | 3 | 0 |
| Analytics | 1 | 2 | 2 |
| Legal | 1 | 1 | 1 |
| Redes sociais | 2 | 2 | 0 |
| Performance | 4 | 2 | 1 |
| **TOTAL** | **23** | **21** | **4** |

---

## PRÓXIMAS 3 AÇÕES IMEDIATAS

1. **Substituir `[SEU_NUMERO]`** pelo número real do WhatsApp (9 ocorrências no `index.html`)
2. **Publicar no GitHub Pages** seguindo o `README.md` — o site já está funcional
3. **Criar imagens do portfólio** — exportar renders do Revit e otimizar para web

---

*Gerado pelo AIOX — GDA Engenharia Digital*
