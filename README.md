#include<iostream.h>
#include<conio.h>
class student 
{
private:
int rno,fees;
char name[10];
public:
void read()
{
cout<<"\n enter the register no,name,and fees";
cin>>rno>>name>>fees;
}
void display()
{
cout<<"\n student details";
cout<<"\n register no="<<rno;
cout<<"\n name="<<name;
cout<<"\n fees="<<fees;
}
};
void main()
{
student s1,*sp;
sp=&s1;
sp->read();
sp->dispaly();
}
