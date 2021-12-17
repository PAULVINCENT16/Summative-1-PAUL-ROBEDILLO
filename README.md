# Summative-1-PAUL-ROBEDILLO
#include <iostream>
#include <string>
using namespace std;

int main()
{

	char age;
	double age;

	cout << "This program is to check the name of the person if they enjoy or cancelled their trip" << endl;

	cout << "[Y] for Enjoy or [N] for cancelled\n" << endl;

	cout << "\nEnter your age in numbers\n";
	int age;
	cin >> age;

	switch (age)
	{
	case 16:
		cout << "You entered Jenny's name";
		cout << "She [Y] enjoy being at the mall";
		break;
	case 17:
		cout << "You entered Mark's name";
		cout << "He [Y] enjoy being at the mall";
		break;
	case 18:
		cout << "You entered John's name";
		cout << "He [N] Cancelled to go at the mall";
		break;
	case 19:
		cout << "You entered Carlo's name";
		cout << "He [N] Cancelled to go at the park";
		break;
	case 20:
		cout << "You entered Jomar's name";
		cout << "He [Y] Enjoy at the istanbul";
		break;
	case 21:
		cout << "You entered Jordan's name";
		cout << "He [Y] Enjoy being at the park";
		break;
	case 22:
		cout << "You entered Antonhy's name";
		cout << "He [Y] Enjoy at the istanbul";
		break;
	case 23:
		cout << "You entered Paul's name";
		cout << "He [N] Cancelled to go at the istanbul";
		break;
	case 24:
		cout << "You entered Lucy's name";
		cout << "She [Y] Enjoy at the istanbul";
		break;
	case 25:
		cout << "You entered Jam's name";
		cout << "He [Y] Enjoy at the istanbul";
		break;
	case 26:
		cout << "You entered Justin's name";
		cout << "He [Y] Enjoy at the hawaii";
		break;
	case 27:
		cout << "You entered Marloe's name";
		cout << "He [Y] Enjoy at the hawaii";
		break;
	case 28:
		cout << "You entered Vincent's name";
		cout << "He [N] Cancelled to go at the hawaii";
		break;
	case 29:
		cout << "You entered Arthur's name";
		cout << "He [Y] Enjoy at the hawaii";
		break;
	case 30:
		cout << "You entered Andrei's name";
		cout << "He [N] Cancelled to go at the hawaii";
		break;
	}
	return 0;
}
