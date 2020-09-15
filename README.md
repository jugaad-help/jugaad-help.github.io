
## Execução

```
docker run -p 8080:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## Atualização

```
git add .
git commit -m '[MOD]: alterações'
git push origin master
```
