# Laboratory 05 – The Cloud Data Engineer

## Mission Overview
This laboratory activity focused on cloud storage, specifically Object Storage.
As part of the Cloud Data Engineering Team at CloudNova Technologies, the task
was to help a client build a proof-of-concept storage solution for a photo-sharing
application. Since containers are ephemeral, images could not be stored inside the
web server itself — instead, an S3-compatible object storage server (MinIO) was
deployed using Docker to provide a scalable, persistent storage solution.

## Objectives

- Differentiate between Block, File, and Object Storage, and identify which
  cloud provider services correspond to each type.
- Deploy an S3-compatible Object Storage server (MinIO) using Docker, including
  configuring environment variables for authentication.
- Understand how port mapping exposes multiple services (API and Web Console)
  from a single containerized application.
- Access a cloud service running inside a container via a web interface using
  port forwarding, simulating how administrators manage cloud infrastructure
  remotely.
- Create a storage bucket and upload objects (files) to the cloud, replicating
  the core workflow of a real object storage system like Amazon S3.
- Troubleshoot real-world deployment issues, such as adapting to a changed
  container registry source.
- Document cloud storage operations using Markdown, producing documentation
  detailed enough for another engineer to replicate the deployment.
- Continue expanding a professional GitHub Cloud Computing Portfolio that
  demonstrates both theoretical understanding and hands-on technical execution.

## Tools Used
- KillerCoda Playground (Ubuntu/Docker environment)
- Docker (containerized deployment)
- MinIO (S3-compatible object storage server)
- Web browser (MinIO Web Console access via port forwarding)
- Markdown (documentation)
- Git & GitHub (version control and portfolio hosting)

## Skills Learned
I learned how to differentiate Block, File, and Object Storage and understand their different uses. I learned how to deploy MinIO using Docker, configure environment variables, map ports, and access the MinIO web console. I also learned how to create a bucket and upload objects, while improving my Linux, Docker, Markdown, and GitHub skills.
