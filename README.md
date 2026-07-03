# Landing Page - Vanessa Miranda Psicóloga

Landing page estática criada para publicação no GitHub Pages e uso temporário no subdomínio:

`psicologavanessamiranda.psinformatica.com.br`

## Arquivos principais

- `index.html` - estrutura da página
- `assets/css/styles.css` - estilos visuais e responsividade
- `assets/js/main.js` - menu mobile, efeito no header e animações suaves
- `assets/img/` - imagens otimizadas da logomarca e foto
- `CNAME` - domínio personalizado para GitHub Pages
- `robots.txt` e `sitemap.xml` - arquivos básicos para indexação

## Como subir no GitHub

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a branch `main`.
3. No repositório, acesse: `Settings > Pages`.
4. Em `Build and deployment`, escolha:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Salve e aguarde o GitHub publicar.

## DNS no Cloudflare

Crie um registro:

- Type: `CNAME`
- Name: `psicologavanessamiranda`
- Target: `SEU_USUARIO.github.io`
- Proxy status: inicialmente `DNS only` até o GitHub validar o domínio.

Depois da validação e HTTPS ativo no GitHub Pages, você pode avaliar ativar o proxy novamente no Cloudflare.

## WhatsApp

O número usado nos botões é:

`+55 31 97181-2563`

Link configurado no formato:

`https://wa.me/5531971812563`
