# Data Descriptor: Waiting Time in Transaction Fee Mechanism

## Summary
Waiting time (Section 5.3): Folder blockdata/ contains waiting time data in blockdata.npy and waitingtime_csv.csv.

## Reproducing data & graphs
### Raw mempool data
Raw mempool data used to calculate waiting time can be downloaded here (about 20GB). After downloading it you should create a folder named **compressed/** to store the uncompressed raw data.

You can see several .txt files, containing the timestamp of transactions received by a particular full node. For example, the file LA_[2021070100,2021071600)_compressed.txt contains timestamp collected by our full node in LA between July 1, 2021 and July 16, 2021. Each line of these files describes a transaction. E.g., the following line means that transaction 0x16... is received at Unix timestamp 1626418821.870.
