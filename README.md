# EEL-ACTIVITY-3
#include <stdio.h>

int main() {
    char item[20000];
    int quantity;
    float price,total;
    
    printf("\n==================================");
    printf("\n RANKA JEWELLERY SHOP ");
    
    printf("\n==================================");

    
    
    printf("\nEnter item :");
    scanf("%s",&item);
    
    printf("Enter price of one item:");
    scanf("%f",&price);
    
    printf("Enter quantity:");
    scanf("%d",&quantity);
    
    total=price*quantity;
    
    printf("====================================\n");
    printf("Item name: %s:\n",item);
    printf("Item price: %f:\n",price);
    printf("Item quantity: %d:\n",quantity);
    printf("=====================================\n");
    printf("Total bill=%f*%d",total);
    
    
    
    
    printf("\nThankyou for shopping with us!");
    
          return 0;
}
