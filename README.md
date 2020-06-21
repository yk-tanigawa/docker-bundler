# docker-bundler

A Ruby Bundler Docker Images. This container execute a bundler install in a working folder

## Docker Compose example

```
bundler:
    image: yosuketanigawa/bundler
    volumes:
        - ./:/app
    working_dir: /app
```

## change log

- 2020/6/20: folked from [webfatorial/docker-bundler](https://github.com/webfatorial/docker-bundler) and configure [locale to UTF8](https://github.com/jekyll/jekyll/issues/4268)

