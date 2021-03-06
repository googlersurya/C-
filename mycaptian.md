//C++ program to find size of int, float, double and char//
#include<iostream>
using namespace std;
int main()
{
	cout<<"Size of char: "<<sizeof(char)<<"byte";
	cout<<"\nSize of int: "<<sizeof(int)<<"bytes";
	cout<<"\nSize of float: "<<sizeof(float)<<"bytes";
	cout<<"\nSize of double: "<<sizeof(double)<<"bytes";
	return 0;
}

//C++ program to find product of two numbers//
#include<iostream>
using namespace std;
int main()
{
	float n1, n2, pro;
	cout<<"Enter two numbers to find product:";
	cin>>n1>>n2;
	pro=n1*n2;
	cout<<"The product of two numbers is "<<pro;
	return 0;
}
