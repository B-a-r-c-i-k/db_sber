# DragonFly  
<img width="317" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/ef05b7da-e12d-41a2-bdf9-27ea542ef0c6">  
Из данного скриншота, сделанного с официального сайта (https://www.dragonflydb.io/features), видно соответствие "C" (1 узел)  

"Based on lessons learned from our experience as users of memory stores and engineers who worked for cloud companies, we knew that we need to preserve two key properties for Dragonfly: Atomicity guarantees for all operations and low, sub-millisecond latency over very high throughput." - цитата с их гитхаба дает соотвествие "А"  

# ScyllaDB  

https://www.scylladb.com/glossary/cap-theorem/  
Some NoSQL databases (for example, ScyllaDB) use  a model of tunable eventual consistency to deliver multi datacenter high availability and fast and efficient write and read operations. In this case, all nodes are equal; this means any node can serve any request, there is no single point of coordination, and all nodes in the system continue to cooperatively provide service, even when nodes become unavailable.  
+  
An AP database provides availability and partition tolerance but not consistency in the event of a failure. All nodes remain available when a partition occurs, but some might return an older version of the data. CouchDB, Cassandra, and ScyllaDB are examples of AP databases.  
Данные цитаты дают доказательство и четко написанную классификацию - AP.  

# ArenadataDB  



