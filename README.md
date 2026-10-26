#include<iostream>
using namespace std;
class student
{
  private:
       int rollno;
       string name;
  public:
       //constructor
       student(int r,string n)
  {
  rollno=r;
  name=n;
  cout<<"student object created"<<endl;
  }
  //member function
  void display()
  {
  cout<<"roll number:"<<rollno<<endl;
  cout<<"name:"<<name<<endl;
  }
  //destructor
  ~student
  { 
  cout<<"student object destroyed"<<endl;
  }
};
int main()
{
students1(101,"ARUN")
s1.display();
return 0;
}M
   
  
