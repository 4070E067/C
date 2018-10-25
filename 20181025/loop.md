
# C語言的3個loop:for / while /do while


### 使用3種loop技術完成1+2+3+4+....+9+10

[1]for loop
```

#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   int i=1,sum=0;
   for(i=1;i<=400;i++)			
   { 
     sum+=i;
     i++;
   }  
   printf("1+3+5+7+...+399=%d\n",sum);	
   
   system("pause");
   return 0;
}
```

[2]while loop
```
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
   int i=1,sum=0;
   while(sum<4950)			
   { 
     sum+=i;
	 i++;
   }  
   printf("1+3+5+7+...+399=%d\n",sum);	
   
   system("pause");
   return 0;
}

```
[3]do while loop

```


```
### 作業

```
[1]使用3種loop技術完成1+3+5+7+....+399
[2]使用3種loop技術完成2+4+6+8+....+298

```
