# Mirror Link Implementation for Distributed Operating Systems Assignment

## Overview
This repository is part of a **Distributed Operating Systems** assignment focused on the concept of **replication and fault tolerance**.  
The repository hosts a replicated copy (mirror) of a video resource to ensure availability when the primary source fails.

## Objective
The main objective of this assignment is to:
- Demonstrate **resource replication** in a distributed environment
- Ensure **high availability** using mirror links
- Handle failures of a primary resource by redirecting users to alternative replicas

## Concept Used (DOS Perspective)
This work demonstrates the following Distributed Operating System concepts:
- **Replication**: Multiple copies of the same resource are maintained at different locations
- **Fault Tolerance**: If the primary video source fails, the system provides mirror links
- **High Availability**: Users can still access the resource even during failures
- **Failover Mechanism**: Manual redirection to a replicated resource

## How the Mirror Link Works
- The primary video is hosted locally in the application
- A replica (mirror) of the same video is stored in this GitHub repository
- When the primary video fails, users are provided with mirror links
- The mirror link uses a **raw GitHub URL** to directly access the replicated resource

## Why GitHub is Used
GitHub is used as a mirror storage platform because:
- It provides reliable public access
- Supports distributed access
- Ensures long-term availability
- Allows version control of replicated resources

## Educational Significance
This assignment simulates a **distributed resource management scenario**, where:
- Resources are distributed across multiple nodes
- Failure of one node does not stop access to the resource
- Replication improves reliability and user experience

## Usage
1. Open the video file in this repository
2. Click the **Raw** button to obtain the direct access link
3. Use this link as a mirror resource in the application

## Course
Distributed Operating Systems

## Author
**Katari Tejaswi**
