# include<stdio.h>

int main(){
float amount, gst,cgst,sgst, discount, payable;

printf(" Enter amount:  ");
scanf("\n %f",& amount);
printf("\n Enter gst: ");
scanf("\n %f",& gst);
printf("\n Enter cgst: ");
scanf("\n %f", & cgst);
printf("\n Enter sgst: ");
scanf("\n %f", & sgst);

 float totaltax= gst+cgst+sgst;
 printf("%f",totaltax);
  discount = amount-7/100;
  payable = totaltax+gst-discount;
 printf("\n The net amout to be paid after 7% Discount: %2f", payable );
 
return 0;
}
