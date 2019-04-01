# 3d-Head

## Предложение 1

# Построение 3d модели головы по фотографии.

Построение модели 3d голвы по фотографии.

Код написан на питоне с использованием нейросети. Есть возможность использования уже натренерованной нейросети.

Для построения модели достаточно одной фотографии.

https://github.com/YadiraF/face3d

https://github.com/AaronJackson/vrn

# Анимирование головы

Для анимирования губ пока готового решения найти не удается.

* Высокое качество

Пользователь произносит специально подобранную фразу на камеру, которая позволяет зафиксировать все возможные анимации лица.
Из этих наборов впоследствии будет составлена анимация для любого произносимого текста.

* Среднее качество

Ползователь делает набор ключевых кадров с различным положением губ. Переходы расчитываются.

## Предложение 2

# Построение 3d модели головы по фотографии.

По фотографии создается набор ключевых точек лица. 

Для поиска ключевых точек можно воспользоваться openCV:

https://docs.opencv.org/3.4.2/d2/d42/tutorial_face_landmark_detection_in_an_image.html

После этого базовая модель гололвы модулируется с помощью ключевых точек.

# Анимация

Анимация создается из набора базовых моделей, промодулированных ключевыми точками.

