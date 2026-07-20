# Merchandise__c Object Fields

| Field Label        | API Name             | Data Type | Values/Details |
|--------------------|----------------------|-----------|----------------|
| Product Name       | Product_Name__c      | Text      | - |
| Product Code       | Product_Code__c      | Text      | - |
| Category           | Category__c          | Picklist  | Electronics, Furniture, Clothing (or values specified in your project) |
| Warranty (Months)  | Warranty_Months__c   | Number    | 0–60 |
| Active             | Active__c            | Checkbox  | Default: True |

## Steps

1. Go to *Setup* → *Object Manager*.
2. Create a custom object named *Merchandise*.
3. Add the following fields:
   - Product Name (Text)
   - Product Code (Text)
   - Category (Picklist)
   - Warranty (Months) (Number)
   - Active (Checkbox)
4. Save all fields.

## Result

The *Merchandise__c* object was created successfully with all required custom fields.
