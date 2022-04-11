# include <stdio.h>
# include <string.h>



int nMul(int n)
{
    int sum = 1;
    int i = 1;
    for(i = 1; i <=n; ++i)
        sum = sum*i;
    return sum;

}



int main()
{
    int i = 1;
    int a = nMul(3);
    int sum = 0;
    printf("%d\n", a);


    //求阶乘和

    for(i = 1; i <= 2; ++i)
    {
        sum = sum +nMul(i);

    }
printf("阶乘和为：\n");
 printf("%d\n", sum);
    return 0;
}
