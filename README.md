
#include<iostream>
using namespace std;


int main(){

string Product;
int quantity;

//Products
string FRIES;//110
string BURGER;//25
string RICE;//15



int calc;

string drinks;//
string coke;//15pesos
string royal;//15pesos
string mountaindew;//20pesos


cout<<"!!MENU!!"<<endl;
cout<<"__________________"<<endl;
cout<<"FOODS:"<<endl;
cout<<"__________________"<<endl;
cout<<"FRIES"<<endl;
cout<<"BURGER"<<endl;
cout<<"RICE"<<endl;
cout<<"__________________"<<endl;

cout<<"DRINKS:"<<endl;
cout<<"__________________"<<endl;
cout<<"COKE"<<endl;
cout<<"ROYAL"<<endl;
cout<<"MTDEW"<<endl;
cout<<"__________________"<<endl;
cout<<"ENTER PRODUCT:"<<endl;
cin>>Product;//Product Input

if(Product=="FRIES" || Product=="fries"){
cout<<"__________________"<<endl;

cout<<"ENTER QUANTITY:"<<endl;
cout<<"__________________"<<endl;
cin>>quantity;

calc=110*quantity;
}
if(Product=="BURGER" || Product=="burger"){
cout<<"__________________"<<endl;
cout<<"ENTER QUANTITY:"<<endl;
cout<<"__________________"<<endl;
cin>>quantity;
calc=15*quantity;
}
if(Product=="RICE" || Product=="rice"){

cout<<"__________________"<<endl;
cout<<"ENTER QUANTITY:"<<endl;
cout<<"__________________"<<endl;
cin>>quantity;
}

cout<<"ENTER YOUR DRINKS:"<<endl;
cin>>drinks;
cout<<"__________________"<<endl;

int drinks1;
if(drinks=="coke" || drinks=="COKE"){
drinks1+=15;
}
if(drinks=="royal" || drinks=="ROYAL"){
drinks1+=15;}

if(drinks=="mountaindew" || drinks=="MOUNTAINDEW"){
drinks1+=20;}

string dessert;



string milktea;
string teamac;
string flavor;
int comp;
cout<<"ENTER A DESSERT:"<<endl;
cin>>dessert;

if(dessert=="milktea" || dessert=="MILKTEA"){
cout<<"__________________"<<endl;
cout<<"ENTER A FLAVOR:"<<endl;
cin>>flavor;
cout<<"__________________"<<endl;
comp+=45;
}
string flavor1;
if(dessert=="TEA" || dessert=="tea"){
cout<<"__________________"<<endl;
cout<<"COLD OR HOT:"<<endl;
cin>>flavor1;
cout<<"__________________"<<endl;

comp+=30;


}
int servpay=50;


cout<<"__________________"<<endl;
cout<<"RECEIPT"<<endl;
cout<<"__________________"<<endl;
cout<<"PRODUCT:"<<Product<<endl;
cout<<"__________________"<<endl;
cout<<"QUANTITY:"<<quantity<<endl;
cout<<"__________________"<<endl;
cout<<"DRINK:"<<drinks<<endl;
cout<<"__________________"<<endl;
cout<<"DESERT:"<<dessert<<endl;

cout<<"FLAVOR:"<<flavor<<flavor1<<endl;
cout<<"__________________"<<endl;
cout<<"SERVICE PAY:-"<<servpay<<endl;
cout<<"__________________"<<endl;
cout<<"TOTAL AMOUNT:"<<(calc+drinks1+comp)-servpay<<endl;
cout<<"__________________"<<endl;




    return 0;
    }
    
    












