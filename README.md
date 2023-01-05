# Java_OOP - Seminar_2

![pictures java for oop](https://raw.githubusercontent.com/Terekhov-A-S/Java_OOP_Seminar_2/main/Icon_Java_OOP_Advanced.png)


### Имеются данные о группе студентов. У каждого студента есть *средний балл* (например, 4.6).
Создайте родительский класс **ЗаписывательВФайл**. Создайте три *детских класса*, которые записывают в файл информацию о студентах в разных формах:

+ **Просто текст:** 
            ```
            *Иван Иванов=4.8*
            *Мария Кузнецова=5.0*
            *Степан Кузьмин=3.6*
            ```


+ **JSON:**
        ```
        {
        "Иван Иванов": 4.8,
        "Мария Кузнецова": 5.0,
        "Степан Кузьмин": 3.6
        }
        ```


+ **XML:**
        ```
        <?xml version="1.0" encoding="utf-8" ?>
        <students> 
        <student><name>Иван Иванов</name><grade>4.8</grade></student>
        <student><name>Мария Кузнецова</name><grade>5.0</grade></student>
        <student><name>Степан Кузьмин</name><grade>3.6</grade></student>
        </students>
        ```




*Подготовил студент Geek Brains* [**`Терехов Александр`**](https://gb.ru/users/7696463), Java_OOP - Seminar_2
