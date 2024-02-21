# DragonFly  
<img width="317" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/ef05b7da-e12d-41a2-bdf9-27ea542ef0c6">  

Из данного скриншота, сделанного с официального сайта (https://www.dragonflydb.io/features), видно соответствие "C" (1 узел)  

<img width="291" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/d801a106-567f-473f-a337-1c5f147049cf">  

<img width="531" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/ac98f49f-478f-4622-b41c-50455dbb84f6">  

Два скриншота выше (аналогично сделанные с официального сайта) дают подтверждение "A".

Итого: CA


# ScyllaDB  

https://www.scylladb.com/glossary/cap-theorem/  
Some NoSQL databases (for example, ScyllaDB) use  a model of tunable eventual consistency to deliver multi datacenter high availability and fast and efficient write and read operations. In this case, all nodes are equal; this means any node can serve any request, there is no single point of coordination, and all nodes in the system continue to cooperatively provide service, even when nodes become unavailable.  
+  
An AP database provides availability and partition tolerance but not consistency in the event of a failure. All nodes remain available when a partition occurs, but some might return an older version of the data. CouchDB, Cassandra, and ScyllaDB are examples of AP databases.  
Данные цитаты дают доказательство и четко написанную классификацию - AP.  

# ArenadataDB  
https://arenadata.tech/products/arenadata-db/?ysclid=lsugetck3v855771327  
<img width="289" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/ebe38e7e-f57f-4cab-bf7f-5f36f7ef552b">  
Дает согласованность данных  
<img width="712" alt="image" src="https://github.com/B-a-r-c-i-k/db_sber/assets/43545491/d1b19a84-965f-4768-a7d1-a25f4e951165">  
Дает устойчивость к разделению  
Итого: СP







