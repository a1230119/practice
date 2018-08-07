#include<stdio.h>

int Fib(int n){
    int ans = 1, temp0 = 0, temp1 = 1;
    while(n > 1){
        ans = temp0 + temp1;
        temp0 = temp1;
        temp1 = ans;
        n--;
    }
    return ans;
}

int main(){
    for(int i = 1; i <= 5; ++i){
        printf("%d\n", Fib(i));
    }
    return 0;
}
