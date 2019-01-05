# contoh-array-2


     #include<stdio.h>
    void tukar (int array[2])
    {
        int t= array[0];
        array [0]=array[1];
        array[1]=t;
    }
    int main()
    {
        int array[2]={1,2};
        printf("before %d - %d\n",array[0],array[1]);
        tukar (array);
        printf("after %d - %d",array[0],array[1]);
    }
    
hasil
![img](https://github.com/septianaana/contoh-array-2/blob/master/Array%202.png?raw=true)
