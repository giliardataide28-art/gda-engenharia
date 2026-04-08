# GDA Engenharia Digital — Guia de Edição

Abra o arquivo `index.html` em qualquer editor de texto (Notepad, VS Code, etc.)
e use Ctrl+F para localizar os termos abaixo.

---

## 1. SUBSTITUIÇÕES OBRIGATÓRIAS (fazer antes de publicar)

### WhatsApp
Localizar: `[SEU_NUMERO]`
Substituir por: seu número com DDD sem espaços ou hífens
Exemplo: `32999998888`

**Quantas vezes aparece:** 8× — substitua TODAS.

### E-mail
Localizar: `[SEU_EMAIL]`
Substituir por: `giliard@gdaengenharia.com.br` (ou seu e-mail real)

### CREA-MG
Localizar: `[NÚMERO_CREA]`
Substituir por: seu número de registro no CREA-MG

---

## 2. LINKS HOTMART (produtos digitais)

| Localizar | Substituir por |
|---|---|
| `[LINK_HOTMART_CHECKLIST]` | Link do Checklist da Obra no Hotmart |
| `[LINK_HOTMART_RELATORIO]` | Link do Relatório da Calculadora no Hotmart |
| `[LINK_HOTMART_PROJETO_PRONTO]` | Link dos Projetos Prontos no Hotmart |

---

## 3. CONTADORES DO HERO (número de projetos entregues)

Localizar: `data-target="47"`
Substituir pelo número real de projetos entregues.

Localizar: `data-target="48"` — manter como está (prazo em horas).

---

## 4. PREÇOS

### Projeto Elétrico Completo
Localizar: `R$ 900 <span>/ projeto</span>`
Substituir pelo seu preço base real.

### Projeto Arquitetônico + Elétrico
Localizar: `R$ 1.500 <span>/ projeto</span>`
Substituir pelo seu preço base real.

### Produtos Digitais
Localizar: `R$ 27` (aparece 2×) e `R$ 297+`
Substituir pelos preços reais dos seus produtos Hotmart.

---

## 5. CALCULADORA — Fórmulas de preço por m²

Localizar no JavaScript:
```javascript
const rate = { simples: 65, medio: 90, alto: 130 }[padrao];
```

Substitua os valores (65, 90, 130) pelos preços médios de mão de obra + material
por m² praticados em Juiz de Fora/MG para cada padrão construtivo.

---

## 6. PORTFÓLIO — Adicionar imagens reais

Para cada card de portfólio, substitua o bloco `portfolio-placeholder` por:
```html
<img src="nome-da-imagem.jpg" alt="Descrição do projeto" loading="lazy" />
```

Coloque as imagens na mesma pasta do `index.html`.

**Tamanho recomendado:** 800×600px, formato JPG, máximo 200KB por imagem.

---

## 7. DEPOIMENTOS — Adicionar clientes reais

Localizar: `[NOME DO CLIENTE]` (aparece 3×)
Substituir pelo nome real do cliente.

Para adicionar foto real, substitua:
```html
<div class="depo-avatar">MA</div>
```
por:
```html
<img src="foto-cliente.jpg" alt="Nome Cliente" style="width:44px;height:44px;border-radius:50%;object-fit:cover" />
```

---

## 8. REDES SOCIAIS

Localizar os links `href="#"` dentro de `.footer-socials` e substitua:
- Instagram: `https://instagram.com/SEU_PERFIL`
- LinkedIn: `https://linkedin.com/in/SEU_PERFIL`
- YouTube: `https://youtube.com/@SEU_CANAL`

---

## 9. FAQ — Adicionar ou remover perguntas

Copie este bloco e cole dentro da div `.faq-list`:
```html
<div class="faq-item">
  <button class="faq-question" onclick="toggleFaq(this)">
    PERGUNTA AQUI
    <i class="fas fa-plus"></i>
  </button>
  <div class="faq-answer">
    <p class="faq-answer-inner">
      RESPOSTA AQUI
    </p>
  </div>
</div>
```

---

## 10. IDENTIDADE VISUAL

### Cores (alterar em `:root` no início do CSS)
```css
--navy:  #0A2540;   /* Azul marinho principal */
--gold:  #F0A500;   /* Dourado técnico */
```

### Logo
O logo atual usa texto (GDA.) em tipografia.
Para substituir por uma imagem, localize `.nav-logo` e substitua o conteúdo por:
```html
<img src="logo.png" alt="GDA Engenharia Digital" height="40" />
```

---

## 11. SEO — Metadados

No `<head>` do arquivo, localize e atualize:

```html
<meta name="description" content="..." />
<meta property="og:title" content="..." />
<meta property="og:description" content="..." />
```

Adicione também:
```html
<meta property="og:image" content="https://seusite.com/og-image.jpg" />
```
(imagem de 1200×630px para preview no WhatsApp e redes sociais)

---

## Dica rápida — Testar localmente

1. Abra o arquivo `index.html` diretamente no navegador (Chrome, Firefox)
2. O site funcionará 100% sem servidor
3. Apenas o formulário abrirá o WhatsApp com os dados preenchidos — teste com seu número
