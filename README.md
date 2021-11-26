# Find-the-9s-do-while-loop
#include<iostream>
using namespace std;
int main()
{

		int sum = 0;
		int num = 0;   //declaring variables with datatype integer
		cout << "Numbers that are divisible by 9 are :\n " << endl;
		do //using for loop
		{
			num++;
			if (num % 9 == 0)
			{
				cout << num << endl;  //displaying all the numbers divisible by 9 from 100-200  
				sum = sum + num;    //adding all the numbers divisible by 9
			}

		}
		while (num <= 200);
		cout << "\nSum of all the numbers divisible by 9 are = " << sum << endl;   ///displaying sum
		
		return 0;
}
