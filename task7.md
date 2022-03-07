### Создание сайта с помощью Hugo

1. Установка Hugo

2. Создание сайта

```
hugo new site quickstart
```

3. Добавление темы оформления

```
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
```

Добавление темы в конфигурации сайта:

```
echo theme = \"ananke\" >> config.toml
```

4. Добавление страниц

```
hugo new posts/page.md
```

5. Запуск сервера

```
hugo server -D
```

6. Сборка сайта

```
hugo -D
```
