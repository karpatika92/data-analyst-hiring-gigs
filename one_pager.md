# Executive Summary
## Business Case
The Connectivity team wants to better understand usage patterns to optimize plan offerings and identify growth opportunities: 
- How much data does a subscription typically consume?
- How does usage look like at different plan data allowances?
- Do subscriptions typically consume consistent amounts of data throughout their lifetime? 

On top of that, the Head of Product approached you:
- Compare the retention pattern for the most recently launched project versus the two older ones.

List follow-up questions for stakeholders and state your assumptions. Note where you'd dive deeper with more time.

## How much data does a subscription typically consume?
* longer subscriptions consume more than shorter ones
* data allowance is a great segmentation here
### Answer
* a typical subscription consumes ~150-300 MB per month and ~ 1GB during their lifetime, depending on the data allowance of the plan.
  * there are huge whales: subscriptions that consume 10x more than this
  * wearables consume much less than phones
  * API Projects have higher data consumption than Connect projects
## How does usage look like at different plan data allowances?
* higher data allowance plans lead to higher data consumption
* there is always a bump in the distribution around the data allowance limit
* there are always a lot of subs who consume 0 data despoite having allowance
* fat tailed distribution: a small number of subs consume a lot of data
* exact figures in the notebook
## Do subscriptions typically consume consistent amounts of data throughout their lifetime?
* It grows over time, peaks around 3-5 months after the start of the subscription and then flat
* this is impacted by survivor bias overall
* if we factor out survivor bias, a typical user who makes it to the 5th month will consume over 80% more data than in the first month acrodd data allowance segments

## Compare the retention pattern for the most recently launched project versus the two older ones
* Based on usage data the most recently launched project is People Mobile
* retention is worse on the new project compared to the older ones
* ACME Phone has the best retention
* even though data usage is higher
* 