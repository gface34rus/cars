# Проект "Автопарк"

## Описание
Проект "Автопарк" представляет собой веб-приложение, позволяющее пользователям просматривать доступные автомобили и бронировать их. Приложение использует Angular для фронтенда и взаимодействует с API для получения данных о автомобилях и обработки заказов.

## Стек технологий
- Angular
- TypeScript
- HTML/CSS
- RxJS
- HTTPClient для взаимодействия с API

## Установка
1. Клонируйте репозиторий:
   ```bash
   git clone <URL_репозитория>
Перейдите в директорию проекта:
cd <имя_папки_проекта>
Установите зависимости:
npm install
Запустите приложение:
ng serve
Откройте браузер и перейдите по адресу http://localhost:4200.
Использование
На главной странице пользователи могут просмотреть доступные автомобили.
Пользователи могут фильтровать автомобили по марке.
Для бронирования автомобиля необходимо заполнить форму с контактными данными.
Функциональность
Компоненты
CarsComponent: основной компонент, который отвечает за отображение автомобилей и обработку заказов.
Методы:
getCars(filter: string): получает список автомобилей с учетом фильтра.
changeFilter(filter: any, carsContent: HTMLElement): изменяет фильтр и обновляет список автомобилей.
sendOrder(): отправляет заказ на бронирование автомобиля.
Шаблон
cars.component.html: содержит разметку для отображения автомобилей и формы для бронирования.
cars.component.css: стили для компонентов приложения.
Лицензия
Этот проект лицензирован под MIT License.
