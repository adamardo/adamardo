#include <iostream>
using namespace std;
int main(){
	string username = "Ardo";
	string password = "ardo"; 
	string usernameInput, passwordInput;
	while(true){	
		cout << "Enter Username: ";
		cin >> usernameInput;
		cout << "Enter password: ";
		cin >> passwordInput;
		if(usernameInput != username && passwordInput != password){
		cout << "username and password not correct try again" << endl;
		continue;
		}
		
		else if(usernameInput != username){
		cout << "username not correct try again" << endl;
		
		continue;
		}
		else if(passwordInput != password){
		cout << "password not correct try again" << endl;
		
		continue;
	}
		
	    
		else{
			cout << "login successful!!!" << endl;
		
		}
	
		
	
	
return 0;
	
}
}
