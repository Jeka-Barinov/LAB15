# WPF-FILE-IO
## Работа с файлами в WPF
Вам предстоит сделать форму сохранения текста в файл и последующую его загрузку. 
Форма содержит кнопки **"Сохранить"** для сохранения текста в файл и кнопку **"Загрузить"** для последующего чтения из файла.

![additional](https://user-images.githubusercontent.com/97738135/150073286-436e638d-548f-4a3c-9aa3-ffd17898809e.png)

## Начало работы

1. Запустить Visual Studio и в стартовом меню выбрать **"Клонировать репозиторий"**. Репозиторий расположен по [ссылке](https://github.com/Sand-by/KPYP_LECTION).
2. Собрать решение и назначить запускаемым проект WorkWithFiles. Далее запустить его и убедиться что открывается приложение следующего вида

![before](https://user-images.githubusercontent.com/97738135/150074197-3243821a-46ae-4e60-ba08-f4d70793a5a6.png)

3. Необходимо внести некоторые изменения в файле MainWindow.xaml

![3](https://user-images.githubusercontent.com/97738135/150074379-52e655e8-2626-4308-9680-c71b8516597a.png)


## Следующий шаг

1. Необходимо убедиться что форма приняла следующий вид:

![1](https://user-images.githubusercontent.com/97738135/150074605-b5deec15-6597-4e53-98fd-d5212062ecc5.png)

В каждом из TextBox-ов появились плавающие подсказки, а так же кнопка очистки поля. Попробуй сохранить введённый текст в первый TextBox и далее нажать на кнопку **"Загрузить"**, и убедиться что всё работает корректно. Примерно так:

![2](https://user-images.githubusercontent.com/97738135/150074806-ec2701ee-6f54-4757-80c3-8b570dca972d.png)

2. *Дополнительно:* Можете добавить свойства ScrollViewer.VerticalScrollBarVisibility="Auto" для двух TextBox-ов, чтобы при заполнении текстом появлялся элемент прокрутки.

![scrollbar](https://user-images.githubusercontent.com/97738135/150075304-14f9879e-79a4-48b5-88dc-6b64d0f4c10f.png)


4. *Дополнительно:* Так же добавьте ещё одну кнопку **"Расположение файла"** при нажатии на которую  в  новом текстовом поле TextBox будет отображать путь к созданному файлу.

![additional](https://user-images.githubusercontent.com/97738135/150075337-5fb15398-1ccb-43d6-bea9-4f1462322726.png)


## Если возникли ошибки

Одним и из способов решить возникшие ошибки - это убедиться имеются ли пакеты MaterialDesign в менеджере NuGet

![error handling](https://user-images.githubusercontent.com/97738135/150075585-32c09453-4cd9-4ed9-a702-98bdce542c6d.png)

![error handling_2](https://user-images.githubusercontent.com/97738135/150075605-98a1619a-a401-48af-bce5-f4415fb17fb1.png)




asdfdsfdhghsgdhh