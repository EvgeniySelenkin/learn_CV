# Компьютерное зрение

Компьютерное зрение (Computer Vision, CV) — это область искусственного интеллекта, связанная с анализом изображений и видео. Она включает в себя набор методов, которые наделяют компьютер способностью «видеть» и извлекать информацию из увиденного.

## Краткое описание каждого блокнота

- CV_1: 
  - Чтение и отображение изображения, его каналов отдельно и гистограмы яркости
  - Добавление границ на изображение: константным цветом, отражением, дублированием цвета на границе
  - Преображение изображения в серый цвет простым, взвешенным и встроенным методом
  - Манипуляу=ция с пикселями: изменение выбранного канала изобраения и извлечение прямоугольника из изображения с заменой на константный цвет
  - Преобразование RGB -> HSV
- CV_2:
  - Изменение изображения методом ближайшего соседа и методом билинейной интерполяции
  - Сжатие изображения методом ближайшего соседа и методом усреднения
  - Изменение яркости изображения нормализованной линейной трансформацией гистограммы
  - Реализация функции гамма коррекции
  - Эквализация гистограммы (стандартизация гистограммы монохромного изображения)
- CV_3: 
  - Генерация различных шумов (соль и перец, Гаусов шум) и применение фильтра Гауса, Box фильтра и медианного
  - Своя имплементация алгоритма детектора границ Canny
  - Реализация детектора границ Харриса
- CV_4: 
  - Реализация алгоритма склейки панорамы, используя SIFT
  - Реализация алгоритма оптического потока Лукаса-Канаде
- CV_5: 
  - Создание модели классификации изображений датасета CIFAR-10 классическими методами машинного обучения
  - Создание модели классификации изображений датасета CIFAR-10, используя полносвязную нейронную сеть
- CV_6: 
  - Обучение CNN для классификации на данных  «Cassava Leaf Disease Classification» (https://www.kaggle.com/competitions/cassava-leaf-disease-classification)
  - Обучение своей CNN с эксперементированием с оптимизаторами (Adam, SGD Momentum, RMSProp)
  - Использование предобученной модели на этом же датасете
- CV_7: На основе набора данных https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset создание модели сегментаии аэроснимков
- CV_neural_style_transfer: Обучение генеративной модели для переноса стиля из одного изображения на другое