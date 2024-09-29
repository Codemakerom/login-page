//login page

#include<iostream>
#include<fstream>

void main()
{
char choice;
cout<<"\n 1.login";
cout<<"\n2.signup";
cout<<"\n3.forgot password";
cout<<"\n4.Exit";
cout<<"\n enter your choice";

class temp()
{
string username,Email, password;
fstream file;
public:
void login();
void signup();
void forgot password();
}obj;
switch(choice)
{
case 1:
obj.login();


break;

case2:
obj.sign();


break;


case3:
obj.forgot password();

break;

case4:
return(0);


break;
default:
cout<<"\n Invalid selection;

}



break;
case5:

void temp::signup()
{
cout<<"\n enter your username";
getline(cin,username);
cout<<"\n enter your emailaddress";
getline(cin,email);
cout<<"\n enter your password";
getline(cin,password);
file.open("Logindata.txt",ios::open | ios::app);
file<<username<<"*"<<email<<"*"<<password<<end1;
file.close();
}
void temp::login()
{
string seachname,searchpass,searchemail;
cout<<"\n _________LOGIN_________";
cout<<"\n ENTER YOU USERNAME;
getline(cin,searchname);
cout<<"\n ENTER YOUR PASSWORD";
cout<<"\n getline(cin,searchpass);
file.open(Logindata.txt<ios::in);
getline(file,searchname'*')
getline(file,email'*')
getline(file,searchpass'\n')
}
while(!file.eof())
{
if(username==searchname)
{
if(password==searchpass)
{
cout<<"\nAccount Login is Sucessful....';
cout<<"\n username::"<<username<<end1;
cout<<"\n email:"<<email<<end1;
}
else 
{ 
cout<<"\n password is incorrect.....!";
}
}
getline(file,username,'*')
getline(file,email,'*')
getline(file,password'\n')
file.close();
}
void temp::forgot password()
{
cout<<"\n enter your username";
getline(cin,username);
cout<<"\n enter your email";
getline(cin,email);
file.open(Logindata.txt,ios::in)
getline(file,username,'*')
getline(file,email,'*')
getline(file,password)

 while(!file.eof)
{
if(username==searchname)
{
if(email=searchpass)
{
cout<<"\n Account is found";
cout<<"\n your password::"<<password<<end1;

}else
{
cout<,"\n Not found!....?
}
}
file.close();



}






















































