# Седмица 8 - Двумерни масиви

Определение:
=
Двумерният масив е структура от данни, съставена от краен брой елементи от един и същи тип, подреден в редове и колони.

Синтаксис:
=
<тип> <име_на_масив> [<брой_редове>] [<брой_колони>];

Семантика:
=
В оперативната памет се заделят последователни клетки, чиийто брой е равен на произведението [<брой_редове>] * [<брой_колони>]. Размерът на заделената памет е произведение от броя елементи на декларирания масив и паметта, необходима за един елемент.

```
Пример: int matrix[2][3];
```
Инициализация:
=
1ви начин: int matrix[2][3] = {{1, 2, 3}, {4, 5, 6}};
2ри начин: int matrix[2][3] = {1, 2, 3, 4, 5, 6};
3ти начин: int matrix[2][3];
           matrix[0][0] = 1;
           matrix[0][1] = 2;
           matrix[0][2] = 3; и т.н.

Недопустими операции:
=
int matrix1[2][3], matrix2[2][3] = {{1, 2, 3}, {4, 5, 6}};
matrix1 = matrix2; //недопустима операция
