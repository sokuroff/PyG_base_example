# PyG_base_example
В данном ноутбуке производится классификация узлов из набора данных Cora, который представляет собой граф цитирования, где узлы соответствуют документам. Каждый узел описывается 1433-мерным вектором признаков, основанным на bag-of-words. Два документа соединены ребром, если между ними существует ссылка на цитирование. Задача заключается в предсказании категории каждого документа (всего 7 категорий).

Для классификации сначала создаётся baseline модель в виде MLP, затем аргументированно предлагается использование GCN, а также рассматривается модель GAT.