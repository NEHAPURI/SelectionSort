#include<iostream.h>
#include<conio.h>
void select(int[], int);       // function prototype
void main()
{
 clrscr();
 int a[100], s;
 cout<<"\t\t\t\tSELECTION SORT";
 cout<<"\n Enter the size of array(max 100) : ";
 cin>>s;   // sizeof array

 cout<<"\n Ehter the array : ";
 for(int i =0;i<s;i++)
	cin>>a[i];    // array

 select(a,s);     // function calling
 getch();
}

void select(int a[], int s)
{
	int pos,small;
	for(int i =0;i<s;i++)
	{
		small =a[i];         // making the first element of i loop as small
		pos = i;
		for(int j=i+1;j<s;j++)
		{
			if(small>a[j])  // comparing with the second element after i
			{                      // if true
				small = a[j];   // making it small
				pos =j;        // storing the position
			}
		}    // swaping
		int temp = a[i];    // store a[i] in te,p variable
		a[i]= a[pos];       // now a[pos] in a[i]
		a[pos] = temp;      // finally put temp in a[pos]
	}
	// display the array
	cout<<"\n Sorted Array :";
	for(int k=0;k<s;k++)
		cout<<a[k]<<" ";
}