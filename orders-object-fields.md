# Orders__c Object Fields

| Field Label  | API Name          | Data Type | Values/Reference |
|---------------|-------------------|-----------|------------------|
| Order Number  | Order_Number__c   | Auto Number | Format: ORD-{0000} |
| Order Date    | Order_Date__c     | Date | - |
| Status        | Status__c         | Picklist | New, Shipped, Delivered |
| Customer      | Customer_c       | Lookup(Customer_c) | Links to Customer object |
| Product       | Product_c        | Lookup(Merchandise_c) | Links to Merchandise object |

## Steps

1. Go to *Setup → Object Manager*.
2. Create a custom object named *Orders*.
3. Add the following fields:
   - Order Number (Auto Number)
   - Order Date (Date)
   - Status (Picklist: New, Shipped, Delivered)
   - Customer (Lookup → Customer)
   - Product (Lookup → Merchandise)
4. Save all fields.

## Result

The *Orders__c* object was created successfully with all required fields and lookup relationships.
