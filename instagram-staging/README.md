# Instagram Staging

Pasta pública temporária para hospedar imagens de carrosséis gerados no ChatGPT antes da publicação via Windsor.ai.

## Convenção
- Um diretório por publicação: `YYYY-MM-DD-slug/`
- Slides em JPEG: `01.jpg`, `02.jpg`, ..., `10.jpg`
- URLs públicas: `https://raw.githubusercontent.com/entrelacos-ship-it/PsiOS/main/instagram-staging/<diretorio>/<arquivo>.jpg`

## Fluxo
1. Gerar os cards no ChatGPT.
2. Converter para JPEG 1080x1350, até 8 MB.
3. Publicar os arquivos nesta pasta.
4. Enviar as URLs públicas ao `create_carousel_post` do Windsor.ai.
5. Após a publicação, os arquivos podem ser mantidos ou removidos.
