数组I:
1.	数组的定义和初始化
a)	定义int  a[5];//a[0]~a[4]
b)	访问：
i.	读取 cout<<a[2];
ii.	写入 a[3]=5; a[4]++;
c)	初始化
i.	完全初始化int  a[5]={1,2,3,4,5};//a[0]=1;a[3]=4;a[2]=3;a[4]=5;
ii.	部分初始化 int  b[5]={1,2} ;//b[0]=1,b[1]=2,b[2]=b[3]=b[4]=0
iii.	int c[5];//c[0]~c[4]都是随机值
2.	数组的输出
a)	cout<<a[0];cout<<a[1]….
b)	循环输出 for(int i=0;i<n;i++)cout<<a[i]<<” “;
3.	数组的输入
a)	循环输入 for(int i=0;i<n;i++)cin>>a[i];
4.	数组的操作//a[n]
a)	转置 // swap a[j]<-> a[n-1-j]
b)	求最大//打擂台
c)	求最小//打擂台
d)	求和//累加
e)	查找x是否存在，如果在，第一次出现位置 ，否则输出-1*
f)	统计y一共出现了多少次* 
g)	排序**
