# M1C
#include<iostream>
class M1C
{
private;
		int spt;
		int a[200];
	public;
		void nhap();
		void xuat();
// nhap mang
void M1C::nhap()
{
	cout<<"so phan tu:";
	cin >> spt;
	int i;
	for(i=0;i<spt;i++)
	{
		cout<<"a["<<x<<"]";
		cin>>a[i];
	}
// xuat mang
void M1C::xuat()
{
	cout<<"Mang:";
	int i;
	for(i=0;i<spt;i++)
	{
		cout<<a[i]<<"\t";
	}
	cout<<end|;
}

int main ()
{
M1C x;
    x.nhap();
    x.xuat();
Contact
Manage cookies
