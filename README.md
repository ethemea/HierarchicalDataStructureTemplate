# Hierarchical Data Structure Template
Курсовая работа "Шаблон иерархической структуры данных в памяти" 3-го семестра.
## Описание задания на курсовую работу
Для заданной двухуровневой структуры данных, содержащей указатели на объекты -	параметры шаблона, разработать полный набор операций (добавление, включение и извлечение по логическому номеру, сортировка, включение с сохранением порядка, загрузка и сохранение строк в бинарном файле, балансировка – выравнивание размерностей структур данных нижнего уровня). Предполагается, что операции сравнения хранимых объектов переопределены стандартным образом (в виде операций <,> и т.д.). Программа должна использовать шаблонный класс с объектами-строками и реализовывать указанные выше действия над текстом любого объема, загружаемого из файла.

Программа должна реализовывать указанные выше действия. Программа тестирования должна содержать меню, обеспечивающее выбор операций.

Шаблон структуры данных – односвязный список, каждый элемент которого содержит статический массив указателей на объекты. Последовательность указателей в каждом массиве ограничена NULL. При переполнении текущего массива указателей создается новый элемент списка, в который переписывается половина указателей из текущего.
