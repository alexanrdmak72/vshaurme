# Vshaurme
Line2deleted
  -  

Line3deleted
  -  
Инновационная социальная сеть для любителей лучшего блюда на свете! Вместо групп, как в большинстве социальных сетей, мы будем объединяться
Line4deleted
  -  
Относительно точек продажи! Вы сможете найти новые знакомства среди людей, которые покупают еду неподалёку от вас,
Line5deleted
  -  
Обмениваться отзывами о любимых сочетаниях мяса и овощей и ставить звёзды продавцам!
Line6deleted
  -  

Line7deleted
  -  
### Проект находится в разработке
Line8deleted
  -  

Line9deleted
  -  
Поэтому приветствуется любая помощь от знающих программистов! Построим социальную сеть будущего вместе!
Line10deleted
  -  

Line11deleted
  -  
Для того чтобы обновить код, вам достаточно сделать fork репозитория, сделать ряд изменений, запушить изменения в fork, а потом создать Pull Request с описанием проделанных изменений.
Line12deleted
  -  

Line13deleted
  -  
### Как помогать
Line14deleted
  -  

Line15deleted
  -  
Проект работает на [Django 1.11.1](https://www.djangoproject.comm). 
Line16deleted
  -  
Сейчас очень нужна помощь с моделированием системы, почитать о котором можно [здесь](https://docs.djangoproject.com/en/1.11/intro/tutorial02/#craeting-models).
Line17deleted
  -  

Line18deleted
  -  
### Как запускать
Line19deleted
  -  
Создайте файл local.py в папке vshaurme/settings/ и положите туда переменную `SECRET_KEY` с любым содержимым.
Line20deleted
  -  
После этого установите зависимости из requirements.txt любым удобным вам образом.
Line21deleted
  -  
Далее создайте базу данных командой ```python manage.py migrate```. Вам нужно будет повторять эту команду, если вы будете скачивать обновления нашего кода, в которых база данных будет меняться.
Line22deleted
  -  

Line23deleted
  -  
Затем соберите статичные файлы командой ```python manage.py collectstatic```. Вам также придётся повторять эту команду всякий раз, когда вы скачаете обновления, в которых будут изменены шаблоны проекта.
Line24deleted
  -  

Line25deleted
  -  
Сам сервер запускается командой ```python manage.py runserver```.
Line26deleted
  -  

Line27deleted
  -  

Line28deleted
  -  
Код написан в образовательных целях на курсах для веб-разработчиков [dvmn.org](https://dvmn.org/).