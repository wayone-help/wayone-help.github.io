
## Para executar o projeto

```
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## Rotina de atualização

```
# Mate a instância do docker
git checkout -- _site
git add .
git commit -m '[MOD]: tutorial xyz'
git pull origin master
# Rode o docker novamente para compilar
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
git add .
git commit 
git push origin master
```
