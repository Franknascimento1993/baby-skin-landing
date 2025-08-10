# Baby Skin – Landing Page

Landing estática pronta para deploy (Vercel/GitHub Pages/Netlify).

## Estrutura
- `index.html` — página completa, responsiva, com animações, CTA, Telegram, FAQ, Modo de uso e Sobre nós.
- `assets/` — coloque aqui suas imagens (ex.: `assets/baby-skin-hero.jpg`).

## Como publicar na Vercel (via GitHub)
1. Crie um repositório no GitHub e suba estes arquivos.
2. Acesse **vercel.com** → **Add New → Project → Import Git Repository** e escolha seu repo.
3. Configurações:
   - **Framework Preset:** `Other`
   - **Build Command:** deixe vazio
   - **Output Directory:** deixe vazio (ou `.`)
4. Clique em **Deploy**.

## Ajustes rápidos
- **Checkout:** edite os atributos `data-link` nos cards de plano para seus links reais (CartPanda, etc.).
- **Telegram:** troque `https://t.me/SEU_CANAL` pelo link real nas 3 ocorrências.
- **Imagens:** substitua os `<!-- <img ...> -->` pelos seus arquivos em `assets/`.

## Dica
Se quiser usar GitHub Pages, ative **Settings → Pages** e escolha branch `main` e pasta `/ (root)`.
