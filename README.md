# GDA Engenharia Digital — Site Oficial

Site profissional completo para GDA Engenharia Digital.
Desenvolvido com HTML5 + CSS3 + JavaScript puro. Zero dependências de servidor.

---

## Como publicar no GitHub Pages (GRATUITO)

### Passo 1 — Criar repositório no GitHub
1. Acesse https://github.com e faça login
2. Clique em **New repository**
3. Nome sugerido: `gda-engenharia` (sem espaços)
4. Marque **Public**
5. Clique **Create repository**

### Passo 2 — Fazer upload dos arquivos
**Opção A — Via interface web (mais fácil):**
1. Na página do repositório criado, clique em **uploading an existing file**
2. Arraste o arquivo `index.html` para a área de upload
3. Clique **Commit changes**

**Opção B — Via Git (recomendado):**
```bash
git init
git add index.html
git commit -m "feat: site GDA Engenharia Digital"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/gda-engenharia.git
git push -u origin main
```

### Passo 3 — Ativar GitHub Pages
1. No repositório, vá em **Settings** → **Pages**
2. Em **Source**, selecione `Deploy from a branch`
3. Em **Branch**, selecione `main` e pasta `/root`
4. Clique **Save**
5. Aguarde 2-5 minutos

### Passo 4 — Acessar o site
Seu site estará disponível em:
```
https://SEU_USUARIO.github.io/gda-engenharia/
```

---

## Domínio personalizado (opcional — ~R$ 40/ano)

Para usar `www.gdaengenharia.com.br`:

1. Compre o domínio em: registro.br (recomendado) ou hostinger.com.br
2. No GitHub Pages → **Custom domain**, digite seu domínio
3. No provedor DNS, adicione os registros:
   - Tipo A: `185.199.108.153`
   - Tipo A: `185.199.109.153`
   - Tipo A: `185.199.110.153`
   - Tipo A: `185.199.111.153`
4. Aguarde até 24h para propagar

---

## Estrutura de arquivos

```
SITE_GDA/
├── index.html       ← Site completo (único arquivo necessário)
├── README.md        ← Este guia
└── COMO_EDITAR.md   ← Guia de edição de conteúdo
```

---

## Tecnologias utilizadas

| Tecnologia | Versão | Uso |
|---|---|---|
| HTML5 | — | Estrutura |
| CSS3 | — | Estilos e animações |
| JavaScript | ES6+ | Interatividade |
| Google Fonts | CDN | Playfair Display + Inter |
| Font Awesome | 6.5 | Ícones técnicos |
| AOS | 2.3.4 | Animações no scroll |

Todas as dependências são carregadas via CDN — nenhuma instalação necessária.

---

## Suporte

Dúvidas sobre publicação ou edição do site:
- Abra uma conversa com Claude Code
- Ou consulte o arquivo `COMO_EDITAR.md`
