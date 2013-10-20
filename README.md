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
  i=1;
  while(i<2010){
      printf("\n%d\n", i);
  i=i*2;
  
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
```c
main(){
  int n;
  for(n=0; n<50; n=n+1)
    printf(" Cześć \n\n");
}
```
Zadanie 5.
```c
main(){
  int n;
  for(n=0; n<10; n=n+1){
    printf("\n  Cześć \n To ja \n");
     printf ("\n Nie \n");
      }
}
```
Zadanie 6.
```c
main(){
  int n,suma;
  suma=0;
  suma=(suma+n);
  for(n=0;n<1001;n=2*n){
    printf("%i\n",n);}
    }
```
Zadanie 7.
```c
main(){
  int n,suma;
  suma=0;
  suma=(suma+n);
  for(n=2;n<2001;n=n*n){
    printf("%i\n",n);}
    }
```
Zadanie 8. Sumowanie dwóch liczb
```c
main(){
int i,j;
  printf("podaj pierwszą liczbę: \n");
  scanf("%i", &i);
  printf("podaj druga liczbe: \n");
  scanf("%i", &j);
  printf("Suma: \n %i \n",i=i+j);
  }
```
Zadanie 9. Suma, Różnica, Iloczyn, Iloraz
```c
main(){
  int i,j;
  printf("podaj pierwszą liczbę: \n");
  scanf("%i", &i);
  printf("podaj druga liczbe: \n");
  scanf("%i", &j);
  printf("Suma: \n %i \n",i+j);
  printf("Różnica: \n %i \n",i-j);
  printf("Iloczyn: \n %i \n",i*j);
    printf("Iloraz: \n %i \n",i/j);
}
```
Zadanie 10. Kwadrat, Sześcian
```c
main(){
  int i,j;
  printf("podaj liczbę: \n");
  scanf("%i", &i);
  printf("Kwadrat: \n %i \n",i*i);
  printf("Sześcian: \n %i \n",i*i*i);
 }
```
