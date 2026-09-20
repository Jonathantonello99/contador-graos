# Contador de Graos Web

Aplicativo de contagem pela webcam, executado no Chrome com OpenCV.js. Nao requer Python.

## Publicar pelo GitHub Pages sem programar

1. Entre em https://github.com e crie um repositorio, por exemplo `contador-graos`.
2. Extraia este ZIP.
3. No repositorio, use **Add file > Upload files** e envie **todo o conteudo da pasta extraida**, inclusive `.github`.
4. Confirme o upload para a branch `main`.
5. Abra **Settings > Pages**.
6. Em **Build and deployment > Source**, selecione **GitHub Actions**.
7. Abra a aba **Actions** e aguarde o workflow `Deploy GitHub Pages` ficar verde.
8. Em **Settings > Pages**, abra o endereco publicado. Ele normalmente segue o formato:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
9. Abra esse endereco no Chrome e permita acesso a camera.

## Uso
1. Escolha a camera integrada ou USB.
2. Deixe a superficie vazia e clique `1. CALIBRAR FUNDO`.
3. Coloque 5 a 30 graos separados e clique `2. CALIBRAR OBJETOS`.
4. Coloque a amostra completa.

## Observacoes
- O processamento da imagem ocorre localmente no navegador.
- `opencv.js` e carregado da documentacao oficial do OpenCV, entao e necessario acesso a internet ao abrir o aplicativo.
- O GitHub Pages fornece o HTTPS necessario para o Chrome permitir a webcam em uma pagina publicada.
