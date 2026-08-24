# Aurora Threads Data Dictionary

| Field | Description |
|---|---|
| Date | Date of the sales transaction |
| Store | Store location associated with the transaction |
| Product | Product sold |
| Category | Product category: Clothing, Footwear, or Accessories |
| Gender | Target market classification: Male, Female, or Unisex |
| Quantity | Number of units sold in the transaction |
| Sales Amount | Sales amount used in the transaction-level revenue calculation |
| Customer ID | Unique identifier used to analyse customer purchasing behaviour |
| Discount | Discount applied to the transaction |
| Payment Type | Payment method used for the transaction |
| Revenue | Derived revenue after accounting for quantity and discount |

## Dataset Scope

- **Transaction records:** 93
- **Stores:** 3
- **Unique customers:** 31
- **Quantity sold:** 771
- **Revenue:** $288,457.50
- **Business domain:** Fashion Retail

## Revenue Calculation

Revenue was calculated as:

`Revenue = Quantity × Sales Amount × (1 − Discount)`
