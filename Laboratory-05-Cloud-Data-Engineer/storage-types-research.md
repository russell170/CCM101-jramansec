# Types of Cloud Storage

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| **Block Storage** | Stores data in fixed-size blocks that can be attached to a virtual machine or server. | Operating systems, databases, and applications that require low-latency storage. | AWS EBS |
| **File Storage** | Stores data as files organized into folders and directories that can be shared across systems. | Shared files, documents, and applications that require a common file system. | AWS EFS |
| **Object Storage** | Stores data as objects together with metadata and a unique identifier. | Large amounts of unstructured data such as images, videos, backups, and other files. | Amazon S3 |

## Client Explain Why Object Storage?

Object storage is the best choice for storing millions of user-uploaded images because it is designed to scale virtually infinitely without the performance and management complexity of a traditional file system. Each image is stored as an independent object with its own metadata, making it simple to retrieve, replicate, and serve directly over the web via a URL. Unlike block storage, which is tied to a single server volume, object storage decouples the data from any specific machine, making it inherently more durable and accessible.