# Paipala
/* File Handling with C++ using ifstream & ofstream class object*/
/* To write the Content in File*/
/* Then to read the content of file*/
//#include <iostream>
//#include <string>

/* fstream header file for ifstream, ofstream,
/fstream classes */
//#include <fstream>

///using namespace std;

// Driver Code
//int main()
//{
	// Creation of ofstream class object
	//ofstream fout;

	//string line;

	// by default ios::out mode, automatically deletes
	// the content of file. To append the content, open in ios:app
	/// fout.open("sample.txt", ios::app)
	///fout.open("sample.txt");

	// Execute a loop If file successfully opened
	//while (fout) {

		// Read a Line from standard input
		//getline(cin, line);
		//cin>>line; 

		// Press -1 to exit
		//if (line == "-1")
			//break;

		// Write line in file
		//fout << line << endl;
	//}

	/// Close the File
	//fout.close();

	//return 0;
//}

//#include <iostream>
//#include <string>
//#include <fstream>
//using namespace std;
//int main() {
//	string mystring;
//	cout << "What do you want to say?";
//	ofstream a;
//	a.open("conversation.txt", ios::app);
//	while (a) {
//
//		cin >> mystring;
//		if (mystring == "-1")
//			break;
//
//		a << mystring << endl;
//	}
//	a.close();
//	return 0;
//}



//#include <iostream>
//#include <string>
//#include <fstream>
//
//using namespace std;
//
//int main() {
//		
//	
//	fstream my_file;
//	
//	my_file.open("my_file.txt", ios::out);
//
//	if (!my_file) {
//		
//		cout << "File not created!";
//		
//	}
//	
//	else {
//		
//		cout << "File created successfully!";
//
//		my_file << "    ";
//
//		my_file.close();
//		
//	}
//	int status;
//	char fileName[20];
//	cout << "Enter the Name of File: ";
//	cin >> fileName;
//	status = remove(fileName);
//	if (status == 0)
//		cout << "\nFile Deleted Successfully!";
//	else
//		cout << "\nError Occured!";
//	cout << endl;
//	
//	return 0;
//
//}

//#include <iostream>
//#include <fstream>
//#include <string>
//#include <vector>
//#include <stdio.h>
//using namespace std;
//
//int main()
//{
//	int answ;
//	vector <string> rom_cip{ "i", "ii", "iii", "iv","v","vi","vii","viii","ix", "x", "xi", "xii", "xiii", "xiv", "xv", "xvi", "xvii", "xviii", "xix", "xx" };
//	cin >> answ;
//	if (answ > 20 || answ < 0) { cout << "WRONG INPUT" << endl; exit(-1); }
	//if (answ == 0)
		//cout << "Error";
	//if (answ > 20)
		//cout << "Error";
//	cout << rom_cip[answ - 1];
//	ofstream a;
//	a.open("roman.txt", ios::app);
//	a << answ << " - " << rom_cip[answ - 1];
//	a.close();
//	int parole;
//	cin >> parole;
//	if (parole == 123)
//	{
//		int status;
//		char fileName[20];
//		cout << "Enter the Name of File: ";
//		cin >> fileName;
//		status = remove(fileName);
//		if (status == 0)
//			cout << "\nFile Deleted Successfully!";
//		else
//			cout << "\nError Occured!";
//		cout << endl;
//	}
//		
//	return 0;
//}

#include <iostream>
#include <string>
#include <vector>
using namespace std;
int main()
{
	vector<string>name
		cout << "Ievadiet savu vardu" << endl;

}
