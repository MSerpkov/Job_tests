### В директории:<br>
`temp` - директория с промежуточными результатами (изображения)<br>
`points.jpg` - файл с исходным изображением<br>
`result.jpg` - файл с результирующим изображением<br>
`points3.ipynb` - Jupyter Notebook с программой<br>
<br>
### Задание:<br>
Оцените количество точек на картинке (Любым способом на ваш выбор) и опишите, как вы это сделали.<br>
https://lh5.googleusercontent.com/yO12GARP3fqmNOZ00zM9Q_nyBVWWfR_xVu8skrvAmhB1hzSJyq_F593jhQqS48aWJyCZ5jzDAQ=w513
<br>

### Комментарий:<br>
Скачиваем исходное изображение по ссылке.<br>
При помощи библиотеки компьютерного зрения OpenCV подсчитываем количество точек на изображении.<br>
Выбран метод анализа площадей контуров на изображении. <br>
Во время предобработки изображения промежуточные результаты сохраняются в директорию temp.<br>
По завершении работы программы выводится количество посчитанных точек и результирующее изображение.<br>
