kotlin level 1

Домашнее задание №2
“Работа со списком и сетью”
Постановка задачи
Требуется разработать небольшое приложение, которое отображает плашки с изображениями, полученными от API.
Приложение должно уметь обрабатывать состояние загрузки данных. В примитивном варианте - выводить крутилку по центру экрана. Если есть догрузка данных - то отображать плашку с крутилкой.
Приложение должно уметь обрабатывать ошибки загрузки - отображать заглушку, которая позволит повторить запрос. Если есть пагинация - то плашка должна отображать элемент, тап по которому позволить повторить догрузку данных.
Ограничения и требования
Требуется использовать Fragment/Compose
Приложение не должно содержать хардкод.
Приложение должно использовать ресурсы(resources) для работы
В коде можно оставлять комментарии, но в конечной версии нельзя оставлять Log
Обработка переворота экрана (загруженные данные не должны грузиться с нуля)
Что будет плюсом
Пропорции плашек, соответствуют пропорциям получаемым изображениям (не все API вам могут позволить это сделать)
Загружаемые изображения - анимированные (gif)
Загружаемые изображения имеют разные пропорции (как в Pinterest)
Пагинация (Догрузка данных во время скролла)
Использование кэша (как для данных так и для картинок)
Основные сценарии проверки
Ошибка загрузки данных. Перед запуском приложения - включить режим полета. После выключения режима полета - тапнуть по заглушке, чтобы данные загрузились
Ошибка догрузки данных(если есть пагинация). После запуска приложения, дождаться загрузки данных, включить режим полета и инициировать догрузку данных. После выключения режима полета - тапнуть на повторную догрузку данных,  данные должны догрузиться.

Где можно найти необходимые API?
RapidAPI, здесь есть полезное API для анимированных картинок - Giphy API.
Github of Public APIs
Punk API:)
Любое API, которое интересно использовать и к которому может получить доступ преподаватель.
Использование стороннего ContentProvider тоже допускается (например, получение списка контактов).

