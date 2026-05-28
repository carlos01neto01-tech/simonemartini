ARQUIVO CORRIGIDO PARA GITHUB PAGES

O erro apresentado no GitHub Actions mostra que o GitHub Pages está tentando publicar a partir da pasta /docs.
Por isso este pacote tem DUAS estruturas:

1) index.html + assets/ na raiz
2) docs/index.html + docs/assets/ também

Assim funciona tanto se o GitHub Pages estiver configurado como:
- main / root
ou
- main / docs

IMPORTANTE:
Antes de subir estes arquivos, apague arquivos antigos do repositório, principalmente:
- assets/css/style.scss
- assets/css/style.css antigo
- qualquer pasta docs antiga quebrada

Depois suba estes arquivos extraídos para a raiz do repositório.
Não suba a pasta compactada inteira nem uma pasta por fora.
