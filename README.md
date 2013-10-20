#Rozwiązania

Zadanie 1. Program wypisuje liczby z tablicy tabela[] w odrwotnej kolejności wj. 12,6,4,2,1

```c

int main(){
  int tabela[]={1,2,4,6,12};
  int i;
  for(i=4;i>=0;i=i-1)
    printf(" \n %d %d\n \n",i , tabela[i]);

  return 0; 

}
```

Zadanie 2.

Napisać i uruchomić program w C, który wypisuje kolejne potęgi 2 nie przekraczające 2010
a)używając pętli for
```c
main(){
  int i;
  int potega=1;
  for(i=1;potega<2010;potega=potega*2)
    printf(" \n %d \n", potega);
}
```
b)używając pętli while
```c
main(){
  int i;
  int potega=1;
  for(i=1;potega<2010;potega=potega*2)
    printf(" \n %d \n", potega);
    }
```
Zadanie 3. Program obliczający wartości n1,n2,n3
```c
main(){
  int n1, n2, n3;
n1=5+3*8/2-3;
n2=2%2+2*2-2/2;
n3=2*4*(5+9/2);
 printf(" \n%d %d %d \n",n1,n2, n3); 
}
```
Zadanie 4. 
