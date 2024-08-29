# System.studen
#include<iostream.h>
#include<string.h>
int h=1,moo=1,p=1;const int ii=80000;
void tadd(string stud[],int size,int &x,int arr[],int &poid){
 cout<<"---------------------------"<<endl;
 cout<<"ملاحظه عدد الغرف 10"<<endl;
  cout<<"ملاحظه اخر عدد الاقسام 5"<<endl;
 for(int i=x;i<size;i++){ 
 cout << "اسم الطالب: "; getline(cin,stud[h]);++h;
 cout << "رقم الطالب: "; getline(cin,stud[h]);++h;
 cout << "اسم القسم: "; getline(cin,stud[h]);++h;
 cout << "المستوى الدراسي:"; getline(cin,stud[h]);++h;
cout<< "تاريخ التسجيل باليوم:";
  string pcha;
kml: getline(cin,pcha);
 try{ arr[poid]=stoi(pcha);}
           catch(invalid_argument const &x){
           cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto kml;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto kml;}++poid;
               
cout<<"تاريخ التسجيل بالشهر:";
  string ha;
ml: getline(cin,ha);
 try{ arr[poid]=stoi(ha);}
             catch(invalid_argument const &x){
             cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto ml;} 
               catch(out_of_range const &x){
                 cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
                   goto ml;}  ++poid;
               
cout <<"تاريخ التسجيل بالسنه:";
  string pca;
pml: getline(cin,pca);
 try{ arr[poid]=stoi(pca);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto pml;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto pml;}  ++poid;
               
               
 cout <<"المبلغ المدفوع :"; 
   string pch;
kl: getline(cin,pch);
 try{ arr[poid]=stoi(pch);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto kl;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto kl;}  ++poid;
               
               
  cout << "رقم الغرفة:"; 
    string pa;
k: getline(cin,pa);
 try{ arr[poid]=stoi(pa);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto k;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto k;}  ++moo;
  cout<<"تمت اضافه الطالب بنجاح"<<endl;
  if(i==x)break;
  x++;
 }}//اضافه قسم
 void addsect(string sect[],int mployees[],int size,int &t){
 cout<<"--------------------------"<<endl;
 cout<<"بيانات الموظف الجديد"<<endl;
 for(int i=t;i<size;i++){
 cout << "اسم الموظف: "; getline(cin,sect[p]);++p;
  cout << "عنوان الموظف"; getline(cin,sect[p]);++p;
    cout << "عمل الموظف:";getline(cin,sect[p]);++p;
 cout<<"رقم الموظف:";
 
   string cha;kll:
 getline(cin,cha);
 try{ mployees[moo]=stoi(cha);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto kll;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto kll;}  ++moo;
               
 cout <<"تاريخ دخول الموظف:";
   string cpha;
pkl: getline(cin,cpha);
 try{ mployees[moo]=stoi(cpha);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto pkl;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto pkl;}  ++moo;
 
 cout<<"راتب الموظف بالشهر:";
   string clha;
kpl: getline(cin,clha);
 try{ mployees[moo]=stoi(clha);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto kpl;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto kpl;}  ++moo;
               
cout<< "عدد ساعات العمل باليوم:";
   string pcha;
   kml: getline(cin,pcha);
  try{ mployees[moo]=stoi(pcha);}
         catch(invalid_argument const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto kml;} 
         catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
                     goto kml;}  ++moo;
  cout<<endl<<"تمت اضافه موظف بنجاح:"<<endl;
  if(i==t)break;
 }}//عرض الطلاب
  void read(string stud[],int size,int x,int arr[]){
  	int i=1,oo=0;
  if(x==1)
  cout<<"الرجى ادخل طلاب اولا♠︎"<<endl;
  else{ for(int w=1;w<x;w++){
  cout << "اسم الطالب: "<<stud[i]<<endl;++i;
 cout << "رقم الطالب: "<<stud[i]<<endl;++i;
 cout << "اسم القسم: "<<stud[i]<<endl;++i;
 cout << "المستوى الدراسي:"<<stud[i]<<endl;++i;
  cout << "تاريخ التسجيل باليوم:"<<arr[oo]<<endl;++oo;
 cout << "تاريخ التسجيل بالشهر:"<<arr[oo]<<endl;++oo;
 cout << "تاريخ التسجيل بالسنه"<<arr[oo]<<endl;++oo;
 cout << "المبلغ المدفوع :"<<arr[oo]<<endl;++oo;
  cout << "رقم الغرفة:"<<arr[oo]<<endl; }}}
  //عرض الموظفين
 void readsec(string sect[],int mployees[],int size,int t){int i=1,m=1;
  cout<<"بيانات الموظفين"<<endl;
   for(int w=1;w<t;w++){
   	cout<<"---------------"<<endl; 
 cout << "اسم الموظف: "<<sect[i]<<"\n";++i;
 cout << "عنوان الموظف:"<<sect[i]<<"\n";++i;
  cout << "عمل الموظف:"<<sect[i]<<"\n";++i;
   cout << "رقم الموظف:"<<mployees[m]<<"\n";++m;
 cout <<"تاريخ دخول الموظف:"<<mployees[m]<<"\n";++m;
 cout<<"راتب الموظف بالشهر:";
 cout<<mployees[m]<<"\n";++m;;
cout<< "عدد ساعات العمل باليوم:";
cout<<mployees[m]<<"\n";++m;
 	}}//مستكملين الدفع
 void sea(string stud[],int size,int arr[],int poid){
 if(h>1){	int s=1;
 for(int w=3;w<=poid;w+=4){int z;
 	if(ii-arr[w]==0){z=ii-arr[w];
 		cout<<"الاسم:"<<stud[s]<<endl;s+=4;
 cout<<"المدفوع:"<<arr[w]<<"  الباقي:"<<z<<endl;}}
 cout<<"---------------"<<endl;}
 else cout<<"لاتوجد بيانات حاليأ"<<endl;

 	
}//غير مستكملين
 void mood(string stud[],int size,int arr[],int poid){
 if(h>1){cout<<"---------------"<<endl;
 		int s=1;
 for(int w=3;w<poid;w+=4){int z;
if(ii-arr[w]!=0){z=ii-arr[w];
 		cout<<"الاسم:"<<stud[s]<<endl;s+=4;
 cout<<"المدفوع:"<<arr[w]<<"  الباقي:"<<z<<endl;
}}cout<<"---------------"<<endl;}
else cout<<"لاتوجد بيانات حاليأ"<<endl;
}//حساب المتبقي من الايام

  void pod(string stud[],int size,int arr[],int poid,int d,int m){
 	int s=1;
 	cout<<"بيانات المتبقيه من الايام:"<<endl;
 for(int w=0;w<poid;w++){int k,f,ff;
 	
 f=arr[w];++w;
  ff=arr[w];
ff++;
k=30-f+d+(m-ff)*30;
if(k<5 && k>1){
cout<<"الاسم:"<<stud[s]<<endl;
cout<<"المتبقي من الايام:"<<k<<endl;}
if(k>6){
cout<<"الاسم:"<<stud[s]<<endl;
cout<<"المتبقي من الفتره:"<<k<<endl;}
if(k<1){
cout<<"الاسم:"<<stud[s]<<endl;
cout<<"انتهت الفتره:"<<k<<endl;}
 w+=3;
 	s+=4;
}}//الحسابات
void slk(string stud[],int size,int arr[],int poid){
 	if(h>2){
 	cout<<"---الحسابات----"<<endl; int s=1;
 for(int w=3;w<=poid;w+=4){int z;
if(ii-arr[w]==0){z=ii-arr[w];
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"المدفوع:"<<arr[w]<<"  الباقي:"<<z<<endl;}
if(ii-arr[w]!=0){z=ii-arr[w];
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"المدفوع:"<<arr[w]<<"  الباقي:"<<z<<endl;}
w+=4;
s+=4;}}else cout<<"لاتوجد بيانات حاليأ"<<endl;}
//حساب الطلاب
void mod(string stud[],int size,int arr[],int poid){
 if(h>1){cout<<"---------------"<<endl;
 cout<<"بيانات الغرف:"<<endl;
 	int s=1;int a=0,b=0,c=0,d=0,e=0,f=0,g=0,hh=0;
 	int i=0,j=0;
for(int w=4;w<=poid;w+=5){
if(arr[w]==1){a++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
else if(arr[w]==2){b++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
else if(arr[w]==3){c++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
 else if(arr[w]==4){d++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
 else if(arr[w]==5){e++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 		 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
  else if(arr[w]==6){f++;
 		  cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
else if(arr[w]==7){g++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
else if(arr[w]==8){hh++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
 else if(arr[w]==9){i++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم:"<<arr[w]<<endl;}
else if(arr[w]==10){j++;
 		cout<<"الاسم:"<<stud[s]<<endl;
 cout<<"الغرفه رقم::"<<arr[w]<<endl;}}
 cout<<" عدد الطلاب في الغرفه1:="<<a<<endl;
 cout<<" عدد الطلاب في الغرفه:2="<<b<<endl;
 cout<<" عدد الطلاب في الغرفه:3="<<c<<endl;
 cout<<" عدد الطلاب في الغرفه:4="<<d<<endl;
 cout<<" عدد الطلاب في الغرفه:5="<<e<<endl;
  cout<<" عدد الطلاب في الغرفه:6="<<f<<endl;
  cout<<" عدد الطلاب في الغرفه:7="<<g<<endl;
  cout<<" عدد الطلاب في الغرفه:8="<<hh<<endl;
  cout<<" عدد الطلاب في الغرفه:9="<<i<<endl;
  cout<<" عدد الطلاب في الغرفه:10="<<j<<endl;
cout<<"---------------"<<endl;}
 else cout<<"لا توجد ادخالات بعد";}
 
 //للبحث
void moid(string stud[],int size,const string w,int x){
	 if(h>1){int kk=0;
	bool found=false;
	for(int i=0;i<h;i++){  kk+=1;    
             if (stud[i].find(w) != std::string::npos) {
                found = true;      
                cout << "بيانات الطالب:" << endl;
                cout <<"الاسم:"<<stud[i]<< endl;++i;
                cout<<"الرقم:"<<stud[i]<<endl;++i;
                    cout<<"القسم:"<<stud[i]<<endl;++i;
                        cout<<"المستوى:;"<<stud[i]<<endl;
		
		}if(!found) cout<<"لايوجد"<<endl;
	}}else cout<<"لايوجد بيانات بعد"<<endl;
}



void kkk(string stud[],int size,int arr[],int poid){
 	if(h>2){int sum=0,mod=0;
 	cout<<"---اجمالي الحسابات----"<<endl; int s=1;
 for(int w=3;w<=poid;w+=5){
  int z; 
  z=ii-arr[w];
  sum+=arr[w];mod+=z;
      if(ii-arr[w]==0){
            cout<<"الاسم:"<<stud[s]<<endl;
                   cout<<"المدفوع:"<<arr[w];
                            cout<<"  الباقي:"<<z<<endl;}
   if(ii>arr[w]){
     	cout<<"الاسم:"<<stud[s]<<endl;
              cout<<"المدفوع:"<<arr[w];
                    cout<<"  الباقي:"<<z<<endl; } s+=4;}
 cout<<"اجمالي الدفع: "<<sum<<endl;
     cout<<"اجمالي المتبقي: "<<mod<<endl;
      	}else cout<<"الرجاء ادخال بيانات اولآ"<<endl;
}
void chark(int &x){
	 string cha;  
	 pp:
getline(cin,cha);
 try{ x=stoi(cha);
   if(x>30){
  cout<<"يجب ادخال رقم موجود::"; 
        goto pp;}}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto pp;} 
              
       catch(out_of_range const &x){
      cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
       goto pp;}
	
	
}



 int main(){int size=50,y,x=1,t=1;
 int arr[500],poid=0,mployees[100];
 string stud[500];
 string sect[500];
 cout<<"★ملاحظه في حال وجود مشكله \n يرجى التواصل مع فريق العمل "<<endl;
 cout<<"ت/778461645";
int yy=1,d,m;mmm:
if(yy==2){
 string cha; 
    cout<<endl<<" تاريخ اليوم:"; 
 op:
getline(cin,cha);

 try{ d=stoi(cha);
   if(d>30){
  cout<<"يجب ادخال تاريخ اليوم بين 1و30::"; 
           goto op;}}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto op;} 
       catch(out_of_range const &x){
      cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
       goto op;}
               
 cout<<"تاريخ الشهر:";   string ccha; 
 opo:
getline(cin,ccha);

 try{ m=stoi(ccha);
   if(m>12){
  cout<<"يجب ادخال تاريخ الشهر بين 1و12::"; 
           goto opo;}}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto opo;} 
       catch(out_of_range const &x){
      cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
       goto opo;}
       }
 
  cout<<" \n"; hh:
 cout<<"          شركه اصيل"<<endl;
 
               cout<<"        للاضافه--1"<<endl;
                cout<<"        للعرض----2"<<endl;
                 cout<<"        للبحث----3"<<endl;
                  cout<<"      الاحصائيات----4"<<endl;
                   cout<<"      الحسابات----5"<<endl;
               
                  if(yy==1){
 yy++; goto mmm;}string chak; 
   kl:
            getline(cin,chak);
 try{ y=stoi(chak);}//لتحقق من نوع البيانات 
     catch(invalid_argument const &x){
             cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto kl;}
    catch(out_of_range const &x){
             cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
       goto kl;}

  switch (y) {
            case 1: {cout<<"اختار الاضافه ♠︎"<<endl;
                     cout<<"اضافه طالب:1"<<endl;
                     cout<<"اضافه موظف:2"<<endl;int n;
                     cout<<"~~";
                      string cha; 
 opx:
getline(cin,cha);

 try{ n=stoi(cha);
   if(n>2){
             cout<<"يجب ادخال قيمه بين 1و2::"; 
           goto opx;}}
     catch(invalid_argument const &x){
          cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto opx;} 
       catch(out_of_range const &x){
      cout<<"البيانات المدخله كبيره:"<<endl;
               goto opx;}                   
                     if(n==1){++x;
                     tadd(stud,size,x,arr,poid);
                    } if(n==2)
                     {addsect(sect,mployees,size,t); ++t;
                     }
cout<<"للرجوع للقائمة الرئيسيه اضغط 0"<<endl;
          cout<<"للخروج من البرنامج اضغط 1"<<endl;
                          int kl;  chark( kl);
                          	 if(kl==0)goto hh;	 
                          	 if(kl==1)goto khh;
                    break;
  }
                                                      
        case 2:{
            cout<<"اختار العرض:"<<endl;
            cout<<"عرض الموظفين1"<<endl;
            cout<<"عرض الطلاب 2"<<endl;
              cout<<"عرض مستكملين المبلغ3:"<<endl;
   cout<<"غير مكتمل التسديد4"<<endl;
      cout<<"عرض الفترات المنهيه\nاو على وشك  الانتهاء.5"<<endl;
 cout<<"عرض اجمالي المدفوع والمتبقي.6"<<endl;
  cout<<"للرجوع للقائمة الرئيسيه اضغط 0"<<endl;
                     int c;      cout<<"---~~--";   
                       chark(c);
                if(c==1)readsec(sect,mployees,size, t);
               if(c==2) read(stud,size,x,arr);
              if(c==3)sea(stud,size,arr, poid);
              if(c==4)mood(stud,size,arr,poid);
              if(c==5) { 
             pod(stud,size,arr,poid,d,m);}
              if(c==6)kkk(stud,size,arr, poid);
       if(c==0)goto hh;
                break;}
                case 3:{cout<<"enter the stu::";          
                	string w;
                	cin>>w;
                     moid(stud,size,w, x);
                     cout<<"للرجوع للقائمة الرئيسيه اضغط 0"<<endl;
          cout<<"للخروج من البرنامج اضغط 1"<<endl;
                          int kl; chark(kl);
                          	 if(kl==0)goto hh;	 
                          	 if(kl==1)goto khh;
                          	 	break;
                	}
            case 4:{ mod(stud,size, arr, poid);
             cout<<"للرجوع للقائمة الرئيسيه اضغط 0"<<endl;
          cout<<"للخروج من البرنامج اضغط 1"<<endl;
          int kl;
                          string kha;
hll: getline(cin,kha);
 try{ kl=stoi(kha);}
     catch(invalid_argument const &x){
       cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
              goto hll;} 
              catch(out_of_range const &x){
              cout<<"يرجى ادخال قيمه صحيحه:"<<endl;
               goto hll;}  
                          	 if(kl==0)goto hh;	 
                          	 if(kl==1)goto khh;
           break;}
           
           
           
           
        case 5: {    slk(stud,size,arr,poid);
         cout<<"للرجوع للقائمة الرئيسيه اضغط 0"<<endl;
          cout<<"للخروج من البرنامج اضغط 1"<<endl;
                          int kl;  cin>>kl;
                          	 if(kl==0)goto hh;	 
                          	 if(kl==1)goto khh;
                             break;}{
                default:
                break;}
        }goto hh;
khh:
    return 0;}
 
