# primary
初学
#include<stdio.h>

//int main()
//{
//	int a = 10;
//	int arr[] = { 1, 2, 3, 4, 5, 6 };//(arr的意思是数组,中括号的是元素)每个元素1个整型，1个整型4个字节，6*4=24
//	printf("%d\n",sizeof(a));
//	printf("%d\n", sizeof a);
//	printf("%d\n", sizeof(int));
//	printf("%d\n", sizeof(arr));//计算数组大小，单位为字节
//	printf("%d\n", sizeof(arr) / sizeof(arr[1]));//每个元素下标都由0开始，即0，1，2，3以此类推 24/4=6
//	return 0;
//}
//int main()
//{
//	int a = 0;//整型占用4个字节，32个bit位
//	int b = ~a;//~按照（二进制）位取反
//	printf("%d\n", b);//
//	printf("%d\n",sizeof(b));
//	return 0;
//}
//int main()
//{
//	int a = 10;
//	int c = ++a;//先自加一，再付值
//	int b = c++;//（后置加加），先付值，再自加一
//	printf("b=%d\nc=%d\n", b, c);
//	int d = a--;
//	printf("d=%d\na=%d\n", d, a);
//	return 0;
//}
//int main()
//{
//	int a =(int)3.14;//原本3.14是double类型，在3.14前面加入（），可强制转变成其他类型。前面则是（int）强转int类型
//	printf("%d\n", a);
//	return 0;
//}
//int main()
//{
//	int a = 10;
//	int b = 20;
//	int max = 0;
//	max=(a > b ? a : b);
//	if (a > b)
//		pritnf("胜利:%d\n", a);
//	else
//		printf("失败:%d\n", b);
//	return 0;
//}
//int main()
//{
//	register ont a = 10;//建议寄存器
//	return 0;
//}
//int main()
//{
//	struct//结构体关键字
//		return 0;
//	union//联合体或者共用体
//}
//typeof 类型定义-类型重定义
//例如：unsigned int a =20;
//typeof unsigned int u_int
//u_int a=20（之后的unsigned int的输入可以用u_int来代替）

//void test()
//{
//	/*static*/ int a = 1;//static加在前面，作用是打破局部变量结束后的持续状态。即此题中，加了static a会累加。
//	a++;
//	printf("a =%d\n", a);
//}//局部变量只在括号内存在所有，只有一出去就消失不存在了
//int main()
//{
//	int i = 0;
//	while (i < 5)
//	{
//		test();
//			i++;
//	}
//	return 0;
//}

//int main()
//{
//	//extern （声明外部符号）
//	extern int vvv;//若在另外一个文件其中一条代码输入static，则无法调用，使加static的代码只能在其文件，无法被extern调用。
//	printf("vvv=%d\n", vvv);
//	return 0;
//}

//声明外部函数
//extern int Add(int x, int y);
//int main()
//{
//	int a = 10;
//	int b = 20;
//	int sum = Add(a, b);
//	printf("sum=%d\n", sum);
//	return 0;
//}

//#define 定义标识符常亮
//#define MAX 200
//int main()
//{
//	int max = MAX;
//	printf("最大：%d\n", MAX);
//	return 0;
//}

//#define 可以定义宏一带参数
//宏的定义方式
//#define MAX(X,Y)(X>Y?X:Y);
//int main()
//{
//	int a = 10;
//	int b = 30;
//	int max = MAX(a, b);
//	printf("最大 = %d\n", max);
//	return 0;
//}
//与宏定义相比函数的比较大小方式
//int MAX(int z, int k)
//{
//	if (z > k)
//		return z;
//	else
//		return k;
//}
//
//int main()
//{
//	int a = 20;
//	int b = 30;
//	int max = (a, b);
//	printf("最大= %d\n", max);
//	return 0;
//}
