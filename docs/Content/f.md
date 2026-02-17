# Week 6
Underlying theory is great! But without the ability to do calculations, it's not engineering. This week in theory I want to dig into the physical properties of discs and get to the point where you can do meaningful calculations on our key performance values.

- Capacity
- Performance
- Availability

## Theory
Read through and understand my notes on [Storage Reliability](https://johnoraw.gitbook.io/storage-theory/storage-reliability)  

Even though I used some equations in this exercise, the math was very simple. If I were doing this in a professional environment, I would need more rigour to my testing. I would perform many tests and ensure consistent results, quantifying the differences from test to test.
Whenever we have plots of X/Y, we will typically use linear regression to characterize our results. We end up with a line in the form Y=MX+C which you may remember from second level geometry. And we calculate all the values we normally associate with regression theory. 

What we have done here is a good estimate only.

## Practice
In the theory notes this week, we examined Single Disk Performance. Using the same methodology, carry out these measurements on your laptop! I want you to gain an understanding of spinning disk performance HDD or SSD.

You can use the tool of your choice for the calculations. I user __HDTune Pro__, free version.

With hardware, its trickier! For this exercise to work, you really need to install software on a physical machine. If you have a home computer or laptop, the suggested software should be safe. If you are using a work laptop, do not install any software! If you are in the University, you also cannot install any software in labs.

If you cannot do the performance exercise on real hardware, you can run it in a Windows VM. However, your results will be anomalous.