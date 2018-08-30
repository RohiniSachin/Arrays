/* Arrays
Programs on array in c++
#Find Frequency of a character in a word*/

#include<iostream>
using namespace std;

int main()
{
char word[100];
char letter;
int len;
int count=0;

cout<<"Enter a word";
cin.get(word,100);

cout<<"Enter letter";
cin>>letter;

for (int i=0; word[i]!='\0'; i++)
{
  len = i;
 }
 
 for(int j=0;j<len;j++)
 {
   if(word[j]==letter)
    count++;
  }
  cout<<"\n Frequency of "<<letter <<count;
  return 0;
  }
