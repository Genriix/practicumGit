# Тренировочный проект для работы с Git.

----

Проект для изучения инструмента контроля версий [Git](https://github.com/git/git/blob/master/README.md)

Проект создан в рамках прохождения учебной практики на сайте [Яндекс Практикум](https://practicum.yandex.ru/profile/html-css/?from=learn_subscriptions-with-prof-recommendations) на 3 курсе специальности **09.02.07 Информационные Системы и Программирование**

## Моё первое консольное прилжения на С# >.<

```C#
﻿using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace quest3._1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("\nЗадание 1\n");

            long a = 25, b = 943287592;
            Console.WriteLine(a + b);
            Console.WriteLine(a * b);
            Console.WriteLine(a - b);
            Console.WriteLine(a / b);


            Console.WriteLine("\nЗадание 2\n");

            int x = 10, y = 12, z = 3;
            Console.WriteLine(x += y - x++ * z);
            Console.WriteLine(z = --x - y * 5);
            Console.WriteLine(z = --x - y * 5);
            Console.WriteLine(y /= x + 5 % z);
            Console.WriteLine(z = x++ + y * 5);
            Console.WriteLine(x = y - x++ * z);


            Console.WriteLine("\nЗадание 3\n");

            Console.WriteLine((1092 + 1279 + 2384) / 3);


            Console.WriteLine("\nЗадание 4\n");

            double pi = Math.PI;
            int r = 6532;
            Console.WriteLine(pi * (r * r));


            Console.WriteLine("\nЗадание 5\n");
            long uberflu? = 1;
            long _Identifier = 1;
            long \u006fIdentifier = 1;
            long &myVar = 1;
            long myVariab1le = 1;

            Console.ReadLine();

        }
    }
}
```