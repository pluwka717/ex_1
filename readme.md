#Sequential Merge Sort in C

##

Проект представляет собой алгоритм сортировки массива слиянием на С. В данной версии потоки не используются. Служит бля базовой реализации принципа
и будет расширен до параллельной обработки.

Программа принимает на вход размер массива и элементы массива, и выводит исходный и отсортированный массив.

## Возможности 

*   Реализация сортировки слиянием
*   Динамическое выделение памяти для массива

## Компиляция

Для проекта потребуется компилятор GCC

1. *Откройте терминал*
2. *Перейддите в директорию проекта*
3. *Скомпилируйте исходный файл*
    ''' bash
    gcc first_task.c -o sort_app
    '''
    *   'gcc': Вызов компилятора.
    *   'first_task.c': Имя исходника.
    *   '-o sort_app'; Имя выходного исполняемого файла.

## Запуск

После компиляции можно приступать к запуску программы из терминала:

1. *Запустите исполняемый файл:*
    ''' bash
    ./sort_app
    '''
2. В терминале будет предложено ввести размер массива (Целове число), введите число и нажмите клавишу 'Enter'.
3. В терминале будет предложено ввести диапазон значений элементов массива, введите желаемое число и нажмите клавишу 'Enter'.
4. Программа выведет исходный и отсортированный массив.
