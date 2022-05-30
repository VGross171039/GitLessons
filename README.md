# Git Course

---

### Alias

```
Path: Users / MyName / .gitconfig
[alias]
  s = status --short
  l = log --oneline --graph --decorate --all

  and more..
```

---

### Отмена команд

Указываем файл для отмены изменений (если отмена в одном файле)

```
git checkout -- index.html
```

Удаляем изменения во всех файлах

```
git checkout .
```

Если изменения добавлены командой 'add .' в одном конкретном файле

```
git reset index.html
git checkout -- index.html
```

Аналогично с группой файлов

```
git reset .
git checkout .
```

### Работа с ветками

Просматриваем существующие ветки

```
git branch
```

Ветка + последний коммит

```
git branch -v
```

Создание новой ветки - 'develop'

```
git branch develop
```

Переход в новую ветку

```
git checkout develop
```

Переход обратно в основную

```
git checkout master
```

Создание новой ветки с одновременным переходом к ней

```
git checkout -b about
```

Переименование ветки в которой находимся

```
git branch -m myfix
```

Переход к любому нужному коммиту

```
git checkout f85404d
```

Залить нужную ветку в облако

```
git push --set-upstream origin myfix
```

Удаление определенной ветки

```
git branch -d develop
```

### Git Graph

Устанавливаем расширение
Показывает графически все ветки

Перерыв: 1.20
