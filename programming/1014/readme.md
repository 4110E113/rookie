```c
#include <stdio.h>

int main(void) {
	int count = printf("this is a test!\n");
	printf("%d\n", count);
  
  return 0;
}
```

```c
#include <stdio.h>

int main(void){
	printf("顯示字元 %c\n", 'A');
	printf("顯示字元編碼 %d\n", 'A');
	printf("顯示字元編碼 %c\n", 65);
	printf("顯示十進位整數 %d\n", 15);
	printf("顯示八進位整數 %o\n",15);
	printf("顯示十六進位整數 %X\n", 15);
	printf("顯示十六進位整數 %x\n", 15);
	printf("顯示科學記號 %E\n", 0.001234);
	printf("顯示科學記號 %e\n", 0.001234);
	
	return 0;
}
```

```c
#include <stdio.h>

int main(){
	printf("example:%6.2f\n", 19.234);
	printf("example:%-6.2f\n", 19.234);
	
	return 0 ;
}
```
```c
#include <stdio.h>

int main(){
	printf("%*d\n", 1, 1);
	printf("%*d\n", 2, 1);
	printf("%*d\n", 3, 1);
	
	return 0 ;
}
```
```c
#include <stdio.h>

int main(void){
	int input;
	
	printf("請輸入數字 : ");
	scanf("%d", &input);
	
	printf("你輸入的數字 : %d\n", input);
	
	return 0 ;
}
```
```c
#include <stdio.h>

int main(void){
	char buf[50];

	printf("enter 1 to 5  : ");
	scanf("%[1-5]", buf);
	printf("your num : %s\n", buf);
	
	fflush(stdin); // 消除輸入緩衝區 
	
	printf("enter X Y Z : ");
	scanf("%[XYZ]", buf);
	printf("ans : %s\n", buf);
	
	return 0 ;
}
```
```c 
#include <stdio.h>

int main(void){
	char buf[10];
	
	printf("enter : ");
	scanf("%9s", buf);
	printf("ans : %s\n", buf);
	
	return 0 ;
}
```
