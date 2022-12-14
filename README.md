# Face_generation
Neural Network Model for Face Generation


Нейронная сеть для генерации изображений лиц.

Была выбрана нейронная сеть DCGAN (Deep Convolutional GAN).

Принцип работы DCGAN описан по ссылке (https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html).
Ниже представлена архитектура генератора модели.

![dcgan_generator](https://user-images.githubusercontent.com/106436340/196920180-9a4d30c8-9da6-4e1f-9091-7eeb7db92876.png)


Ниже показан результат работы на 10000 эпохах. 

Обучение при параметрах Image_size=(32,32), Batch_size=128 составляет около 45 минут.

![Faces_gen](https://user-images.githubusercontent.com/106436340/196918293-fe977a80-a94c-4a07-88a6-1f8db7d4ee0c.gif)

Размер изображения выбран 32Х32 для ускорения времени обучения модели.

Для повышения качества изображения можно изменить размер картинки до 64 (и выше), но время обучения будет намного больше.

Результат работы моделе представлен ниже (сгенерированное лицо)

![Face_1](https://user-images.githubusercontent.com/106436340/196919149-b479bcb8-a2f8-45ea-b05f-534097190d82.png)
