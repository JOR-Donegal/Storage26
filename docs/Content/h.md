# Week 8
The definition for devices is often a little nebulous, but for my modules a SAN is a specialized device to do _block storage_. It will be highly reliable, with its own dedicated back end network, of redundant high speed connections.

The main technologies we use are iSCSI, which we have already seen, and Fibre Channel, which we will look at before the end of this module.

We will do these exercises using Dell Isilon technology.

Prior to working with Isilon, our last generation of SAN was from Equalogic, and I did a [training video](https://media.heanet.ie/page/b7bf742117fb440c89efeee7602a4dfb) on this in 2019.

EMC were one of the biggest brands in storage from the 1990s onwards. In 2016 they were acquired by Dell. One of the most common and popular brands in use in Ireland is Dell Isilon, in fact, the institute has used this technology for several years. 

In this exercise, you are required to investigate a suitable scale-out SAN for an ME data centre.

Your aims are to identify

- A suitable model of Isilon for an ME application.
- The storage technology used by this device (e.g., RAID, Erasure Coding, other).
- The features of this device which are of significance to the enterprise.
- The options for local encryption and security.
- Solutions which support a virtualized infrastructure.

Now download the Isilon VM and build a clustered solution (3 nodes) in VMWare Workstation.