# Homework10
#include <stdio.h>

int main (){
  
 int total_days = 500;
 int years = 0;
  int weeks = 0;
 int days = 0; 

 years = total_days/365;
 total_days = total_days % 365;
 weeks = total_days/ 7;
 days = total_days % 7;
 printf("Total days: %d is equal to %d years,%d weeks, %d days.\n", total_days,years,weeks,days);
 return 0;
}
