## Como instalar?
Para instalar o mkdocs é bem simples, basta digitar:
```
pip install mkdocs
```

Será necessário instalar o tema [material](https://squidfunk.github.io/mkdocs-material/getting-started/), caso for utilizar. O comando é parecido.
```
pip install mkdocs-material
```

## Comandos básicos
O mkdocs é tem 3 comandos básicos, que são eles:

- mkdocs new . ou [dir-name] *(Criar o novo projeto)*
- mkdocs serve *(Iniciar o servidor para visualizar as alterações)*
- mkdocs build ou gh-deploy
    - *build* gera a pasta com os arquivos estáticos
    - *gh-deploy* é necessário realizar o commit antes.