// **Lecture-9_Exercises**

// Reverse 9
#include <iostream>
using namespace std;

int main()
{
	int num = 108;
	while (num >= 9) {
		cout << num << endl;
		num = num - 9;
	}
	cin.get();
	return 0;
}
  
  ----------------------------------
// Pointless Box
  #include <iostream>
using namespace std;
  
int main()
{
	int num;
	cout << "Enter a number (1 or 2)" << endl;
	cin >> num;
	while (num == 1 || num == 2)
	{

		if (num == 1) {
			cout << "You have entered number 1" << endl;
			cout << "enter a number." << endl;
			cin >> num;
		}
		else
		{
			cout << "You have entered number 2." << endl;
			cout << "enter a number." << endl;
			cin >> num;
		}
	}
	cout << "You did not enter 1 or 2" << endl;
}
  
 -------------------------------------------------------------
 // Input Improvement
  #include <iostream>
using namespace std;
  
int main() {
	char input;
	do {
		cout << "Would you like to Quit (Y/N)?" << endl;
		cin >> input;
	} while ((input != 'Y' && input != 'y'));
	cout << "Game Over" << endl;
	return 0;
}
