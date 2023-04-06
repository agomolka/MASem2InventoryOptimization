# Inventory Optimization in ✨Julia✨
## Simulation optimization of inventory management decisions in Julia


### Stock optimization
* COO and CFO of the chain of stores turned to you - as the main Data Scientist - with a request to optimize the current stocking system, ie system parameters (s, S).
* The CFO is primarily interested in lowering storage levels, which will reduce the cost of capital tied up in stock, which, given the rising interest rates, is a heavy financial burden for the company.
* The COO wants to at least maintain or further improve customer satisfaction by ensuring a high level of product availability on store shelves

### Complete and describe analytical tasks in the report
* Translate the logistic and financial problem into the language of the analytical optimization and simulation task, i.e.
  - Define your leverage, i.e. optimized decisions
  - Define the space of solutions, i.e. the set of admissible decisions, e.g. Granulation, minimum and maximum values
  - If you want to fine-tune the values of model parameters and decide which of them will be the subject of your sensitivity analysis. Justify that these       parameters are most vulnerable to change in the current economic situation and that examining their impact on RO will allow you to better manage the       risks
  - Clarify and propose a function/purpose that will address the needs of the COO and CFO by defining:
    * one objective function that takes into account and properly weights both COO and CFO sub-objectives
    * Two goal functions corresponding to the COO and CFO goals

 
### Sensitivity analysis and action recommendations
* Perform Sensitivity Analysis: Parameter Change vs. Optimal Solution (RO)
  - will a change in the parameter (e.g. an increase in the product price by 5% / an increase in the hourly wage) change the R.O., or will it still remain    the same?
  - if a parameter must be changed (e.g. product price/employee salary) so that R.O. has changed?
  - determine the relationship (e.g. regression) between 2 or three parameters R.O.
  - Ceteris-paribus analysis for 2-3 parameters
* Recommend one solution that you believe best addresses the CFO's and COO's goals, as well as two alternative solutions that may be considered by them in  case of different importance of individual goals or changes in environmental conditions and parameters
