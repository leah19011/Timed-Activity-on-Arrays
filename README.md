# Timed-Activity-on-Arrays
Leah Mae Libante
#include<stdio.h>

int main(){

    int id[3][2] = {
    {1100, 12345},
    {1400, 23141},
    {1231, 23242}};

    int User, Pass, i;

    printf("#####Enter ID: ");
    scanf("%d", &User);
    printf("\n#####Enter Pin: ");
    scanf("%d", &Pass);


   for(i=0; 1 < 3; i++) {
   if(id[i][0]==User && id[i][1] == Pass){
           printf("\n\n#####You have successfully logged in to ID#: %d\n\n", User);
       }
    else{
        printf("\n\n#####Invalid ID/PIN!\n\n");
    }
        return 0;
   }
}
