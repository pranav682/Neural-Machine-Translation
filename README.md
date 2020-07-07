# Neural-Machine-Translation
Translating human readable dates to machine readable dates


The model we will build here could be used to translate from one language to another, such as translating from English to Hindi.
However, language translation requires massive datasets and usually takes days of training on GPUs.
To give you a place to experiment with these models without using massive datasets, we will perform a simpler "date translation" task.
The network will input a date written in a variety of possible formats (e.g. "the 29th of August 1958", "03/30/1968", "24 JUNE 1987")
The network will translate them into standardized, machine readable dates (e.g. "1958-08-29", "1968-03-30", "1987-06-24").
We will have the network learn to output dates in the common machine-readable format YYYY-MM-DD.
1.1 - Dataset
We will train the model on a dataset of 10,000 human readable dates and their equivalent, standardized, machine readable dates. 
