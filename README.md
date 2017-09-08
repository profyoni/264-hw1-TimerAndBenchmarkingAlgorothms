# 264-hw1-TimerAndBenchmarkingAlgorothms

Create a `Timer` class and use it to benchmark 2 Java algorithms
===================
#### <i class="icon-file"></i> **Implement using Best Practices**
    public class Timer
    {
	    public void start() // starts the Timer; elapsedTime will start to accumulate. Calling start when the Timer is active (i.e. started) will result in a thrown IllegalStateException

	    public void stop() // stops the Timer; elapsedTime will stop accumulating. Calling stop when the Timer is inactive (i.e. stopped) is legal and does nothing
	    
	    public long getAccumlatedTimer()// returns the time between start/stop or reset/stop or the current accumulated time if the Timer is active

#### <i class="icon-file"></i> **Benchmarking**
Write a program that uses your `Timer` class to measure the time in milliseconds needed to run each of the following :algorthms. First add ten million random int's (in the full range of legal ints) into an array and then
- sort them using Arrays.sort (see Javadoc as needed). Output the time in ms needed to perform the sort
- call Arrays.binarySearch with a  random int 1000 times and output the time needed to run it.

**Submission due on Monday before class, on Hard Copy = paper printout.**

---
This was designed using  **StackEdit**[^stackedit]. 


  [^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.


  [1]: http://math.stackexchange.com/
