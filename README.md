# PageCacheSync
This project was made as a team effort by Saurabh Singh,David Abjornsson and Hitesh Laware for the course Advanced Data Structures at Boston University.

##Project Objective
To develop a Product that is able to sync image search queries received at the two data centers of Google image search. 
The two Data Centers communicate over the internet and identify each other with their IP addresses. 
Most of the image search queries are common and as a result of this Google keeps the result of these queries cached in the datacenters. 
The aim of this project is to figure out the identical image search queries received at both the datacenters and sync it 
with rest of the queries. This is done so that with minimum data transfer amongst the datacenters, we can have results of 
all the queries unique and non-unique cached in both the data centers. We then expand the database by adding a third data center 
and apply the same implementation to handle data traffic from all three data centers synced with each other.  