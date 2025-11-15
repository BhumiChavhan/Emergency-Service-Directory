// Online C compiler to run C program online
#include <stdio.h>
#include <string.h>

int main() {
    // Write C code here
    int i,j,phone_no;
    int phone[5]={1950,100,104,108,1091};
    char loc[5][30]={"Election","Police","Fire Brigade","Ambulance","Women Helpline"};
    int found=0;
   printf("Enter the phone number:");
   scanf("%d",&phone_no);
for(i=0; i<5; i++){
    
      if(phone_no==phone[i]){
       printf("Phone no. - %d\n",phone[i]);
       printf("Location - %s\n",loc[i]);
       printf("phone_no is found and location is matched\n");
       found++;
       break;
      }
    }

      if(found==0)
       {
       printf("Phone no. not found and location is mismatched");
       }
   return 0;
}

