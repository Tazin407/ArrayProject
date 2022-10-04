#include<iostream>
using namespace std;

int main(){

   int i,j;
   float num[100], sum=0.0 ,av;
   char name[100];

   cout<<"Enter the number of students "<<endl;
   cin>>j;

   while (j>100)
   {
      cout<<"Can't take too much load "<<endl;
      cout<<"Enter your value again"<<endl;
      cin>>j;
   }

   cout<<"Now entry the data "<<endl;
   
   for (int i = 0; i <j; i++)
   {
      cin>>num[i];

      sum+=num[i];
      cout<<"The sum is "<<sum <<endl;
   }

   av=sum/j;
   cout<<"The avarage is "<<av<<endl;
   if (av>=70)
   {
      cout<<"Your students are exellent "<<endl;
   }
   else if (av >=55 && av!=70)
   {
      cout<<"Needs improvement "<<endl;
   }
   
   else
   {
      cout<<"It's not too late to start over "<<endl;
   }
   
   
   

return 0;
}

 
