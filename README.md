# c
//结构体变量的声明
struct Date
{
	int da_year;
	int da_month;
	int da_day;
 } ;
 //声明三个struct为Date的结构体变量 
 struct Date yesterday,today,tomorrow;
//或者在定义结构体类型的时候在后面直接定义变量：
struct Date
{
	int da_year;
	int da_month;
	int da_day;
 } yesterday,today,tomorrow; 
