# Тестовое задание для Habidatum

## Задание

1. Отображать списком семпл из данных (например первые 50-100 записей,
   количество не важно)
2. Элемент списка должен содержать информацию 
    * о начале и конце поездки
    * продолжительности поездки
    * начальной и конечной точках
3. Рядом со списком должна располагаться карта на которой точками будут
   показаны начальные и конечные точки поездки
4. При наведении на один из элементов списка соответствующие точки на карте
   должны активироваться:
    * они должны стать больше
    * должен измениться их цвет
    * у них должны появиться лейблы с названиями локаций
    * размер точек зависит от продолжительности поездки

## Online Demo

[Habidatum Demo](https://av1at0r.github.io/habidatum-demo/)

## Запуск в режиме разработки

> Для запуска необходимо создать файл .env, в который поместить Mapbox access token

```
  REACT_APP_MAPBOX_TOKEN=your_token
```

Скрипт запуска

```
> yarn start
```

[Telegram](https://t.me/nikita_li) | [livik.nick@gmail.com](mailto:livik.nick@gmail.com)
