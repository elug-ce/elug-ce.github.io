# Elug CE

[![Build Status](https://travis-ci.org/elug-ce/elug-ce.github.io.svg?branch=master)](https://travis-ci.org/elug-ce/elug-ce.github.io)
[![Netlify Status](https://api.netlify.com/api/v1/badges/c2ec444d-b1b7-4c86-8c5b-5d13f2af4a4a/deploy-status)](https://app.netlify.com/sites/elug-ce/deploys)

Código-fonte do site do Elug CE. Para saber mais sobre nós, acesse nosso site, [elug-ce.github.io](https://elug-ce.github.io/sobre).

## Building

Você vai precisar ter [Ruby](https://www.ruby-lang.org/) e [Jekyll](https://jekyllrb.com/) instalados. Verifique as instruções de instalação respectivas de cada projeto.

Para rodar o projeto em modo de desenvolvimento, execute:

```
bundle exec jekyll serve
```

O site deve estar disponível localmente no endereço [localhost:4000](http://localhost:4000).

Para buildar o projeto para produção, execute:

```
bundle exec jekyll build
```

Os assets publicáveis deverão estar em uma pasta chamada `_site`.

Verifique a [documentação do Jekyll](https://jekyllrb.com/docs/) para maiores informações.

## Licença

[MIT](license)
