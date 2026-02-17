# Week 3
When we try to classify storage, it gets complicated! We can break up a storage medium like a disc into multiple volumes. Or we can aggregate multiple discs together to create a single volume.

In this week's notes, I want to introduce some of these concepts and some terminology.

If this area is completely new to you, you're about to experience many new concepts. From the administrator trying to do systems recovery, these ideas are fundamental. When we teach forensics, trying to find hidden data for example, these ideas are fundamental. To understand storage, we must get a little way into this world. The best book for practitioners that I have come across is _File System Forensic Analysis_ by Brian Carrier (ISBN: 978-0321268174). It is intended for security and forensics practitioners, but it’s the best reference I can suggest.

## Theory
First we need to understand storage at the highest level. We define block, file, object and stream storage, read through my notes on [Storage Organization](https://jor-donegal.github.io/StorageOrganization26/a/).

Once we have a storage volume, we need to break that up into usable partitions. Read through the notes on [Volume Organization](https://jor-donegal.github.io/VolumeOrganisation26/)

## Practice
You will find [this week's exercises](https://jor-donegal.github.io/PartitionTables26/) tough! We are going to map an MBR partition in exactly the way we would for data recovery. And then worse, we will do the same with a GPT partition. As always, save anything you need to create a report should you be required.

