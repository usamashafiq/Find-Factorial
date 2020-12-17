#include<iostream>
#include<conio.h>
using namespace std;
int fab(int);
int main()
{
	int a,total;
	cout << "Enter a number find Factorial : ";
	cin >> a;
	total= fab(a);
	cout << total;
	_getch();

}int fab(int a) {
	
	if (a == 1) {
		return 0;
	} 
	if (a == 2) {
		return 1;
	}
	else {

		return fab(a - 2)+fab(a-1);
	}
	


}
