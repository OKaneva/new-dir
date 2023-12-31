# Шпаргалка для работы с git

1. Сделать папку репозиторием 

```
git init
```


2. «Разгитить» папку, если что-то пошло не так
```
 — rm -rf .git
```


3. Проверить состояние репозитория 
```
git status
```


4. Подготовить файлы к сохранению
```
git add
```


5. Выполнить коммит
```
git commit
```


6. Просмотреть историю коммитов
```
git log
```


7. Привязать удалённый репозиторий к локальному
```
git remote add
```


8. Убедиться, что репозитории связаны
```
git remote -v
```


9. Отправить изменения на удалённый репозиторий
```
git push
```

# Доп функции для работы с git

1. Хеш


Хеширование (от англ. hash, «рубить», «крошить», «мешанина») — это способ преобразовать набор данных и получить их «отпечаток» (англ. fingerprint).


2. Структура описания коммита


- строка из цифр и латинских букв после слова commit — это хеш коммита;
- Author — имя автора и его электронная почта;
- Date — дата и время создания коммита;
в конце находится сообщение коммита.


Получить список коммитов

```
git log
```

3. HEAD


Файл HEAD (англ. «голова», «головной») — один из служебных файлов папки .git. Он указывает на коммит, который сделан последним (то есть на самый новый).





