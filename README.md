# Classification-Model
The model classifies images of people by gender and age

Датасет для этого проекта взят отсюда: https://www.kaggle.com/ttungl/adience-benchmark-gender-and-age-classification
Он имеет в общей сложности 26 580 фотографий 2284 разных людей в восьми возрастных диапазонах, размер около 1 ГБ.

В качестве библиотеки по глубокому обучению использован PyTorch.
Архитектура сети для проекта:
1 - CNN-слой, выходных каналов 6, фильтр 5Х5, макспулинг.
2 - CNN-слой, выходных каналов 16, фильтр 5Х5, макспулинг.
3 - CNN-слой, выходных каналов 32, фильтр 5Х5, макспулинг.
4 - CNN-слой, выходных каналов 32, фильтр 5Х5, усреднение тензора по двум размерностям.
5 - Полносвязный слой, является выходным слоем.
