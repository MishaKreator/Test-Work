# Контрольная работа

## Для хорошего результата требуется: 
1) Создать репозиторий на GitHub
2) Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3) Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4) Написать программу, решающую поставленную задачу
5) Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)
### Задача:

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


# Последовательность действий для решения поставленной задачи:
- создаем массив
- наполняем массив последовательностью символов, которые вводим в консоле
- производим подсчет количества элементов в массиве, длина которых меньше либо равна 3 символа
- создаем новый массив размером, равным количеству подсчитанных элементов
- наполняем новый массив элементами, длина которых меньше либо равна 3 символа
- выводим на печать исходный массив и новый массив

## Какие команды используем?
- "**FillArray**" для заполнения массива
- "**PrintArray**" для печати массива
- "**CountStringSymbols**" для подсчета количества элементов в массиве, длина которых меньше либо равна 3 символа
- "**GenerateNewArray**" для создания нового массива, состоящего из строк, длина которых меньше либо равна 3 символа