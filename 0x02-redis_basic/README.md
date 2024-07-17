Redis is an in-memory data structure that is used for faster access to data. It is used to store data that needs to be accessed frequently and fast. It is not used for storing large amounts of data. If you want to store and retrieve large amounts of data you need to use a traditional database such as MongoDB or MYSQL. Redis provides a variety of data structures such as sets, strings, hashes, and lists.

The Redis server is a program that runs and stores data in memory.
You can just connect to that server and can use it to store and retrieve data faster.
For that reason, Redis is not used for persistent storing of data as complete data will be lost if the system crashes.
Redis is scalable as you can run multiple instances of the server.
It is often used as a cache that stores data temporarily and provides faster access to frequently used data.