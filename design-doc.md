# Title

Accelerate High Performance Computing storage with Azure HPC Cache
<!--- Alternate title: Accelerate NFS for HPC storage by using Azure HPC Cache -->

## Role(s)

- administrator
- technology manager
- solution architect
<!--- Optional: functional consultant -->

## Level

- intermediate

## Product(s)

- Azure HPC Cache

## Prerequisites

- Familiarity with NFS storage concepts such as mount, export, and namespace.
- Familiarity with networking concepts such as subnet, DNS, and TCP/UDP ports.
- Familiarity with creating virtual machines in the Azure portal.

## Summary

Create a virtual caching solution for NFS storage. Client machines will connect to the cache, read data, and process the data.

## Learning objectives

By the end of this module the learner will be able to:
1. Create an Azure HPC Cache.
1. Configure an Azure HPC Cache to accelerate a Linux-based filesystem.
1. Configure (Attach) virtual client machines to read from the cache.
1. Read and process storage data using client machines.

## Chunk your content into subtasks

> NOTE: This table is necessary. Having established your learning objectives, you need to spell out how you will reinforce those objectives.
> Once that is established, you can lay out your units for conceptual, exercise, knowledge check, etc.

| Subtask | What part of the introduction scenario does this subtask satisfy? | How will you assess it: **Exercise or Knowledge check**? | Which learning objective(s) does this help meet? | Does the subtask have enough learning content to justify an entire unit? If not, which other subtask will you combine it with? |
| ---- | ---- | ---- | ---- | ---- |
| Create an Azure HPC Cache | TODO | TODO | TODO | TODO |
| Configure an Azure HPC Cache | TODO | TODO | TODO | TODO |
| Configure virtual client machines | TODO | TODO | TODO | TODO |
| Read and process storage data | TODO | TODO | TODO | TODO |

## Outline the units

<!--- *Add more units as needed for your content*

1. **Introduction**

    Provide a scenario of a real-world job-task that shows how the technology is used in practice:

    *Add your scenario [(Scenario guidance)](https://review.docs.microsoft.com/en-us/learn-docs/docs/id-guidance-scenarios)*

1. **Learning-content unit title**

    List the content that will enable the learner to *subtask*:

    - Enabling objective
        - Information needed to accomplish the enabling objective
        - Information needed to accomplish the enabling objective
    - Enabling objective
        - Information needed to accomplish the enabling objective
        - Information needed to accomplish the enabling objective
    - Enabling objective
        - Information needed to accomplish the enabling objective
        - Information needed to accomplish the enabling objective

    **Knowledge check**

    What types of questions will test *learning objective*? *[(Knowledge check guidance)](https://review.docs.microsoft.com/en-us/learn-docs/docs/id-guidance-knowledge-check)*

    - Question type
    - Question type

1. **Exercise - exercise unit title**

    List the steps which apply the learning content from previous unit:

    1. Step
    1. Step
    1. Step

1. **Summary**

    How did you solve the problem in the initial scenario with the knowledge learned in the module? 
    
    *Add your summary [(Summary guidance)](https://review.docs.microsoft.com/en-us/learn-docs/docs/id-guidance-module-summary-unit)*

-->

1. **Introduction**

    > NOTE: Think of the introduction as the value proposition for the module; what problem is this module going to solve, what are users going to learn from this module, what technologies are we talking about, etc.

    - Create HPC Cache
    - Add a storage target to HPC Cache over Express Route
    - Create HPC clients to mount HPC Cache and request data
    - HPC Cache reads the data from the storage target and stores it
    - Client requests for the same data are served from HPC Cache

1. **Creating the cache**

    - Creating an HPC Cache
    - Adding a Storage Target
    - Building the Namespace
    - Network Access (dedicated subnet, DNS, ports)
    - Usage Model

1. **Connecting to Storage**

    - Create a Linux-based (NFS) storage server
    - Configure the NFS server (create exports)
    - Set storage Permissions (root access to exports, no root squash)

1. **Connect clients**

    - Point hundreds of clients to HPC Cache
    - Most efficient way is to leverage scripts and automation to create and configure HPC clients
    - HPC clients mount HPC Cache virtual namespace path
    - Client permissions (same vnet, not subnet; network access, NFS utilities, local path for mount)
    - Mount Instructions

1. **Exercise - Quiz**

    > NOTE: This isn't a problem since we're in the early design phase right now, but a unit can be either an exercise or a knowledge check, but not both.

1. (Optional) **Video demo**

    > NOTE: A video should be included in one of your conceptual units.

1. **Summary**

    > NOTE: The summary is necessary.

## Notes

Note any additional information that may be beneficial to this content such as links, reference material, etc.
