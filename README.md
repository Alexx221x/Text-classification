# Text classification (toxic comments)
Пример бинарной классификации текста по датасету соревнования [jigsaw-toxic-comment-classification-challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data) для всех желающих.

Рекомендую запуск в колабе: https://colab.research.google.com/drive/1gERCNDgBJXrV3djs2mSp6uBTu5Nwpwop?usp=sharing

## Содержание:

1. [Работа с библиотеками](#c1)
2.  [Работа с датасетом](#c2)
  * [Загрузка датасета](#c3)
  * [Вводный анализ](#c4)
      * [Анализ датасета](#c5)
      * [Распределение в таргете](#c6)
      * [Анализ текстов](#c7)
  * [Предобработка данных](#c8)
      * [Выборки](#c9)
      * [Очистка](#c10)
      * [Спеллер](#c11)
      * [Лемматизация](#c12)
      * [Облако слов](#c13)
      * [LDA (Latent Dirichlet Allocation)](#c14)
  * [Получение признаков](#c15)
      * [TF-IDF](#c16)
      * [BERT](#c17)
  * [Борьба с дисбалансом в таргете](#c18)
  * [Вывод:](#c19)
3.  [Обучение моделей](#c20)
  * [На признаках TF-IDF](#c21)
      * [Обучение](#c21)
      * [Результат](#c23)
  * [На эмбеддингах BERT](#c24)
      * [Обучение](#c24)
      * [Результат](#c25)
  * [Тестирование](#c26)
  * [Вывод:](#c27)
4. [Немного про CatBoost и текстовые признаки](#c28)
5. [Финальный вывод:](#c29)

[**Bonus:** Tensorflow/Keras (Bidirectional LSTM)](#c30)
