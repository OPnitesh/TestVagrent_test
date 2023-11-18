#include <iostream>

using namespace std;

int main()
{
  string product[4] = {"leather_wallet","umbrella","cigarette","honey"};
  int unit_price;
  int gst;
  int quantity;
  int max_amount=0;
  int gst_amount = 0;
  int i =0;
  while(i<4){
      if(product[i]=="leather_wallet"){
          gst = 18;
          unit_price = 1100;
          int amount = ((unit_price*gst)/100+unit_price);
          gst_amount = (unit_price*gst)/100;
          max_amount = amount-(amount*5/100);
           cout<<"total amount = "<<max_amount<<"  gst amount = "<<gst_amount<<endl;
          i++;
      }
      else if(product[i]=="umbrella"){
          gst = 12;
          unit_price = 900;
          quantity = 4;
          int amount = quantity*((unit_price*gst)/100+unit_price);
          gst_amount = quantity*(unit_price*gst)/100;
          max_amount = amount-(amount*5)/100;
          cout<<"max total amount = "<<max_amount<<"  max gst amount = "<<gst_amount<<endl;
          i++;
      }
      else if(product[i]=="cigarette"){
          gst = 28;
          unit_price = 200;
          quantity = 3;
          int amount = quantity*((unit_price*gst)/100+unit_price);
          gst_amount = quantity*(unit_price*gst)/100;
          max_amount = amount;
           cout<<"total amount = "<<max_amount<<"  gst amount = "<<gst_amount<<endl;
          i++;
      }
      else if(product[i]=="honey"){
          gst = 0;
          unit_price = 100;
          quantity = 2;
          int amount = quantity*((unit_price*gst)/100+unit_price);
          gst_amount = quantity*(unit_price*gst)/100;
          max_amount = amount;
          cout<<"total amount = "<<max_amount<<"  gst amount = "<<gst_amount<<endl;
          i++;
      }
      
      
  }
}
