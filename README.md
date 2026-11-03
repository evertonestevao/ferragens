# Ferraço Forte – Site institucional

## Rodar localmente
```
npm install
npm run dev
```
Abra o endereço mostrado (ex.: http://localhost:5173).

## Gerar versão para publicar
```
npm run build
```
Os arquivos finais ficam na pasta `dist/`.

## Publicar na internet
- **Netlify:** arraste a pasta `dist/` em https://app.netlify.com/drop
- **Vercel:** importe o projeto; build `npm run build`, saída `dist`.
- **Hospedagem comum (cPanel/FTP):** envie o conteúdo de `dist/` para a pasta `public_html`.

## Personalizar
Edite `index.html`: troque nome, telefone (procure `5511900000000`), Instagram e as fotos (links `loremflickr.com`).
