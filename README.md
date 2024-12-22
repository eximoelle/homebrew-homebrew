# Eximoelle Homebrew

Здесь находятся некоторые кастомные рецепты для Homebrew.

## Установка

`brew install eximoelle/homebrew/<formula>`

## Содержание

### Yandex Cloud CLI

`brew install eximoelle/homebrew/yandex-cloud-cli`

Возвращает рецепт по установке YC CLI к виду в коммите [3794a9c](https://github.com/Homebrew/homebrew-cask/commit/3794a9c4b0b51d0f0e752d446fd2a29eb1765837). Здесь при каждом обновлении и новой установке файлы автодополнений линкуются по правильным путям, как это принято в любой утилите, где есть автодополнения. В результате любые плагины Zsh Completition корректно компилируют их. И не нужно загромождать свой `.zshrc` лишними строками, как предлагают разработчики. По каким-то причинам эти полезные изменения были выброшены из официального репозитория Homebrew под видом фикса.

## Документация

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
