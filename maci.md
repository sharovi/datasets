%md

### Documentation for `M a c y s (USA) dataset`

Key highlights:
  - 47,338 product line items (All inventory as of December 2024)
  - 45+ unique categories of products, 144 secondary categories
  - Detailed product description that can be used for GenAI traning
  - Dataset generated on Dec 2024, however fresh data can be made available on demand
  - Below are the primary categories the dataset can be filtered on
    * Gift Guide
    * Home Improvement
    * Sports Fan Shop
    * Home, All Wall Décor
    * Unique Gifts by STORY
    * Luggage & Backpacks 
    * Pet Supplies
    * Health & Wellness
    * Party Supplies
    * Jewelry & Watches
    * Petites
    * Shop All Holiday
    * Rugs
    * All Outdoor & Patio
    * Women's Clothing
    * Food & Gourmet Gifts
    * Men's Clothing & Accessories
    * Electronics
    * Brands
    * Mattresses
    * Upright Luggage
    * Handbags
    * Fine China
    * Lawn & Garden
    * Arts
    * Furniture
    * Bed & Bath
    * Kids
    * Kitchen & Dining
    * Red Carpet by Macy's
    * Shoes
    * Men's Shoes
    * Shop All Baby
    * Plus Sizes
    * All Toys
    * Home Decor
    * Beauty
    * Luggage Collections
    * Juniors'
    * Bath
    * Dining & Entertaining

Dataset Schema:
- **product_title**: string - The title of the product.
- **product_page_url**: string - The URL of the product page.
- **product_description**: string - A description of the product.
- **brand**: string - The brand of the product.
- **category**: string - The original category string of the product.
- **full_price**: float - The full price of the product.
- **category1**: string - The primary category of the product.
- **category2**: string - The secondary category of the product.
- **category3**: string - The tertiary category of the product.
- **competence_date**: timestamp - The date and time when the data was collected.
- **product_code**: string - The unique code of the product extracted from the product page URL.
- **country_code**: string - The country code, set to "USA".
- **currency_code**: string - The currency code, set to "USD".
- **website_name**: string - The name of the website, set to "Macys".
- **variant**: string - The variant of the product, currently set to an empty string.
- **discounted_price**: string - The discounted price of the product, currently set to an empty string.
- **flag_discounted**: int - A flag indicating if the product is discounted, set to 0 (not discounted).

This dataset is used to store product information scraped from the Macy's website, including details about the product's pricing, categorization, and metadata.
