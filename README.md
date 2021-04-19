# Eligible-to-vote-or-not.
This program will help you to understand if a person is Eligible to cast his vote or not.
#include<bits/stdc++.h>
using namespace std;
int Eligible(int age){
	if(age>18){
		cout<<"You age is greater than 18, you're eligible to vote."<<endl;
		return 1;
	}
	else{
	cout<<"You age is less than 18, you're not eligible to vote."<<endl;
	return 0;
}
}
int main(){
int age;
cout<<"Enter the age of the voter: ";
cin>>age;
Eligible(age);
	return 0;
}
