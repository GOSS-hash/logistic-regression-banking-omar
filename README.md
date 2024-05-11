# Banking Marketing Campaign - Logistic Regression Analysis
This project focuses on predicting customer engagement for a Portuguese bank's long-term deposit marketing campaigns, using data from phone calls made to customers. The analysis employs logistic regression to create a ranking algorithm, predicting the likelihood of a customer signing up for a long-term deposit, thus allowing the bank to focus its marketing efforts more efficiently.

## Dataset Overview
The dataset used is the "Bank Marketing Campaign Data" which includes the following variables:
- `age`: Age of customer (numeric)
- `job`: Type of job (categorical)
- `marital`: Marital status (categorical)
- `education`: Level of education (categorical)
- `default`: Credit in default? (categorical)
- `housing`: Has housing loan? (categorical)
- `loan`: Has personal loan? (categorical)
- `contact`: Contact communication type (categorical)
- `month`, `day_of_week`: Last contact month and day (categorical)
- `duration`: Duration of the last contact (numeric)
- `campaign`: Number of contacts during this campaign (numeric)
- `pdays`: Number of days since last contact (numeric)
- `previous`: Number of contacts before this campaign (numeric)
- `poutcome`: Outcome of the previous marketing campaign (categorical)
- Economic indicators like `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, and `nr.employed`

The dataset was preprocessed to handle categorical variables and scaled using MinMaxScaler.

## Model Training and Evaluation
### Logistic Regression Model
- A logistic regression model was initially trained with default parameters.
- The model was optimized through GridSearchCV to refine hyperparameters.

### Results Summary
- The initial logistic regression model achieved an accuracy of approximately 89.2%.
- After optimization, the improved model achieved an accuracy of approximately 89.4%.

## Usage
To replicate the analysis:
- Load the dataset.
- Perform exploratory data analysis and preprocessing.
- Train the logistic regression model.
- Evaluate the model and optimize it using hyperparameter tuning.

For more detailed steps and code execution, see the provided Jupyter notebooks.

## Contact
For inquiries or contributions, please contact [spomar36@gmail.com](mailto:spomar36@gmail.com).

## Production Services
To ensure our banking marketing model operates seamlessly in a production environment, we leverage the following cloud services and ML operations practices:

### AWS
- **Amazon S3**: Store and retrieve any amount of data at any time.
- **AWS Lambda**: Run code in response to data changes in S3 buckets.
- **Amazon SageMaker**: Train, tune, and deploy machine learning models.

### Azure
- **Azure Blob Storage**: For large-scale data storage.
- **Azure Functions**: Event-driven compute for data processing.
- **Azure Machine Address Learning Service**: Build, train, and deploy models.

### GCP
- **Google Cloud Storage**: Durable and scalable object storage.
- **Cloud Functions**: Serverless execution of functions in response to cloud events.
- **AI Platform**: End-to-end machine learning model lifecycle management.

### ML Operations
- **Continuous Training**: Implement pipelines to retrain models with new data.
- **Data Validation**: Use services like AWS Data Pipeline or Azure Data Factory for data integrity checks.
- **Model Monitoring**: Track model performance and data drift to maintain accuracy over time.

These services ensure our model stays updated, scalable, and maintainable, with robust ML operations that support continuous improvement.

## Quickstart

```bash
git clone https://github.com/GOSS-hash/logistic-regression-banking-omar
