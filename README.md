# QueueingData

The following package includes:

1. Sampling code of a G/G/1 queue.
2. The Neural network prediciton model of a G/G/1 queue.
3. G/G/1 data set.

# Sampling code of a G/G/1 queue:
This part contains a code of a G/G/1 code, where one can use our samlping algorithm for the inter-arrival and service time distributions and then compute the true steady-state probabilites of the number of customers in the system. 


The user may control the following cinfigurations:
--num_examples: number of G/G/1 batches to sample, where batch contains multiple G/G/1 queues.
--batch_size: number of examples in a G/G/1 queue. At the end, the system saves two files for each batch. One file contains the inter-arrival and service time moments and the other contain the steady-state probabilities. 
--num_moms: number of inter-arrival and service time moments are saved.
--data_path: The directory path where we wish the data will be saved.
--max_utilization: the maximum utilization of the G/G/1 queue.

# Neural network prediciton model:





