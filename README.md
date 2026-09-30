# inlab-6-task
# task 2
#include<stdio.h>
int main(){
    for(int i = 9 ; i>=6;i++){
        printf("%d",i*i);
    }
}
# task 1
#include<stdio.h>
int main(){
    for(int i = 0 ; i<=18;i++){
        printf("%d\t",i+2);
    }
    return 0;
}

# task 3 
#include<stdio.h>
int main(){
    int i ;
    while(i!=0){
        printf("\nenter number\t");
            scanf("%d",&i);
        printf("%d",i*i*i);
    }
    return 0;
}

# task 4 
#include<stdio.h>
int main(){
    int i ;
  int  students = 0;
    while(i!=0){
        printf("\nenter marks\t");
            scanf("%d",&i);
        if(i!=0){
       students++ ;}
           
    }
     printf("%d\n",i);
     printf("%d total students",students);
    return 0;
}

# task 5 
#include<stdio.h>
int main(){
    int i ;
    int temp ;
    int count = 0;
  for(i=1;i<=7;i++){
      printf(" %d enter the temp\t ",i);
      scanf("%d",&temp);
      
      if(temp>100){
          count ++ ;
      }
      printf("%d\n",temp);
     
  }
   printf("%d temp greater than 100 : ",count);
    return 0;
}

# task 6
#include<stdio.h>
int main(){
    
    int saving=1 ,sum=0;
    int deposit = 0;
 while(saving>0){
printf("enter the amount saved\n");
     scanf("%d",&saving);
        
     if(saving!=0){
         sum +=saving;
         deposit ++;
             
     }
      
 }
    printf("%d\n",sum);
     printf("%d\n",deposit);
    return 0;
}

# task 7
#include<stdio.h>
int main(){
    char name[50];
    int  total_bill=0,order=0;
    int price = 0, choice = 1;
    
 while(choice!=0){
printf("enter the name of food item saved\n");
     scanf("%s",&name);

     printf("enter the price of food item saved\n %s\t",name);
     scanf("%d",&price);
      total_bill +=price;
     order ++;
        
         printf("do you want to order another item");
         scanf("%d",&choice);
       
     
 }
    printf("%d\n",order);
     printf("%d\n",total_bill);
    return 0;
}

# task 8
#include<stdio.h>
int main(){
   int salary[6];
    int count = 0;
    for( int i=0;i<6;i++){
        printf("enter salaries\t ");
        scanf("\t%d",&salary[i]);


        
        if(salary[i]>50000){
            count ++ ;
           
        }
       
    }

      printf("\n number of employees salary greater than 50000%d \n",count);
    return 0;
 
}
