# DATA DICTIONARY
--------------------------------------------------------------------------------------------------------------------

**TABLE ()** customer excel
  - `AccountNum`:  - Phone number of the customer without the area zip code.
  - `Name`: Name of the customer
  - `Address`: Address of the customer
  - `City`: City of the customer
  - `State`: State in which the customer is located
  - `Zip`: Zip code of the customer location
  - `Routenr`: Route number of the customer location
  - `first_date`: date on which first time the garment came in for dry cleaning services
  - `last_date`: date on which last time the garment came in for dry cleaning services
  - `last_paid`: date on which the last payment was receievd
  - `last_payment`: dollar amount of the last payment received
  - `AreaCode`: Area code
  - 
  
**TABLE ()**  garmlabel excel
  - `Garmnumlong`: Barcode for each garment
  - `Phone`: Phone number of the customer without the area zip code.
  - `FirstDate`: date on which first time the garment came in for dry cleaning services
  - `LastDate`: date on which last time the garment came in for dry cleaning services
  - `Count`: Number of times the garment has come for dry cleaning services
  - `Type`: Type of garment received for dry cleaning
  - `Color1/Color2/Color3/Color4`: Various Colors for a specific garment which helps in easy identification.
  - `Upcharge1/Upcharge2/Upcharge3/Upcharge4`: Type of fibre of the garment
  - `Text4`: Brand of the garment
  - `DateRev`:Last date on which the payment was received
  - `LastPrice`: dollar amount of the last payment received


**TABLE ()** account excel
  - `Date`: Date on which the invoice by built. 
  - `Master`: Phone number of the customer without the area zip code.
  - `Phone`: Phone number of the customer without the area zip code.
  - `Master/Phone`: Phone number of the customer without the area zip code.
  - `Amount`: Amount of the the particular invoice.
  - `Payment`: Payment made against the invoice.
  - `Balance`: Carry forward balance (total amount due)
  - `Type`: Type of business. D - Dry Cleaning, A - Alterations, L - Laundry, M - Misc, O - Other
  - `Discount`: Discount amount.
  

