# Love-Text
#include <iostream> 

using namespace std;

int main()
{
	string Your_Favorite_Color, Your_Favorite_Things_or_Hobby, Your_Name;
	
	cout << "Enter Your_Favorite_Color: ";
	getline (cin, Your_Favorite_Color) ;
	cout << "Enter Your_Favorite_Things_or_Hobby: ";
	getline (cin, Your_Favorite_Things_or_Hobby) ;
	cout << "Enter Your_Name: ";
	getline (cin, Your_Name) ;  
	cout << Your_Favorite_Color << " isn't brighter than your smile." << endl;   
	cout << Your_Favorite_Things_or_Hobby <<" are great.By the way, Your Beauty is Incomparable " << endl;
	cout << "I love " << Your_Name << " too much when I first saw your smile."  << endl;
	return 0;
}
