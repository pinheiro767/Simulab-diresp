# Roteiro Prático de Anatomia - PWA

Aplicativo com 36 questões, captura/anexo de fotos, pontuação automática, relatório PDF offline e área do professor protegida por senha.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Em **Settings > Pages**, selecione **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Aguarde a publicação e abra a URL do GitHub Pages.

## Observação de segurança
A senha e o gabarito ficam no código do aplicativo porque a correção precisa funcionar offline. Isso impede a exibição casual do gabarito na interface, mas não é segurança criptográfica contra alguém que inspecione o código-fonte. Para sigilo forte, é necessário um backend/servidor.
