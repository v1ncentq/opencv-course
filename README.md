# OpenCV Course

Навчальний репозиторій із практичними прикладами та нотатками за курсом [OpenCV with Python](https://youtu.be/oXlwWbU8l2o) від freeCodeCamp.

## Зміст

- базова робота із зображеннями та відео;
- трансформації, контури й порогова обробка;
- колірні простори, розмиття, маски, гістограми та градієнти;
- детекція й розпізнавання облич за допомогою Haar Cascade та LBPH;
- фінальний проєкт — CNN-класифікатор персонажів «Сімпсонів».

Основні матеріали та виконані завдання зібрані в [`opencv-course-solutions.ipynb`](./opencv-course-solutions.ipynb).

## Технології

`Python` · `OpenCV` · `NumPy` · `Matplotlib` · `Jupyter Notebook` · `TensorFlow/Keras`

## Запуск

```bash
git clone https://github.com/v1ncentq/opencv-course.git
cd opencv-course

python3 -m venv .venv
source .venv/bin/activate

pip install opencv-contrib-python numpy matplotlib jupyter tensorflow keras caer kagglehub
jupyter notebook opencv-course-solutions.ipynb
```

> У Windows для активації середовища використовуйте `.venv\Scripts\activate`.

## Джерело

Репозиторій створено на основі матеріалів [оригінального курсу](https://github.com/jasmcaus/opencv-course). Ліцензія — [MIT](./LICENSE).
