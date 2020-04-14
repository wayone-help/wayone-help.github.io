
## Para executar o projeto

```
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## Rotina de atualização

```
git add .
git commit -m '[MOD]: tutorial xyz'
git pull origin master
git push origin master
```
