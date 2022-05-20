## Второе ревью: Flask-приложение для блога

### Клонирование репозитория с помощью ssh
в терминале запускайте следующую команду
> git clone git@github.com:humooo/Python_second_review.git \
> cd Python_second_review

## Запуск приложение
### через запуск файла run.sh
> ./run.sh

### через Docker
> sudo docker build -t my_app . \
>  sudo docker run -d -p 5000:5000  my_app

### Или откройте этот [сайт](http://my-blllog.herokuapp.com) в браузере 