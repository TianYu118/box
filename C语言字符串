### 学习参考《C Primer Plus(第6版)》
```
#include<stdio.h> 
#include<string.h>		//提供strlen()函数的原型
#define DENSITY 62.4
int main() {
	float weight,volume;
	int size,letters;
	int flag=1;
	char name[40];
	while(flag){
		
		printf("Hi!What's your first name?\n");
		scanf("%s",name);
		printf("%s,what's your weight in pounds?\n",name);
		scanf("%f",&weight);
		size=sizeof(name);
		letters = strlen(name);
	//	printf(letters);
		volume = weight/DENSITY;
		printf("Well,%s,your volum is %2.2f cublic feet.\n",name,volume);
		printf("Also,your first name has %d letters,\n",letters);
		printf("and we have %d bytes to store it.\n",size);
		printf("是否结束调试:0结束 or 1 继续\n");
		scanf("%d",&flag);
	} 
	return 0;	
}
```
