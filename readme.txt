1. Title: E-Mail Marketing

Universal Plus randomly sent an e-mail marketing campaign to some of its customers.
Some customers received a campaign on women's products, some received a campaign on men's products,
and some did not receive an e-mail campaign at all.
The company collected data for all of these customers (including the ones who did not receive the campaign)
during the two weeks following the e-mail campaign.

2. Files and number of instances

   campaign_data.csv            52,000 customers, all 21 attributes listed below.
   next_campaign.csv		12,000 further customers from the same campaign. All attributes 				are provided except `visit`, which has been withheld. Universal 				Plus has shared this file to see how your system would be used 					in its next campaign.

3. Number of attributes: 21

4. Attribute information:

  1) Customer_ID: Customer identification number
  2) recency: Months since last purchase before the marketing campaign
  3) purchase_segment: Categorisation of the purchase amount in the past year before the marketing campaign
     Categories: 1) 0 - 100: the purchase amount is between £0 and £100
                 2) 100 - 200: the purchase amount is between £100 and £200
                 3) 200 - 350; 4) 350 - 500; 5) 500 - 750; 6) 750 - 1,000; 7) 1,000+
  4) purchase: Actual purchase amount (£) in the past year before the marketing campaign
  5) mens: whether the customer purchased men's merchandise in the past year before the marketing campaign (1 = purchased, 0 = not)
  6) womens: whether the customer purchased women's merchandise in the past year before the marketing campaign (1 = purchased, 0 = not)
  7) zip_area: categorisation of the customer's postcode area as Urban, Suburban or Rural
  8) new_customer: whether the customer is new in the past year or an existing customer (1 = new customer, 0 = existing customer)
  9) channel: the channels the customer purchased from in the past year.
     The categories are Phone, Web and Multichannel
 10) email_segment: e-mail campaign the customer received
     The categories are:
     Mens E-Mail: the customer received an e-mail marketing campaign for men's products
     Womens E-Mail: the customer received an e-mail marketing campaign for women's products
     No E-Mail: the customer did not receive an e-mail
 11) age: age of the customer in years
 12) dependent: whether the customer has a dependant or not (1 = yes; 0 = no)
 13) account: whether the customer has an account or not (1 = yes; 0 = no)
 14) employed: whether the customer has a permanent job (1 = yes; 0 = no)
 15) phone: whether the customer registered his/her phone number or not (1 = yes; 0 = no)
 16) delivery: delivery address type (1 = home; 2 = work; 3 = multiple)
 17) marriage: marital status (1 = married, 2 = single, 0 = other)
 18) payment_card: whether the customer registered a credit card for payment in the past year (1 = yes; 0 = no)
 19) satisfaction_score: satisfaction score (1 = very dissatisfied, 10 = very satisfied) from the annual customer
     survey conducted three months before the marketing campaign. Only customers who responded to the survey have a score.
 20) spend: total amount (£) spent in the following two weeks period
 21) visit: 1 = the customer visited the shop in the following two weeks period;
            0 = the customer did not visit the shop in the following two weeks period
