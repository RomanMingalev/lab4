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
int product[2][2];
void init(){
int n=3;
int m=3;
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
Form1->StringGrid3->Visible=true ;
int n=3;
int m=3;
for (int i = 0; i < n; i++)
        for (int j = 0; j < n; j++)
            for (int inner = 0; inner < 3; inner++)
                product[i][j] += a[i][j] * b[i][j];
for(int i=0; i<n; i++)
      for(int j=0; j<m; j++)
      {Form1->StringGrid3->Cells[j][i]=product[i][j];
       }
}


//-------------------------------------------------------------------- -------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button1Click(TObject *Sender)
{
matrix();




}
//---------------------------------------------------------------------------
void __fastcall TForm1::FormCreate(TObject *Sender)
{
init();
}
//---------------------------------------------------------------------------
