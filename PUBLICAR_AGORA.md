# GDA Engenharia Digital — Publicar Hoje

> Site pronto. Siga este guia para publicar em menos de 15 minutos.

---

## STATUS DO SITE

| Item | Status |
|------|--------|
| Paleta branco/verde Apple | ✅ Aplicada |
| Copy baseado nas 5 dores | ✅ Feito |
| 3 cards de produto (sem abas) | ✅ Feito |
| Produtos digitais (seção separada) | ✅ Feito |
| Parcerias — sem eletricista, sem preços | ✅ Feito |
| Depoimentos DN Projetos, Pro Arq, RN Eng | ✅ Feito |
| WhatsApp (16) 9 97970166 em todos os CTAs | ✅ Feito |
| Calculadora paleta verde | ✅ Feito |
| Imagens de marketing integradas | ✅ Feito |
| Nenhuma menção a plugin ou IA | ✅ Verificado |

---

## PUBLICAÇÃO — GITHUB PAGES (GRATUITO)

### Passo 1 — Criar conta e repositório

1. Acesse **github.com** e crie uma conta (se ainda não tiver)
2. Clique em **New repository**
3. Nome: `gda-engenharia` (sem espaços, sem acentos)
4. Marque **Public**
5. Clique **Create repository**

### Passo 2 — Fazer upload dos arquivos

Na página do repositório criado:

1. Clique em **uploading an existing file**
2. Arraste **TODA A PASTA** `SITE_GDA` para a área de upload:
   - `index.html`
   - Pasta `IMAGENS MARKETING/` com todas as imagens
3. Mensagem de commit: `Site GDA Engenharia Digital v1`
4. Clique **Commit changes**

### Passo 3 — Ativar GitHub Pages

1. No repositório → **Settings** → **Pages**
2. Em **Source**: selecione `Deploy from a branch`
3. Em **Branch**: selecione `main` e pasta `/root`
4. Clique **Save**
5. Aguarde 3–5 minutos

### Passo 4 — Acessar o site

```
https://SEU_USUARIO.github.io/gda-engenharia/
```

---

## DOMÍNIO PRÓPRIO — FUTURO (R$ 40/ano)

Para usar `www.gdaengenharia.com.br`:

1. Compre o domínio em: **registro.br** (recomendado) ou hostinger.com.br
2. No GitHub Pages → **Custom domain**: digita `www.gdaengenharia.com.br`
3. No painel DNS do provedor, adicione:
   ```
   Tipo A: 185.199.108.153
   Tipo A: 185.199.109.153
   Tipo A: 185.199.110.153
   Tipo A: 185.199.111.153
   ```
4. Aguarde até 24h para propagar

---

## O QUE AINDA FALTA PREENCHER

O site está pronto para publicar. Após publicar, preencha:

### Obrigatório antes de divulgar:
| Onde | O que preencher |
|------|----------------|
| `index.html` → footer | `[SEU_EMAIL]` → seu e-mail real |
| `index.html` → footer | `[NÚMERO_CREA]` → seu registro CREA-MG |
| `index.html` → footer e redes sociais | URLs do Instagram, LinkedIn, YouTube |
| `index.html` → Ferramentas Digitais | `[LINK_HOTMART_CHECKLIST]` → link real do Hotmart |

### WhatsApp já configurado:
- Número: **(16) 9 97970166** — em todos os 12 botões do site ✅

### Para adicionar depois:
- Google Analytics 4 (rastrear visitas)
- Meta Pixel (Facebook/Instagram Ads)
- Imagem OG (1200×630px para preview no WhatsApp)
- Política de Privacidade (LGPD)

---

## TESTAR ANTES DE PUBLICAR

Abra o `index.html` diretamente no Chrome:

1. Verifique se as imagens da pasta `IMAGENS MARKETING` aparecem
2. Teste a calculadora — mova os sliders
3. Clique em um CTA do WhatsApp — deve abrir com o número correto
4. Clique em uma foto do portfólio — deve abrir o lightbox
5. Reduza a janela para testar o mobile
6. Abra o FAQ — clique nas perguntas

---

## CONTATO DE SUPORTE

Dúvidas sobre publicação: abra conversa com Claude Code.

---

*GDA Engenharia Digital — Site pronto para publicar em 07/04/2026*
