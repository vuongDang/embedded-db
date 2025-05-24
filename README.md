# embedded-db


Bootcamp project to build a high-performance DB for embedded devices. 

## Project Requirements

### Database structure
Define a Database struct: Create a struct to handle key-value store operations.
Implement CRUD operations: Develop methods for creating, reading, updating, and deleting key-value pairs.

### Indexing
Define an indexing struct: Create a struct to represent the index.
Implement an indexing algorithm: Add a B-tree or hash index to speed up data insertion and retrieval.

### Storage format optimization
Text-based storage: Start with a simple text-based storage format such as JSON for records.
Binary-based storage: Optimize by implementing a binary storage format.
Input file parameter: Accept an input file parameter for initializing the database with pre-existing data in various formats (JSON or binary).

### Memory and performance optimization
Memory optimization: Use specialized embedded-systems-friendly data structures to minimize memory usage.
Query speed optimization: Optimize query execution by caching frequently accessed records.

### Simulating embedded constraints
Memory limitation: Programmatically limit memory usage within your Rust application.
CPU throttling: Simulate limited processing power by introducing artificial delays.
Slow disk I/O: Add delays to read and write operations to simulate slow disk access.

## Optional Enhancements

### Concurrency and parallelism
Implement concurrency mechanisms to allow multiple threads to perform database operations simultaneously.
Ensure thread safety and data integrity while handling concurrent operations.

### Compression
Integrate data compression techniques to reduce the storage footprint of the database.
Experiment with different compression algorithms (e.g., gzip, LZ4) and evaluate their impact on performance.

(Note that these enhancements are optional and should only be attempted after the core database functionality is working.)

