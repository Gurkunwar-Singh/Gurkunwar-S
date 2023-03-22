# Gurkunwar-S
First repository
#C Program to get the array input form user:

code:

#include<stdio.h>
int main(){
int n; //size of array
scanf("%d",&n);
int array[n];
for (int i=0;i<n;i++){
scanf("%d",array[i]); //get value of array according to size;
}
//to display array;
for (int i=0;i<n;i++){
printf("%d",array[i]);
}
return 0;
}
