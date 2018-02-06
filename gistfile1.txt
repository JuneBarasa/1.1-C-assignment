#include <iostream>

using namespace std;

 int main()
 {
char vote;
char C;
int Y=0;
int N=0;
int U=0;

while(1)
{

  cout<<"Welcome!Do you think October 26, 2017 elections will take place?"<<endl;
  cout<<endl;

  cout<<"Please enter any of the following opinions; Y-Yes, N-No, U-Undecided/Not Sure"<<endl;
  cin>>vote;

  switch (vote)
  {
  case 'Y':
  case 'y':
      cout<<"Yes, elections will take place"<<endl;
      Y=Y+1;
      break;

  case 'N':
  case 'n':
    cout<<"No, elections will NOT take place"<<endl;
    N=N+1;
    break;

  case 'U':
  case 'u':
    cout<<"Not sure/Undecided whether elections will take place"<<endl;
    U=U+1;
    break;
  }
    cout<<"Here are the results of the opinions entered:"<<endl;
    cout<<endl;

   if(vote)
      {
          cout<<"Y= "<<Y<<endl;


      }
      if(vote)
      {
       cout<<"N= "<<N<<endl;

      }
      if(vote)
      {
          cout<<"U= "<<U<<endl;


      }

cout<<"Thank you! Next voter, please click B to enter opinion."<<C<<endl;
cin>>C;
cout<<endl;

}
     return 1;

 }
