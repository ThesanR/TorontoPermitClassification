# TorontoPermitClassification

ABSTRACT:

The uncertainty posed by process time affects many applicants that submit building permit documents to their municipalities. Subsequent decisions in the construction process such as scheduling, contracting, re-assigning tenants, payments, and more are reliant on when a permit is issued. Thus, from open data provided by the City of Toronto, this ML pipeline analyzes and predicts whether an application will take more or less time to process when compared to a particular threshold number of days. The data was cleaned, transformed, and then reshaped into 3 datasets for short, medium and long term projects. Each dataset was modeled separately and yielded moderate capabilities to predict the outcome of new permit entries using the CatBoost Classifier (Binary Classification). To produce more accurate predictions, likely more input data regarding permit stages and roadblocks within the permit process is required. 

Link to Youtube video: https://www.youtube.com/watch?v=jJ1qc2IWQjQ
