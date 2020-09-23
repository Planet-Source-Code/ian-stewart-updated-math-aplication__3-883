<div align="center">

## Updated Math Aplication


</div>

### Description

Please vote for this code!!! This code adds, subtracts, multiplies, divides, finds the square root of a number, finds the circumference of a circle, finds the area of a quadrilateral, finds the angle of a triangle when two are given, solve for the hypontinus of a right angle (Pythagoreams Theorum), and convert Farenheit to Celsius.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Stewart](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-stewart.md)
**Level**          |Beginner
**User Rating**    |4.8 (19 globes from 4 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-stewart-updated-math-aplication__3-883/archive/master.zip)





### Source Code

```
#include <iostream.h>
#include <math.h>
#include <fstream>
void main()
{
	int asmd;
	float add1;
	float add2;
	float subtract1;
	float subtract2;
	float multiply1;
	float multiply2;
	float divide1;
	float divide2;
	float x;
	float dia;
	float quad1;
	float quad2;
	float ang1;
	float ang2;
	float adj;
	float opp;
	float celsius;
	int quit;
	cout << " Do you want to..." << endl;
	cout << " 1) Add" << endl;
	cout << "  2) Subtract" << endl;
	cout << "  3) Multiply" << endl;
	cout << "  4) Divide" << endl;
	cout << "  5) Find the square root of a number" << endl;
	cout << "   6) Find out the circumference of a circle" << endl;
	cout << "   7) Find out the area of a quadralateral" << endl;
	cout << "   8) Find out what an angle of a triangle is" << endl;
	cout << "   9) Solve for the hypontinus of a right angle (Pythagoreams Theorum)" << endl;
	cout << "    10) Convert from Farenheit to Celsius" << endl;
	cin >> asmd;
	{
	if (asmd==1)
	{
		cout << "Enter the first number" << endl;
  cin >> add1;
		cout << "Enter the second number" << endl;
		cin >> add2;
		cout << "Your answer is: " << add1+add2 << endl;
	}
	else if(asmd==2)
	{
		cout << "Enter the first number" << endl;
	 cin >> subtract1;
		cout << "Enter the second number" << endl;
		cin >> subtract2;
		cout << "Your answer is: " << subtract1-subtract2 << endl;
	}
 else if(asmd==3)
	{
		cout << "Enter the first number" << endl;
	 cin >> multiply1;
		cout << "Enter the second number" << endl;
		cin >> multiply2;
		cout << "Your answer is: " << multiply1*multiply2 << endl;
	}
 else if(asmd==4)
	{
		cout << "Enter the dividend" << endl;
	 cin >> divide1;
		cout << "Enter the divisor" << endl;
		cin >> divide2;
		cout << "Your answer is: " << divide1/divide2 << endl;
	}
	else if(asmd==5)
	{
		cout << "Enter a number" << endl;
	 cin >> x;
		cout << "Your answer is: " << sqrt(x) << endl;
	}
	else if(asmd==6)
	{
		cout << "Enter the diameter of the circle" << endl;
	 cin >> dia;
		cout << "Your answer is: " << dia*3.14 << endl;
	}
	else if(asmd==7)
	{
		cout << "Enter the length of the quadrilateral" << endl;
	 cin >> quad1;
		cout << "Enter the width of the quadrilateral" << endl;
		cin >> quad2;
		cout << "Your answer is: " << quad1*quad2 << endl;
	}
	else if(asmd==8)
	{
		cout << "Enter the 1st angle" << endl;
	 cin >> ang1;
		cout << "Enter the 2nd angle" << endl;
		cin >> ang2;
		cout << "Your answer is: " << 180-(ang1+ang2) << endl;
	}
	else if(asmd==9)
	{
		cout << "Enter the value of the adjectant side" << endl;
	 cin >> adj;
		cout << "Enter the value of the opposite side" << endl;
		cin >> opp;
		cout << "Your answer is: " << sqrt((adj*adj)+(opp*opp) )<< endl;
	}
	else if(asmd==10)
 Range:
 	cout << "Enter a range of degrees (Ex. 0 150)";
 int low;
 int high;
 	cin >> low >> high;
 int diff = high - low;
 if (diff >= 10001)
  	{
  	cout << "Enter a smaller range.\n";
  	goto Range;
  	}
  	std::fstream fout;
  	fout.open("f2c.txt" , std::ios::out);
  	if (!fout.is_open()) return;
  	cout << "Farenheit to Celcius Conversion\n";
  	fout << "Farenheit to Celcius Conversion\n";
  	cout << "Farenheit\tCelcius\n";
  	fout << "Farenheit\tCelcius\n";
  	cout << "---------\t-------\n";
  	fout << "---------\t-------\n";
  int faren2;
  	while (faren2 < high)
   {
   faren2 = low;
   celsius = 0.55f * (faren2 - 32);
   cout << faren2 << "\t\t" << celsius << '\n';
   low++;
  }
	cout << "Press any key and return to quit" << endl;
	cin >> quit;
}
}
```

