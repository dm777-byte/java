1 Задать целочисленный массив, состоящий из элементов 0 и 1. Например: [ 1, 1, 0, 0, 1, 0, 1, 1, 0, 0 ]. Написать метод, заменяющий в принятом массиве 0 на 1, 1 на 0;
2 Задать пустой целочисленный массив размером 8. Написать метод, который помощью цикла заполнит его значениями 1 4 7 10 13 16 19 22;
  
1. 

public static void main(String args[]) {
int[] arr = new int[10];    //создаём целочисленный массив и присваиваем значение из 10 элементов
arr [0] = "1"
arr [1] = "1"
arr [2] = "0"
arr [3] = "0"
arr [4] = "1"
arr [5] = "0"
arr [6] = "0"
arr [7] = "1"
arr [8] = "1"
arr [9] = "0"
arr [10] = "0"


int[] arr = {1, 1, 0, 0, 1, 0, 1, 1, 0, 0 } // Можно задать по другому

for (int i = 0; <10; i++) {   // Не понимаю что такое arr.lenght (скорее всего длина массива =10) нашёл эту строчку в методичке)
if arr[i] =1, arr[1] = 0;  // если значение 1 присвоить к i-тому элементу массива, значения массива с индексом 1 = 0
System.out.println ("arr [i]=1");
else arr[i]=1, arr [1] = 0;  // в противном случае arr [i] =0


2. 
public static void main(String args[]) {
int[] arr = new int[8];   // объявляем массив из 8 элементов
arr[0] = 0;
arr [1] = "1"
arr [2] = "4"
arr [3] = "7"
arr [4] = "10"
arr [5] = "13"
arr [6] = "16"
arr [7] = "19"
arr [8] = "22"
for (int i = 0; i <8; i++) {













 
