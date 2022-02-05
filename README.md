#include<stdio.h>
#include<math.h>
int main(){
	int n,t,x;
	double fact, sonuc_e,son_sonuc;

    printf("e sayisinin kacinci kuvvetini hesaplamak istediginizi giriniz\n");
    scanf("%d",&x);
    fact=1;
    son_sonuc=1;
    for(n=1;n<15;n++){
    fact=1;
    t=n;
    while(t!=0){
     fact=fact*t;
     t--;}
    sonuc_e=pow(x,n)/fact;
    son_sonuc=sonuc_e+son_sonuc;}

    printf("e^%d: %lf",x,son_sonuc);

    }
