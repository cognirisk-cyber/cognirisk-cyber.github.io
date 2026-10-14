# CogniRisk — VANT

Site de apresentação do **VANT**, a plataforma de cibersegurança da
**CogniRisk**: controles, vulnerabilidades, pentest, acessos e incidentes num
só lugar, da operação à diretoria.

Página estática: `index.html`, o CSS e as imagens em `static/`. Sem build e
sem dependência — o GitHub Pages serve como está.

## Publicar

1. Envie o conteúdo desta pasta para a branch `main` de um repositório.
2. Em **Settings › Pages**, escolha **Deploy from a branch**, `main`, pasta
   `/ (root)`.

O `.nojekyll` faz o GitHub Pages servir os arquivos como estão, sem passar
pelo Jekyll.

## Domínio

O site responde em `cognirisk.com.br`. O arquivo `CNAME` diz isso ao GitHub
Pages — **ele não pode sumir** numa atualização, senão o domínio se desliga do
site. O certificado HTTPS é emitido pelo próprio GitHub Pages (Let's Encrypt)
e não vai na pasta.
