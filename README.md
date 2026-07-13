#include <iostream>
using namespace std;

int main(){
	int studentAge;
	double studentGrade;
	string studentName;
	int choice;
    	cout<<"===Student Grade Manager==="<<endl;
    	
	    cout<<"1. Add Student"<<endl<<"2. Exit"<<endl;
	    
	    cout<<"Enter your choice"<<endl;
	    
	    cin>>choice;
	    
	    switch(choice){
	    	case 1: 
			cout<< "Enter student Name : "<<endl;
			cin>>studentName;
			cout<< "Enter student Age : "<<endl;
			cin>>studentAge;
			cout<< "Enter student Grade : "<<endl;
			cin>>studentGrade;
			
			cout<<"Student Information"<<endl<<"----------------"<<endl;
			cout<<"Student Name: "<< studentName<<endl;
	    	cout<<"Student Age: "<< studentAge<<endl;
	    	cout<<"Student Grade: "<< studentGrade<<endl;
	    	
	    	if(studentGrade >= 10){
	    		cout<<"Status: Passed";
			}
			else{
				cout<<"Status: Failed";
			}
			
			break;
			
			case 2:
				cout<<"Exit";
				break;
			default : 
			cout<<"Invalid Choice!";	
			
		}
		return 0;
	
}
