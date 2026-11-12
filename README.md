A collection of projects, learning notes, and experiments from a data enthusiast and practitioner.

| Category | Projects & Resources |
|---|---|
| **How I Use AI for Data Work** | [Auditing My Python Pipeline](https://github.com/linyuli303/DataEngineeringAuditLog/tree/main) · [Column Lineage Explorer](https://github.com/linyuli303/ColumnLineageExplorer) |
| **How I Use AI in Everyday Life** | [MyApps — All your favourites, one place](https://github.com/linyuli303/Apps) |
| **Databricks Projects** | [NYC Taxi Data](https://github.com/linyuli303/DatabricksDemoWithNYCTaxiData/tree/main) · [dbt on Databricks](https://github.com/linyuli303/dbt_core_databricks_demo) |
| **Continuous Learning** | [Certificates of Completion — Udemy & Coursera](https://linyuli303.github.io/certifications/) |
| **Learning Notes** | [Machine Learning · Deep Learning](https://linyuli303.github.io/MachineLearningDeepLearningAI/yuli_learning_notes_cherry_blossom_theme.html) |
| **Learning in Progress** | [Agentic AI & MCP](https://udemy.com/course/langchain/) · [Snowflake](https://udemy.com/course/ultimate-snowpro-core-certification-course-exam/) |
| **Tableau Public** | [Tableau Visualizations](https://public.tableau.com/app/profile/yuli.lin/vizzes#!/) |
| **Interactive Resume** | [Download My Power BI Resume (.pbix)](https://raw.githubusercontent.com/linyuli303/MachineLearningDeepLearningAI/main/WhoIsYuli/Yuli.pbix) |

**Preview**

<img width="450" height="240" alt="image" src="https://github.com/user-attachments/assets/ed998a9b-4cbe-4e38-90ab-21d59ff21e50" />

## Code Templates

Learning notebooks and reusable examples for data preparation, machine learning, deep learning, NLP, and practical data utilities.

### Data Preparation & Dimensionality Reduction

| Topic | Notebook | Notes & References |
|---|---|---|
| Data Preprocessing | [Data Preprocessing Tools](./CodeTemplate/data_preprocessing_tools.ipynb) | Data preparation examples |
| Principal Component Analysis | [PCA](./CodeTemplate/DimensionalityReduction/principal_component_analysis.ipynb) | [Interactive explanation](https://setosa.io/ev/principal-component-analysis/) |
| Linear Discriminant Analysis | [LDA](./CodeTemplate/DimensionalityReduction/linear_discriminant_analysis.ipynb) | Dimensionality reduction |
| Kernel PCA | [Kernel PCA](./CodeTemplate/DimensionalityReduction/kernel_pca.ipynb) | Nonlinear dimensionality reduction |

### Machine Learning

#### Regression

| Method | Notebook |
|---|---|
| Multiple Linear Regression | [Notebook](./CodeTemplate/Regression/multiple_linear_regression.ipynb) |
| Polynomial Regression | [Notebook](./CodeTemplate/Regression/polynomial_regression.ipynb) |
| Support Vector Regression | [Notebook](./CodeTemplate/Regression/support_vector_regression.ipynb) |
| Decision Tree Regression | [Notebook](./CodeTemplate/Regression/decision_tree_regression.ipynb) |
| Random Forest Regression | [Notebook](./CodeTemplate/Regression/random_forest_regression.ipynb) |

#### Classification

| Method | Notebook | Examples / Focus |
|---|---|---|
| Logistic Regression | [Notebook](./CodeTemplate/Classification/logistic_regression.ipynb) | |
| Logistic Regression with Spark | [Notebook](./CodeTemplate/Classification/logistic_regression_with_spark.ipynb) | Titanic survival · Customer churn |
| K-Nearest Neighbors | [Notebook](./CodeTemplate/Classification/k_nearest_neighbors.ipynb) | |
| Support Vector Machine | [Notebook](./CodeTemplate/Classification/support_vector_machine.ipynb) | |
| Kernel SVM | [Notebook](./CodeTemplate/Classification/kernel_svm.ipynb) | |
| Naive Bayes | [Notebook](./CodeTemplate/Classification/naive_bayes.ipynb) | |
| Decision Tree Classification | [Notebook](./CodeTemplate/Classification/decision_tree_classification.ipynb) | |
| Random Forest Classification | [Notebook](./CodeTemplate/Classification/random_forest_classification.ipynb) | |
| Random Forest with Spark | [Notebook](./CodeTemplate/Classification/random_forest_featureimportance_spark.ipynb) | Feature importance |

#### Clustering & Association Rules

| Topic | Notebook | Examples / References |
|---|---|---|
| K-Means Clustering | [Notebook](./CodeTemplate/Clustering/k_means_clustering.ipynb) | Customer segmentation |
| Hierarchical Clustering | [Notebook](./CodeTemplate/Clustering/hierarchical_clustering.ipynb) | |
| Apriori | [Notebook](./CodeTemplate/AssociationRuleLearning/apriori.ipynb) | Association rules · [Course slides, pp. 332–350](https://online.fliphtml5.com/grdgl/hfrm/#p=332) |
| Eclat | [Notebook](./CodeTemplate/AssociationRuleLearning/eclat.ipynb) | Association rules |

#### Model Evaluation, Selection & Boosting

| Topic | Notebook | Notes & References |
|---|---|---|
| k-Fold Cross-Validation | [Notebook](./CodeTemplate/ModelSelection/k_fold_cross_validation.ipynb) | Model evaluation |
| Grid Search | [Notebook](./CodeTemplate/ModelSelection/grid_search.ipynb) | Hyperparameter tuning with cross-validation · [Documentation](https://scikit-learn.org/stable/modules/grid_search.html#grid-search) |
| XGBoost | [Notebook](./CodeTemplate/xg_boost.ipynb) | Gradient boosting |

### Natural Language Processing & Deep Learning

#### Natural Language Processing

| Approach | Notebook | Examples / Focus |
|---|---|---|
| NLP with NLTK | [Notebook](./CodeTemplate/NLP/natural_language_processing.ipynb) | Sentiment analysis |
| NLP with Spark | [Notebook](./CodeTemplate/NLP/nlp_with_spark.ipynb) | Spam detection |
| Sentence Transformers | [Notebook](./CodeTemplate/NLP/nlp_with_sentence_transformers.ipynb) | Clustering · Semantic search |

#### Deep Learning

| Architecture | Notebook | Examples / Focus |
|---|---|---|
| Artificial Neural Networks (ANN) | [Notebook](./CodeTemplate/DeepLearning/artificial_neural_network.ipynb) | Regression · Classification · Customer churn |
| Convolutional Neural Networks (CNN) | [Notebook](./CodeTemplate/DeepLearning/convolutional_neural_network.ipynb) | Computer vision |
| Recurrent Neural Networks (RNN) | [Notebook](./CodeTemplate/DeepLearning/rnn.ipynb) | Time series analysis |

### Data Engineering, Python Utilities & Query Languages

| Area | Template / Reference | Focus |
|---|---|---|
| Distributed Data Processing | [PySpark](./CodeTemplate/OtherUtils/pyspark.ipynb) | Spark with Python |
| Data Architecture | [Lakehouse Medallion Architecture](./CodeTemplate/OtherUtils/medallion_architecture_implementation.ipynb) | Implementation example |
| Test Data | [Faker](./CodeTemplate/OtherUtils/faker_eandom_data_generation.ipynb) | Random data generation |
| PDF Processing | [PyPDF](./CodeTemplate/OtherUtils/PyPDF.ipynb) | Working with PDF files |
| Notebook Utilities | [nbformat](./CodeTemplate/OtherUtils/merge_notebooks.ipynb) | Merging notebooks |
| SQL | [MySQL Syntax Reference](./CodeTemplate/OtherUtils/MySQL.pdf) | PDF reference |
| DAX | [DAX Functions Reference](./CodeTemplate/OtherUtils/DAXFunctions.pdf) | PDF reference |

## Resources & References

### Data Engineering & Platforms

| Resource | Link |
|---|---|
| Spark SQL / PySpark | [API Reference](https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/index.html) |
| Databricks | [Free Edition](https://signup.databricks.com/?dbx_source=docs) |
| Amazon SageMaker AI | [Platform](https://aws.amazon.com/sagemaker/ai) |
| dbt | [Reference Documentation](https://docs.getdbt.com/reference/references-overview?version=2) · [Package Hub](https://hub.getdbt.com/) |
| Microsoft Fabric | [Data Warehousing SQL Wiki](https://github.com/malvik01/Fabric-Data-Warehousing-SQL-Code/wiki) |

### Machine Learning & Deep Learning

| Resource | Link |
|---|---|
| scikit-learn | [User Guide](https://scikit-learn.org/stable/user_guide.html) |
| TensorFlow | [Python API Reference](https://www.tensorflow.org/api_docs/python/tf) · [Playground](https://playground.tensorflow.org/) |
| Apache Spark ML | [Classification & Regression](https://spark.apache.org/docs/latest/ml-classification-regression.html) |
| Keras | [Code Examples](https://keras.io/examples/) |

### Generative AI, Transformers & LLMs

| Resource | Link |
|---|---|
| Hugging Face | [Platform](https://huggingface.co/) |
| LangChain | [Framework](https://www.langchain.com/) · [LangSmith Prompt Hub](https://smith.langchain.com/hub/) |
| Transformer Explainer | [Interactive Explanation](https://poloclub.github.io/transformer-explainer/) |
| Prompt Engineering Guide | [Guide](https://www.promptingguide.ai/) |

### Python Automation & Open Datasets

| Category | Resource |
|---|---|
| Python Automation | [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/) |
| Open Datasets | [UCI Machine Learning Repository](https://archive.ics.uci.edu/) · [Kaggle](https://www.kaggle.com/) |

### Visualization, Color & Apps

| Category | Resources |
|---|---|
| Color Palettes | [Adobe Color — Extract from an Image](https://color.adobe.com/create/image) · [Japanese Color Atlas](https://japanesecoloratlas.com/en/palettes) · [Nippon Colors](https://nipponcolors.com/) |
| Data Visualization | [D3 Visualization Gallery](https://observablehq.com/@d3/gallery) |
| Data Apps | [Streamlit](https://streamlit.io/) |

### Books

| Book | Author(s) |
|---|---|
| [An Introduction to Statistical Learning](https://www.statlearning.com/) | Gareth James and co-authors |
| [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) | Aurélien Géron |
