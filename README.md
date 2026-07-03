# Vanessa Miranda Psicóloga

Landing page estática para GitHub Pages, com seção de depoimentos representativos, FAQ, sobre mim e chamada para WhatsApp.

## Publicação no GitHub Pages

1. Suba todos os arquivos para a raiz do repositório `psicovanessamiranda`.
2. Vá em `Settings > Pages`.
3. Em `Build and deployment`, selecione:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Salve e aguarde o deploy em `Actions` ficar verde.

## Domínio personalizado futuramente

Quando for apontar o subdomínio no Cloudflare, crie um arquivo `CNAME` na raiz com:

```text
psicologavanessamiranda.psinformatica.com.br
```

No Cloudflare, use:

```text
Tipo: CNAME
Nome: psicologavanessamiranda
Destino: pedrinns0610.github.io
Proxy: DNS only inicialmente
```

Depois configure o mesmo domínio em `Settings > Pages > Custom domain`.

## Ajuste desta versão

- Banner e menu revisados para dispositivos móveis.
- Cards flutuantes do banner agora se reorganizam no celular, sem sobrepor o conteúdo.
- Logo do menu ajustada para não ser cortada em telas pequenas.
