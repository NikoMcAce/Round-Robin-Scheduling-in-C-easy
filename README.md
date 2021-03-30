# Round-Robin-Scheduling-in-C-easy
Hey I'm Raj Davande, and here I have given a code for round robin scheduling which is following the easiest methods and is fairly easy to understand.

In the above code we have one 2-D array which houses all the parameters required for a Job such as arrival time , burst time , remaining burst time , Time of completion and turn around time as different elements in the 2D array.
We increase the time by the specified time quantum and at the same time we deduct the time remaining for a job by the time quantum. 
If the remaining time is smaller than the time quantum we add the remaining time to the time variable and set the remaining time to zero. 
All of this happens only when the job has an arrival time less than or equal to current time and the remaining time is not zero.
If that condition is not met then we consider the time to be Idle time and hence print idle at time t.


**Made By Raj Davande **
**-NikoMcAce**
