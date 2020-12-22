# Profiling
The essence of this laboratory work is to check the CPU time. I used Visual Studio for this. The profiling was done twice: with sleep function and without. 
### Original code 

```
void func1(int a)
{
    for(int i = 0; i < 100000000; i++)
	{
		sleep(1);
			if(i>a)
				return;
		
	}

    return;
}

void func2(int c)
{
    for(int i = 0; i < 10; i++)
	{
		sleep(1);
			if(i>c)
				return;
	}
    return ;
}
void func3(int b)
{
    for(int i = 10; i > 3; i++)
	{
		sleep(1);
			if(i<a)
				return;
	}
    return ;
}

int main(void)
{
    printf("\n Inside main()\n");
	string typeOfShape;
	scanf("%s", typeOfShape);
	
    int i = 0;

    for(;i<10;i++);
	{
		for(int j=1000000; j > 0; j--)
		{
			if(func1(i) || func2(j-i) || func3(j){
				printf("\n Inside if()\n");
			}
		}
	}

    return 0;
}
```
### Result with sleep function
 ![alt text](picture/result_sleep.png "Code_after")​
### Result without sleep function 
 ![alt text](picture/result_without_sleep.png "Code_after")​
