<!-- @format -->

### Develop, Execute, and Manage

- Pipeline based approach to organizing ML workflows
- Promotes efficiency, repeatabilitym and collaborations

### Step by step

1. Prepare data 2. Feature eng 3. Model training 4. Model evaluation 5. Model Deployment 6. Pipeline 7. Run pipeline

### Install

ZemML with Dashboards
`pip install "zenml[server]"`

SciKitLearn
`zenml integration install sklearn -y`

PyParsing
`pip install pyparsing=2.4.2`

### Initial

`zenml init`

### Dashboards

`zenml up --blocking`
