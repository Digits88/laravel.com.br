Guia para contribuição
======================

## Seu próprio fork
Primeiramente, faça seu [fork](https://help.github.com/articles/fork-a-repo) do repositório [LaravelBrasil/laravel.com.br](https://github.com/LaravelBrasil/laravel.com.br). É nele que você deve fazer as modificações primeiramente. Depois de clonar seu fork adicione o remote do repositório original ao seu ambiente com o comando.
```
git remote add upstream https://github.com/LaravelBrasil/laravel.com.br.git
```

## Enviando contribuições

Segue uma sugestão de ciclo de trabalho:

### 1. Mantenha o branch master do seu fork atualizado

Com o conteúdo do LaravelBrasil/laravel.com.br

```
git checkout master
git fetch upstream
git merge upstream/master
```

### 2. Crie um branch

Crie um branch para suas novas modificações

```
git-checkout -b <nome-do-branch>
```

### 3. Faça suas alterações

Faça as alterações e os **commits** que forem necessários no seu branch

### 4. Envie um Pull Request

Envie um [Pull Request](https://help.github.com/articles/using-pull-requests) do seu branch para o branch **DEVELOPMENT** do repositório LaravelBrasil/laravel.com.br. Seja descritivo no seu Pull Request, explique o que há de novo.

## Organização e guidelines

Para mantermos o código limpo, estável e com qualidade algumas guidelines são necessárioas para pull requests de qualidade:

- **Branch:** Pull requests devem ser enviados ao branch `development`. Então tenha certeza de escolher o alvo do pull request corretamente antes de apertar 'Send'.
- **Descrição:** Seja descritivo no seu Pull request. Explique do que se trata pelo menos. Sabendo aonde você quer chegar fica muito mais facil fazer o code-review.
- **Testes:** [TODO]
