# dCache Project

The goal of this project is to provide a system for storing and retrieving huge amounts of data,
distributed among a large number of heterogenous server nodes, under a single virtual filesystem
tree with a variety of standard access methods. Depending on the persistency model, dCache provides
methods for exchanging data with backend (tertiary) storage systems as well as space management,
pool attraction, dataset replication, hot spot determination and recovery from disk or node failures.
Connected to a tertiary storage system, the cache simulates unlimited direct access storage space.
Data exchanges to and from the underlying HSM are performed automatically and invisibly to the user.
