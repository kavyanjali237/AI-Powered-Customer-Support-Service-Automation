# User_Cases__c Object Fields

| Field Label | API Name | Data Type | Values/Reference |
|--------------|----------------------|---------------------------|----------------------------------|
| Product | Product_c | Lookup(Merchandise_c) | Lookup to Merchandise object |
| Order | Order_c | Lookup(Orders_c) | Lookup to Orders object |
| Priority | Priority__c | Picklist | Low, Medium, High |
| Issue Category | Issue_Category__c | Picklist | Delivery, Damage, Warranty |
| AI Summary | AI_Summary__c | Long Text Area | AI-generated case summary |

## Steps to Create

1. Go to *Setup → Object Manager*.
2. Create a custom object named *User Cases*.
3. Add the following fields:
   - Product (Lookup → Merchandise)
   - Order (Lookup → Orders)
   - Priority (Picklist: Low, Medium, High)
   - Issue Category (Picklist: Delivery, Damage, Warranty)
   - AI Summary (Long Text Area)
4. Save all the fields.

## Expected Result

The *User_Cases__c* object is created successfully with all required fields and lookup relationships.
