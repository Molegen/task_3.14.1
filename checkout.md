[< на главную](./readme.md)

---

### Работа с ветками:
1. [git branch](./branch.md)
2. [git checkout](./checkout.md)
3. [git merge](./merge.md)

---

## git checkout

Позволяет переключаться между ветками при помощи команды:

~~~bash=
git checkout [название]
~~~

Есть возможность сразу создать ветку и переключиться на неё:

~~~bash=
git checkout -b [hotfix]
~~~

Кроме взаимодействия с ветками есть возможность отмены изменений в файле с помощью команды:

~~~bash=
git checkout -- [config.yml]
~~~