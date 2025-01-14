# RESEARCH TOPIC

**Building a SOC Simulation System**

## Requirements

1. **Website Development**
   - Develop a website.
   - Set up an Nginx gateway.
   - Log all incoming requests.

2. **Log Transfer Mechanism**
   - Use file synchronization mechanisms such as Rsync.
   - Utilize message queues (e.g., Kafka) to send logs to the receiving system.

3. **Log Processing System**
   - Implement ElasticSearch for log indexing and searching.
   - Use Graylog for log management and processing.

## System Deployment

This simulation system is designed and deployed using Docker containers to emulate a real-world environment, simulating the behavior of a Security Operations Center (SOC).

- Docker containers are used to build isolated environments for all components: Nginx, Kafka, ElasticSearch and Graylog.

![ alt text](/overview1.jpg)

![ alt text](/overview2.jpg)

![ alt text](/overview3.jpg)

