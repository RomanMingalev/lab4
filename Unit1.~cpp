//---------------------------------------------------------------------------

#include <iostream>
#include <vcl.h>
#pragma hdrstop
#include <fstream>
#include <string>
#include <stdio.h>
#include <Math.hpp>
#include <cstdio>
#include "Unit1.h"
#include <math.h>
#include<stdlib.h>
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma resource "*.dfm"
TForm1 *Form1;
 int a[2][2];
int b[2][2];
int n=3;
int m=3;
int product[2][2];

void Umnog1(int i){
Form1->Edit1->Text=String(atoi(Form1->Edit1->Text.c_str())*i);
Form1->Edit2->Text=String(atoi(Form1->Edit2->Text.c_str())*i);
Form1->Edit3->Text=String(atoi(Form1->Edit3->Text.c_str())*i);
Form1->Edit4->Text=String(atoi(Form1->Edit4->Text.c_str())*i);
Form1->Edit5->Text=String(atoi(Form1->Edit5->Text.c_str())*i);
Form1->Edit6->Text=String(atoi(Form1->Edit6->Text.c_str())*i);
Form1->Edit7->Text=String(atoi(Form1->Edit7->Text.c_str())*i);
Form1->Edit8->Text=String(atoi(Form1->Edit8->Text.c_str())*i);
Form1->Edit9->Text=String(atoi(Form1->Edit9->Text.c_str())*i);
}
void Umnog2(int i){
Form1->Edit10->Text=String(atoi(Form1->Edit10->Text.c_str())*i);
Form1->Edit11->Text=String(atoi(Form1->Edit11->Text.c_str())*i);
Form1->Edit12->Text=String(atoi(Form1->Edit12->Text.c_str())*i);
Form1->Edit13->Text=String(atoi(Form1->Edit13->Text.c_str())*i);
Form1->Edit14->Text=String(atoi(Form1->Edit14->Text.c_str())*i);
Form1->Edit15->Text=String(atoi(Form1->Edit15->Text.c_str())*i);
Form1->Edit16->Text=String(atoi(Form1->Edit16->Text.c_str())*i);
Form1->Edit17->Text=String(atoi(Form1->Edit17->Text.c_str())*i);
Form1->Edit18->Text=String(atoi(Form1->Edit18->Text.c_str())*i);
}

void transporate(){
AnsiString temp;
temp=Form1->Edit2->Text;
Form1->Edit2->Text=Form1->Edit4->Text;
Form1->Edit4->Text=temp;

temp=Form1->Edit6->Text;
Form1->Edit6->Text=Form1->Edit8->Text;
Form1->Edit8->Text=temp;

temp=Form1->Edit3->Text;
Form1->Edit3->Text=Form1->Edit7->Text;
Form1->Edit7->Text=temp;

temp=Form1->Edit11->Text;
Form1->Edit11->Text=Form1->Edit13->Text;
Form1->Edit13->Text=temp;

temp=Form1->Edit15->Text;
Form1->Edit15->Text=Form1->Edit17->Text;
Form1->Edit17->Text=temp;

temp=Form1->Edit12->Text;
Form1->Edit12->Text=Form1->Edit16->Text;
Form1->Edit16->Text=temp;
}
void init(){

randomize();
Form1->Edit1->Text=String(rand()%10);
Form1->Edit2->Text=String(rand()%10);
Form1->Edit3->Text=String(rand()%10);
Form1->Edit4->Text=String(rand()%10);
Form1->Edit5->Text=String(rand()%10);
Form1->Edit6->Text=String(rand()%10);
Form1->Edit7->Text=String(rand()%10);
Form1->Edit8->Text=String(rand()%10);
Form1->Edit9->Text=String(rand()%10);
Form1->Edit10->Text=String(rand()%10);
Form1->Edit11->Text=String(rand()%10);
Form1->Edit12->Text=String(rand()%10);
Form1->Edit13->Text=String(rand()%10);
Form1->Edit14->Text=String(rand()%10);
Form1->Edit15->Text=String(rand()%10);
Form1->Edit16->Text=String(rand()%10);
Form1->Edit17->Text=String(rand()%10);
Form1->Edit18->Text=String(rand()%10);
}
void matrix(){

Form1->StringGrid3->Visible=true ;

for (int i = 0; i < n; i++)
        for (int j = 0; j < n; j++)
            for (int inner = 0; inner < 3; inner++)
                product[i][j] += a[i][j] * b[i][j];
for(int i=0; i<n; i++)
      for(int j=0; j<m; j++)
      {Form1->StringGrid3->Cells[j][i]=product[i][j];
       }
}

void Init1(){
a[0][0]=atoi(Form1->Edit1->Text.c_str());
a[0][1]=atoi(Form1->Edit2->Text.c_str());
a[0][2]=atoi(Form1->Edit3->Text.c_str());
a[1][0]=atoi(Form1->Edit4->Text.c_str());
a[1][1]=atoi(Form1->Edit5->Text.c_str());
a[1][2]=atoi(Form1->Edit6->Text.c_str());
a[2][0]=atoi(Form1->Edit7->Text.c_str());
a[2][1]=atoi(Form1->Edit8->Text.c_str());
a[2][2]=atoi(Form1->Edit9->Text.c_str());
b[0][0]=atoi(Form1->Edit10->Text.c_str());
b[0][1]=atoi(Form1->Edit11->Text.c_str());
b[0][2]=atoi(Form1->Edit12->Text.c_str());
b[1][0]=atoi(Form1->Edit13->Text.c_str());
b[1][1]=atoi(Form1->Edit14->Text.c_str());
b[1][2]=atoi(Form1->Edit15->Text.c_str());
b[2][0]=atoi(Form1->Edit16->Text.c_str());
b[2][1]=atoi(Form1->Edit17->Text.c_str());
b[2][2]=atoi(Form1->Edit18->Text.c_str());
}
//-------------------------------------------------------------------- -------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button1Click(TObject *Sender)
{
Init1();
matrix();




}
//---------------------------------------------------------------------------
void __fastcall TForm1::FormCreate(TObject *Sender)
{
init();
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button2Click(TObject *Sender)
{
Init1();
transporate();
}
//---------------------------------------------------------------------------


void __fastcall TForm1::Button4Click(TObject *Sender)
{
Umnog1(atoi(Form1->Edit19->Text.c_str()));
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button3Click(TObject *Sender)
{
Umnog2(atoi(Form1->Edit20->Text.c_str()));
}
//---------------------------------------------------------------------------

