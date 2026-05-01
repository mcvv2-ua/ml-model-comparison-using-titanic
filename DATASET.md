# Dataset Note

This project uses the classic Titanic dataset, a public dataset commonly used for machine learning classification exercises.

The file `data/titanic.csv` includes historical passenger information such as names, ticket numbers and cabin identifiers. These fields are part of the public source dataset and are not personal data from the author of this repository.

In the notebook, the columns `PassengerId`, `Name`, `Ticket` and `Cabin` are removed before training because they have high cardinality and can introduce noise or overfitting.

If you prefer to publish a more minimal repository, you can replace `data/titanic.csv` with instructions for downloading the dataset from its original source.
