## About Myself

I'm Liu Junfeng, currently working in [PingCAP](https://github.com/pingcap) as an infra engineer. Recently interested in:
1. Streaming system
2. Database system
3. Cloud native system
4. Robust and comprehensible system design

### My Work
Working in PingCAP, I'm mostly focusing on building data migration system, capable of both full migration and incremental migration (or, so-called Change Data Capture system). In terms of the full migration, the project I'm in is [Lightning](https://github.com/pingcap/tidb), which can import data from files to [TiDB](https://github.com/pingcap/tidb). The most distinctive merit of using Lightning is that it is able to decode and encode data as key-value pairs and directly ingest them to [TiKV](https://github.com/tikv/tikv), the KV storage engine of TiDB, which is exponentially faster than simply executing SQL via TiDB. 

Another project I'm participating is [TiFlow](https://github.com/pingcap/tiflow). It's a high-performance data migration platform being able to capture change-data from  MySQL-like database, such as MySQL, MariaDB, Aurora, TiDB, etc, to other data storage system, including TiDB, Kafka, and etc. I'm responsible to build the migration system from MySQL to TiDB (often known as [DM](https://docs.pingcap.com/tidb/stable/dm-overview)). In addition to migration, we have built a lot of interesting and helpful features.

The two systems are open-source. Please feel free to reach out to us by filing issues or contacting me by e-mail if you have any questions or precious suggestions.

Besides, I'm recently taking part in developing the [TiDB Cloud](https://tidbcloud.com) and supporting import service on it. But I don't have much knowledge about cloud computing and still work hard to comprehend it.

I'm currently pursuing a PhD opportunity researching software system, database system, or data processing system. Please contact me if you are interested in my work.

### Contact
liujunf9@gmail.com
