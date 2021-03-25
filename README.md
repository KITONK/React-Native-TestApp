# React-Native TestApp

## Тестовое задание:
Реализовать галерею на базе React-Native (не React.js), которая будет отображать фотографии из unsplash. Это приложение должно извлекать ресурс в формате JSON.

## Документация REST API: [API Documentation](https://unsplash.com/documentation)

## Приложение должно содержать два экрана(страницы):
* Список
    - мини изображение с названием и автором
    - когда пользователь нажимает на изображение, открывается экран фотографии 
* Фотография
    - отображает одну фотографию с максимальной площадью.

Предпочтительнее инициировать приложение через React Native CLI с помощью команды - react-native init TestApp, нежели чем через команду - create-react-native-app, если ресурсы вашего компьютера позволяют.

***!!! Использовался Expo CLI, чтобы не нагружать компьютер и иметь доступ к приложению через свой телефон (iOS) !!!***


## Необходимые к применению технологии:
* React-Native
* Redux + Async Redux library (redux-thunk, redux-saga, e.g.)
* es6 (JS) или TypeScript
* Flexbox
* React Navigation
* fetch или axios

## Предлагаемые к применению технологии:
* Hooks
* компоненты высшего порядка (High Order Components)
* render props
* ref

## Screenshots

![GalleryScreen](https://i.ibb.co/1sYs4gh/galleryscreen.jpg)

![ImageScreen](https://i.ibb.co/yycyL3W/imagescreen.jpg)
