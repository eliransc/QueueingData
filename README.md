# QueueingData

The following package includes:

1. Sampling code of a G/G/1 queue.
2. The Neural network prediciton model of a G/G/1 queue.
3. G/G/1 data sets.


# Sampling code of a G/G/1 queue:
This part contains a code of a G/G/1 code, where one can use our samlping algorithm for the inter-arrival and service time distributions and then compute the true steady-state probabilites of the number of customers in the system. 


The user may control the following cinfigurations:
--num_examples: number of G/G/1 batches to sample, where batch contains multiple G/G/1 queues.
--batch_size: number of examples in a G/G/1 queue. At the end, the system saves two files for each batch. One file contains the inter-arrival and service time moments and the other contain the steady-state probabilities. 
--num_moms: number of inter-arrival and service time moments are saved.
--data_path: The directory path where we wish the data will be saved.
--max_utilization: the maximum utilization of the G/G/1 queue.

# Neural network prediciton model:
In this part, the user is required to give 5 inter-arrival and service time moments and the program's output is a 500 size vector of the steady-state probability. Whereas, the i^th location represent the number of customers n the system under steady-state. 
The program also plots a bar chart of the disitrbution (outputs only the first 30 values, but the user can change it).

# G/G/1 data:

The folder of the data can be downloaded from this link:

https://utoronto-my.sharepoint.com/:f:/g/personal/eliran_sherzer_rotman_utoronto_ca/EqnABrSRlz1MoXW6Duyr6zEBRzFWB6QZbBieLG0X3Dhetg?email=eliran.sherzer%40rotman.utoronto.ca&e=ajaRfL

The folder contains python pickle file. There are 4 files:
1. train_moms_valid_qa.pkl
2. train_ys_valid_qa.pkl
3. train_ph_moms.pkl
4. train_ph_ys.pkl

Files 1 and 2 represent a small G/G/1 data set.File 1 is the moments and file 2 is the steay-state probabilites.
Files 3 and 4 represent a large G/G/1 data set.File 3 is the moments and file 4 is the steay-state probabilites.








