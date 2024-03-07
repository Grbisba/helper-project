# **Проект который поможет тебе разобрать с гит**
## **Команды bash terminal**
- cd = "Изменить директорию"
- pwd = "(от англ. print working directory) возвращает путь к рабочей папке"

---
### **Хеш — идентификатор коммита**
git log - команда, которая позволяет посмотреть информацию о коммитах
после выполнения, код вернет нам:
1. commit <<hash>>
2. Author 
3. Date
Для того чтобы посмотреть hash последнего коммита необходим перейти в скрытую директорию в папке проекта ".git".
После этого выполнить команду "cat HEAD", что вернет путь к веткам проекта.
Затем переходим в директорию "cd /refs/head/"(которую нам вернула команда "cat HEAD").
Читаем файл master, что выведет hash.
__Git хеширует (преобразует) информацию о коммите с помощью алгоритма SHA-1 (от англ. Secure Hash Algorithm — «безопасный алгоритм хеширования») и получает для каждого коммита свой уникальный хеш — результат хеширования.__


[Ссылка на git руководство](https://github.com/git/git/blob/master/README.md "Прочитай меня")
    
