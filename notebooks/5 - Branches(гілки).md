# Branhes - гілки

## Наявні гілки

```sh
git branch
```

Створення нової гілки `feature`:

```sh
git branch feature
```

## Наявні гілки

```sh
git branch
```

## Перемикання між гілками

```sh
git checkout feature
```

```sh
git log
```

## Створення та перемикання на нову гілку

```sh
git checkout -b new_branch_name
```

```sh
git branch
```

## Внесення змін

Додайте новий файл або змініть існуючий текстовий файл. Потім збережіть зміни:

```sh
git add .
```

```sh
git commit -m "Оновлення файлів"
```

```sh
git log
```

```sh
git checkout main
```

## Об'єднання гілки

```sh
gir checkout main
git diff new_branch_name
```

```sh
git merge new_branch_name
```

```sh
git log
```

## Видалення гілки

```sh
git branch -d new_branch_name
git branch -D new_branch_name
```


