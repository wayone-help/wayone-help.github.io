
## Para executar o projeto

```
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## Rotina de atualização

```
# Mate a instância do docker
git commit -m ...
git pull origin master
# Vai dar conflito na pasta _site
git checkout --theirs _site/caminho/do/arquivo
# Rode o docker novamente para compilar
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
git add .
git commit 
git push origin master
```
