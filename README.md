#include <stdio.h>
#include <stdlib.h>

int pos_ou_neg(int res){
    
    
    
    if(res>=0){
        printf("o numero e positivo");
    }else{
       printf("o numero e negativo");
    }
    
}int main(){
    
    int res;
    
    printf("digite um numero para saber se é positivo ou negativo\n");
    scanf("%d", &res);
    pos_ou_neg(res);
    
    return 0;
}
