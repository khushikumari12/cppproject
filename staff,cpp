
#include <iostream>
using namespace std;
class staff
 {protected:

     int code;

     char name[20];

 public:

     void getstaff(void)

     {
   cout<<"\n\nEnter code :-";
   cin>>code;
   cout<<"Enter name :-";
    cin>>name;
     }
     void dispstaff(void)
     {
      cout<<"\nNAME :-"<<name;
      cout<<"\nCODE :-"<<code;
 }
 };
   class teacher :public staff
    {
        public:
      
        char subject[20],publication[30];
    void show()
    {  
        cout<<"Please enter your subject "<<endl;
        cin>>subject;
        cout<<"Please enter your publication"<<endl;
        cin>>publication;
        }
};
class officer : public  staff
{
    public:
    char grade[10];
    officer()
    {
        cout<<"Please enter your grade"<<endl;
        cin>>grade; 
    }
    void show()
    {
        cout<<"grade : "<<grade<<endl;
    }
};
class typist : public  staff
{
    public:
    int speed,wages;
    typist()
    {cout<<"Please enter your speed "<<endl;
        cin>>speed;
        cout<<"Please enter your wages"<<endl;
        cin>>wages;
    }
    void show()
    {cout<<"speed : "<<speed<<endl;
    cout<<"wages : "<<wages<<endl;
    }
};
int main()
{ char op;
    cout<<"Your are a teacher or officer or typist ? \n(Enter T(for teacher) or o(for officer) or k(for typist)"<<endl;
    cin>>op;
    if(op=='T')
    {
        teacher obj;
        obj.show();
    }
    else if(op=='o')
    {
        officer obj2;
        obj2.show();
    }
     else if(op=='k')
    {        typist obj2;
        obj2.show();
    }
    else
    {cout<<"Please enter a valid option";
    }
    return 0;
}
