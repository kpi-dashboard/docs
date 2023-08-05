
## Doku
https://squidfunk.github.io/mkdocs-material/getting-started/

## Create

docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .


## Previewing as you write

docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

## 