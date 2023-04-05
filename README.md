# dbtCloud - ELT effectively rather than ETL
https://docs.getdbt.com/
https://cloud.getdbt.com
1) Create SQL Warehouse in Databricks (Azure Portal > Databricks)
2) Import csv files, check column types
3) verify quota values are sufficient
4) try github import scenario, link account load drivers, etc
   On cloud.getdbt page click on "Develop" under the user's avatar. This should open the Cloud IDE


# Key topics
## Models
Explain what models are in a dbt project.
Build your first dbt model.
Explain how to apply modularity to analytics with dbt.
Modularize your project with the ref function.
Review a brief history of modeling paradigms.
Identify common naming conventions for tables.
Reorganize your project with subfolders.

## Sources
Explain the purpose of sources in dbt.
Configure and select from sources in your data warehouse.
View sources in the lineage graph.
Check the last time sources were updated and raise warnings if stale.

## Tests
Explain why testing is crucial for analytics.
Explain the role of testing in analytics engineering.
Configure and run generic tests in dbt.
Write, configure, and run singular tests in dbt.

## Documentation
Explain why documentation is crucial for analytics.
Understand the documentation features of dbt.
Write documentation for models, sources, and columns in .yml files.
Write documentation in markdown using doc blocks.
Generate and view documentation in development.
View and navigate the lineage graph to understand the dependencies between models.

## Deployment
Understand why it's necessary to deploy your project.
Explain the purpose of creating a deployment environment.
Schedule a job in dbt Cloud.
Review the results and artifacts of a scheduled job in dbt Cloud.
