# Scheduling-Algorithms

I have implemented scheduling algorithms using C language. In this code snippet i have used file management system and structures. 

In this code first of all you have to choose which algorithm you have to perform. After choosing an algorithm you have to provide arrival time, burst time and priority of process column if required. 

After giving this much inputs you will get Gantt chart describing sequence of execution of processes. also you will get a table showing whole data of all process like Priority, Arrival time, Burst time, Completeion time, Turn around time and Waiting time. End of that you will also get Average Turn around time and Average Waiting time of scheduling.

There are total six scheduling algorithm I've implemented given below.

1. First-come first-serve scheduling algorithm : In first-come first-serve scheduling algorithm process which has shortest arrival time executes first.
2. Shortest Job first scheduling algorithm : In this scheduling algorithm process which has shortest burst time executes first
3. Round robin scheduling algorithm : In this scheduling algorithm you have to provide time quantum. this algorithm is same as shortest job first scheduling algorithm but processes can be run in time interval of given time quantum only.
4. Priority scheduling scheduling algorithm : In this scheduling algorithm process will be executed on the basis of priority given by user.
5. Shortest remaining time first scheduling algorithm : In this scheduling algorithm same as round robin scheduling algorithm but here time quantum is fixed that is equal to 1 and process which has shortest burst time executes first.
6. Longest remaining time first scheduling algorithm : In this scheduling algorithm same as Shortest remaining time first scheduling algorithm but here process which has largest burst time executes first.

Sample inputs,

1 1 0

3 5 0

5 2 0

7 5 0

Here, first column is Arrival time, second column is burst time and third column is priority.

<img width="533" alt="image" src="https://github.com/Harshil4442/Scheduling-Algorithms/assets/118929591/862a7eb7-6328-45b4-b4f9-9cad92271a85">


