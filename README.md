#  Module-2 Day-3 SEB
## AIM:
Write a C function/subprogram to check whether the given number is a perfect square or not.

### Note:  Function should not have a return type and it should have arguments.

## For example:
<img width="292" height="112" alt="image" src="https://github.com/user-attachments/assets/f5222f9b-8329-432e-b9e4-dfca91315e6d" />

## Program:
```c
#include <stdio.h>
#include <math.h>
void perfect(int a){
    int n;
    n=sqrt(a);
    if(n*n==a){
        printf("%d is a perfect square.",a);
    }
    else{
        printf("%d is not a perfect square.",a);
    }
    
}
int main(){
    int b;
    scanf("%d",&b);
    perfect(b);
    return 0;
}
```
## Result:
<img width="620" height="116" alt="image" src="https://github.com/user-attachments/assets/2213ab7c-4219-41bd-8c8d-fd2de4d669f4" />

