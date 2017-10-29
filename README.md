# A-B-for-Input-Output-Practice-II-

A+B for Input-Output Practice (II)

Problem Description

Your task is to Calculate a + b. 

Input

Input contains an integer N in the first line, and then N lines follow. Each line consists of a pair of integers a and b, separated by a space, one pair of integers per line. 

 
Output

For each pair of input integers a and b you should output the sum of a and b in one line, and with one line of output for each line in input. 

 
Sample Input

2

1 5

10 20

 
Sample Output

6

30 


解答：

#include<stdio.h>

#define M 1000

void main()

{ 

    int a ,b,n,j[M],i;
    
    //printf("please input n:\n");
    
    scanf("%d",&n);
    
    for(i=0;i<n;i++)
    
    {
    
        scanf("%d%d",&a,&b);
        
        //printf("%d %d",a,b);
        
        j[i]=a+b;
        
    }
    
    i=0;  
       
    while(i<n)
    
    {
    
        printf("%d",j[i]);    
        
        i++;
        
        printf("\n");
        
    }
    
}     


