#include<stdio.h>
void main()
{
    int arr[5],sum=0,i;
    printf("Enter array elements:");
    for(i=0;i<5;i++)
    {
        scanf("%d",&arr[i]);
    }
    printf("The array elements are:");
    for(i=0;i<5;i++)
    {
        printf("%d",arr[i]);
        sum=sum+arr[i];
    }
    printf("The sum value is %d",sum);
}    
    
