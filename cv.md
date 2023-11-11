----
# Alexander Uvarov
----
## Junior front-end developer
----
## * Contacts
  - #### e-mail: alexander.uvarov001@gmail.com
  - #### telegram: Alex_Uvarov01
  - #### git hub: Alex-Uvarov
----
## * About me
  I am a firs year master's student in information systems and technology. In my undergraduate degree I studied chemistry. Now I am also learning grafic and ux/ui design, that's why I’ve decided to try something new. I hope my diligence and the courses will help me to obtain useful knowledge.
----
## * My skills
  - JS
  - C#
  - Photoshop
  - Illustrator
  - Figma
----
## * Code example:
```
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        //Зададим список
        List<string> numbers = new List<string> {"15", "2", "33", "4", "56"};
        //Делегат Function, который увеличивает значение числа на 2
        Func<int, int> IncreaseForTwo = x => x+=2;
        //Делегат Function, который возводит число в квадрат
        Func<int, int> Square = x => x * x;
        //Делегат Action, который вызывает Func и принимает список объектов
        Action<Func<int, int>, List<string>> ListIncreasing = (increasingFunc, list) =>
        {
            Console.WriteLine("Начало выполнения");
            Console.WriteLine("");
            // берем каждый отдельный элемент списка применяем на него Func
            for (int i = 0; i < list.Count(); i++)
            {
                int result = increasingFunc(int.Parse(list[i]));

                Console.WriteLine($"При выполнении функции для числа {list[i]} было получени значение {result}");
            }
            Console.WriteLine("");
            Console.WriteLine("Конец выполнения");
            Console.WriteLine("");
        };
        //Вызов
        ListIncreasing(IncreaseForTwo, numbers);
        ListIncreasing(Square, numbers);
    }
}
```
---
## * Work expirience:
No
---
## * Education:
  - Under graduate: Chemistry (2023)
  - Master: Information systems and technology (2025)
---
## * English:
B2
