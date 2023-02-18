# Алгоритм решения:

1. Делаем перебор значений из исходного массива.
2. Проверяем каждое значение из массива на соответствие условию: длина строки меньше или равна трем.
3. Если строка удовлетворяет условию кладем значение в новый массив.
4. Повторяем пункты 2 и 3 до тех пор пока не достигнем конца исходного массива.
5. Возвращаем новый заполненный массив как результат.
   
//Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
/*Console.Write("Введите количество элементов: ");
int size = Convert.ToInt32(Console.ReadLine());
string[] arrayStrings = new string[size];
int len = 3;
int pos = 0;
for(int i = 0; i < size; i++)
{
    Console.WriteLine($"Введите {i + 1} - й элемент: ");
    string element = Convert.ToString(Console.ReadLine()!);
    if (element.Length <= len)
    {
        arrayStrings[pos] = element;
        pos++;
    }
}
Console.WriteLine();
PrintArray(arrayStrings);

//метод
void PrintArray(string[] array)
{
    for(int i = 0; i < array.Length; i++)
    {
        Console.Write(array[i] + " ");
    }
    Console.WriteLine();
}*/