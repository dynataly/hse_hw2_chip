https://colab.research.google.com/drive/1gn6mm7eDlM_Nky-QuJbhRx_IkZKfh3la?usp=sharing


Результат анализа fastQC

Качество чтений достаточное хорошее, но в контрольном образце доверительный интервал находится в пределах желтой зоны, тогда как в двух других - уходит далеко в красную. Тем не менее, качество чтений считается приемлимым.

Критерий, который не проходит ни один из образцов - это слишком часто встречающиеся последовательности - скорее всего остатки праймеров. Но и по этому показателю у контрольного образца лучше качество: последовательность составляет 0.14%, тогда как в двух других образцах - 7% и 1.2% соответственно.

1. ENCFF001FLQ

![flq1](https://user-images.githubusercontent.com/72361668/157705035-093ad6d4-703d-40be-9465-a24fe17d4574.png)


![flq2](https://user-images.githubusercontent.com/72361668/157704923-e6099199-75e2-4f61-b96b-f52911e16722.png)
![flq3](https://user-images.githubusercontent.com/72361668/157704937-b6b92b9f-0156-4335-ba88-0d4fcb2de953.png)
![flq4](https://user-images.githubusercontent.com/72361668/157704949-63dd139f-09c7-4b52-9eae-c822562cd984.png)



2. ENCFF001FLT

![flt1](https://user-images.githubusercontent.com/72361668/157705068-e377859b-34ee-431b-b9b1-dba041ad7fc9.png)
![flt2](https://user-images.githubusercontent.com/72361668/157705097-9e139124-3b21-435a-82f1-2dad5544cd78.png)
![flt3](https://user-images.githubusercontent.com/72361668/157705113-a4b00858-b1c2-41b2-8c75-b97c2bd1e377.png)

3. (контроль) ENCFF001HOD

![hod1](https://user-images.githubusercontent.com/72361668/157705130-767e61f8-475f-471d-998c-e252ccaecaf4.png)
![hod2](https://user-images.githubusercontent.com/72361668/157705149-31e984c6-b366-473d-831c-47fcd861ac47.png)



Статистика картирования:

ENCFF001FLQ:

17676344 reads; of these:

  17676344 (100.00%) were unpaired; of these:
  
    15809400 (89.44%) aligned 0 times
    
    496689 (2.81%) aligned exactly 1 time
    
    1370255 (7.75%) aligned >1 times
    
10.56% overall alignment rate


ENCFF001FLT:

14347796 reads; of these:

  14347796 (100.00%) were unpaired; of these:
  
    11781942 (82.12%) aligned 0 times
    
    638531 (4.45%) aligned exactly 1 time
    
    1927323 (13.43%) aligned >1 times
    
17.88% overall alignment rate

ENCFF001HOD

18282579 reads; of these:

  18282579 (100.00%) were unpaired; of these:
  
    14755841 (80.71%) aligned 0 times
    
    941627 (5.15%) aligned exactly 1 time
    
    2585111 (14.14%) aligned >1 times
    
19.29% overall alignment rate


Всего выровнялось от 10 до 20%, что неудивительно, учитывая, что выравнивание происходило только на одну хромосому. 


Пики (см приложенные pdf файлы)

В ENCODE оказывается значительно больше пиков, чем находится с помощью macs2: для первого образца - в 100 раз меньше, для второго - в 10.
Пересечение составляет 5-10% от пиков, найденных с помощью macs2.


Бонус

Для ENCFF001FLQ:
![result1](https://user-images.githubusercontent.com/72361668/157707778-6a0e98b9-75b4-4090-b9cf-227810c669a9.png)


