# Used Car Prices

A final project for DTSA-5509, Supervised Learning. The goal for this project is to use a dataset of used car listings gathered to predict the price of a vehicle before listing it for sale.

For this dataset, I am going to explore using simple linear regression and multi-linear regression for price prediction. I suspect the multi-linear regression will give the best results due to how dependant year, make, and model are when considering the price of a vehicle along with other features like the odometer reading.

## About the dataset

Data from: https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data

Data was excluded from this git repo due to even the compressed version of the dataset exceeding the size limits of github. It's 250MB zipped and 1.45GB uncompressed.

The notebook is expecting the downloaded dataset to be unzipped to a `data` subdirectory (`./data/vehicles.csv`).

The `read_csv` function could also be updated instead to point to the downloaded, unzipped dataset.
