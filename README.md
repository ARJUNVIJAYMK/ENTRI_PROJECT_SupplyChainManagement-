### ***ENTRI_PROJECT_SupplyChainManagement***
ENTRI app project
Supply Chain Management

**OVERVIEW**

A Fast Moving Consumer Goods (FMCG) company entered into the instant noodles business two
years back. Their higher management has noticed that there is a mismatch in the demand and
supply. Where the demand is high, supply is pretty low and vice-versa which results in a loss in
inventory cost and ultimately loss to the company. Hence, the higher management wants to
optimize the supply quantity in each and every warehouse in the entire country.
Create a model using : Train dataset

**GOALS**

The objective of this exercise is to build a model, using historical data that will determine an
optimum weight of the product to be shipped each time from the respective warehouse.
1. Focus on all steps of data science (EDA, data processing, model, evaluation, charts)
2. Highlight any trend in data, deep insight, novel steps that you take
3. Highlight next steps and improvements.
4. Apply 5 to 6 machine learning algorithms and evaluate it using Test dataset .


#### Variables:

1.**Ware_house_ID**: Unique Warehouse ID where the product is prepared for dispatch. (dtype: Object)

2.**WH_Manager_ID**: Manager ID present in the warehouse. (dtype: Object)

3.**zone**: Zone of the warehouse. (dtype: String)

4.**WH_regional_zone**: Regional zone of the warehouse. (dtype: Object)

5.**wh_owner_type**: The ownership type of the warehouse (owned by the company or on rent). (dtype: String)

6.**approved_wh_govt_certificate**: Type of approval issued by the government to the warehouse. (dtype: Object)

7.**num_refill_req_l3m**: Refilling requests received by the warehouse in the last 3 months. (dtype: Integer)

8.**transport_issue_l1y**: Number of transport issues for the warehouse in the last 1 year. (dtype: Integer)

9.**Competitor_in_mkt**: Number of competitors in the market. (dtype: Integer)

10.**retail_shop_num**: Number of retail shops selling noodles produced by the warehouse. (dtype: Integer)

11.**distributor_num**: Number of distributors working between the warehouse and retail shops. (dtype: Integer)

12.**flood_impacted**: Whether the warehouse is in a flood-impacted area or not. (dtype: Integer)

13.**flood_proof**: Warehouse having a flood-proof indicator. (dtype: Integer)

14.**electric_supply**: Whether the warehouse has proper electric supply along with power backup. (dtype: Integer)

15.**dist_from_hub**: Distance from the warehouse to the production hub. (dtype: Integer)

16.**workers_num**: Number of workers in the warehouse. (dtype: Integer)

17.**wh_est_year**: Warehouse establishment year. (dtype: Integer)

18.**storage_issue_reported_l3m**: Storage issues reported by the warehouse in the last 3 months. (dtype: Integer)

19.**temp_reg_mach**: Warehouse having a temperature-regulating machine indicator or not. (dtype: Integer)

20.**wh_breakdown_l3m**: Number of times the warehouse faces breakdown in the last 3 months. (dtype: Integer)

21.**product_wg_ton**: Product weight. (dtype: Integer)
