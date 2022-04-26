# class-test-1
athika and ritu got a nice job at a mnc company . She was confused with the salary credited in her account . to verify if the correct amount of HRA and DA was provided to them ritu and athika planned to develop a software that calculates the salary pay if the basic pay was provided . the salary policy of athika and ritu s  company is as follows:    HRA is 80% of the basic pay and DA is 40% of basic pay can  you help ritu and athika in the software development ?      constraints:   20000&lt;_basic&lt;_75000  input format :  single integer representing the basic pay of the employee output fomat:  print the gross salary of employee by adding the certain amount of HRA nd DA to the basic pay 
#include <stdio.h>
int main()
{
float basic,sal;
scanf("%f",&basic);
sal=0.8*basic+0.4*basic+basic;
printf("%.2f",sal);
  reaturn 0;
}
