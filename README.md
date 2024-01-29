# Advance-Demand-Prediction

## Dataset Description

XYZ Sportswear (company name disguised due to NDA) is a world-renowned company that sells high-quality parkas to 45 countries (the real company name was disguised). Most sales occur in the western European and Russian markets. However, XYZ is not actively present in these locations, so the company sells the products to vendors. Some of the vendors are directly linked to big sporting goods retailers (e.g., Decathlon). The vendors place the orders well in advance of their requested delivery date. For each order, they may select more than one item in different quantities. If a vendor places an order for 3 different parkas in some quantities, for example, the order will appear in three different rows in the dataset such that each line corresponds to an order code/product code pair. The orders are stored in a dataset which includes 11 variables. Each variable corresponds to one column. There are 2421 rows in the dataset, covering time between 2009 and 2011.

To improve the accuracy of demand forecasts, the demand planners determined two issues that need to be addressed by an external project team. First, the company needs a choice model to understand if the choice probabilities are affected by seasonality. Second, a model to estimate demand depending on the advance orders is needed.

## Definition of Variables

| Column Name              | Description                                                     |
|--------------------------|-----------------------------------------------------------------|
| Order Date               | The date when an order is received. (Format: DD.MM.YYYY)        |
| Requested Delivery Date  | The delivery date requested by the vendor. (Format: DD.MM.YYYY) |
| Customer Country Code    | The country code of the vendor.                                 |
| Product Code             | The company code of the product ordered by the vendor.          |
| Description              | A short description of the product.                              |
| Order type               | All orders are received from vendors. The order type is "VO," standing for Vendor Order. |
| Customer Order Code      | A reference code given to each order. As explained above, the same order code may appear in multiple rows if the vendor places more than one items in different quantities at the same time. |
| Value                    | The price that is charged to the vendor.                        |
| Currency                 | The currency of the price.                                      |
| Items                    | The quantity requested by the vendor for the selected product.  |
| Route                    | The vendors may request items to be delivered to different regions. For each region, there is a specific route code. Within the borders of a country, there may be multiple routes. |

