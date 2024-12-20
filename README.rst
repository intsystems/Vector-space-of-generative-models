|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Методы векторного представления глубоких генеративных моделей
    :Тип научной работы: НИР
    :Автор: Мария Александровна Никитина
    :Научный руководитель: к. ф-м н., Бахтеев Олег Юрьевич
    :Научный консультант(при наличии): аспирант, Бишук Антон Юрьевич

Описание
========

Задан набор генеративных моделей, описывающий разные выборки/генеральные совокупности данных. Требуется предложить метод векторного представления этих моделей, который будет представлять статистические свойства моделей. А именно:

- Расстояние между векторными представлениями моделей для близких выборок должно быть невелико (при условии, что сами модели хорошо их описывают)

- Модели, обученные на композиции/смеси выборок должны учитывать свойства всех выборок, входящих в смесь
