# Stickers-Trends-Stocks
I identify which item–store combinations present elevated operational risk due to forecast bias and error, using visual diagnostics rather than model tuning or inventory optimization.

# Business Questions
- Where are forecasts systematically biased across items and stores?
- Does conservative forecast bias translate into meaningful inventory or service trade offs?
# Key Findings
-	Forecast demonstrated consistently positive bias across all store-item store combinations indicating systematic conservative tendency 
-	Conservative bias enabled higher service levels but also significantly higher average inventory
-	Inventory penalties vary per item with Item 2 consistently carrying more inventory than item 1.
  
# Finished Product
Read my full Kaggle Notebook [here](https://www.kaggle.com/code/marissan/stickers-trends-and-stockouts-forecast-bias)!
<br>

**Deliverables**
-	An understanding of forecast downstream impacts 
-	Store/item combinations that experience the highest biases
# Programs
-	Python
-	Copilot
    -	Used as learning aids w/ code debug, proper process structure, and exploration
# Data Source
In this case, I chose the Store Item Demand Challenge dataset from 8 years ago as it's supposed to be friendly for beginners and is already clean!

# Assumptions & Scope Boundaries
-	**Service Level Target** was selected at about 90%. This is different from our prior projects and was selected to more accurately reflect a retail environment in contrast to our high penalty flooring company prior.
-	Analysis focuses on bias patterns and operational impact, **not** model selection or parameter tuning.
-	Results are interpreted comparatively rather than as absolute performance benchmarks.

# Opportunities
Given that forecast behavior and downstream inventory outcomes differ meaningfully across items, one opportunity would be to evaluate whether a uniform planning approach is appropriate for all SKUs. In particular, items that consistently carry higher average inventory may benefit from differentiated service targets or stocking strategies designed to better balance inventory efficiency and availability.
Additionally, expanding the analysis to examine forecast performance around specific holidays or seasonal events could help identify periods where conservative bias is most costly. Understanding which demand spikes are predictable versus trend driven may allow planners to reduce excess conservatism during slower periods while remaining responsive ahead of known seasonal surges.

# Reflection
This project was easier than prior, which is ironic because we are forecasting more items now! I think because beyond the model summary report card and heat map, most of the analysis was centered around 1 store and 1 item. I enjoyed repurposing the bones of the prior work to execute this project a bit faster too! It demonstrates that this training is paying off for permanent comprehension. Exploring this SARIMA model has been very interesting since most of the work has come from a high service level perspective. Taking a step back and seeing the model’s impact on items and stores specifically reveals more areas to make the model more responsive or be satisfied with its performance. 
