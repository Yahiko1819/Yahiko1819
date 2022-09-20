#include<iostream>
using namespace std;

int main() {
    string fname; 
    string mn;
    string lname;
    int age;
    string address;
    
    cout<<"Enter First name: ";
    cin>>fname;
    
    cout<<"Enter Middle name: ";
    cin>>mn;
    
    cout<<"Enter Last name: ";
    cin>>lname;
    
    cout<<"Enter age: ";
    cin>>age;
    cin.ignore();
    

    cout<<"Name: "<<fname<<" "<<mn<<" "<<lname<<endl;
    cout<<"Age: "<<age<<endl;
    return 0;
}
