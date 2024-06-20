# CPU-Scheduler
This project involves implementation of various CPU Scgeduling algorithms, preemptive and non-preemptive both.
Implemented algorithms:
1) First Come First Serve (FCFS) : First in, first out (FIFO), also known as first come, first served (FCFS), is the simplest scheduling algorithm. FIFO simply queues processes in the order that they arrive in the ready queue. 
In this, the process that comes first will be executed first and next process starts only after the previous gets fully executed.

2) Shortest Job First (SJF) : The shortest job first (SJF) or shortest job next, is a scheduling policy that selects the waiting process with the smallest execution time to execute next. SJN, also known as Shortest Job Next (SJN).
   
3) Longest Job First (LJF) : Longest Job First (LJF) is a non-preemptive scheduling algorithm. This algorithm is based on the burst time of the processes. The processes are put into the ready queue based on their burst times i.e., in descending order of the burst times.
  
4) Shortest Remaining Time First (SRTF) : In the Shortest Remaining Time First (SRTF) scheduling algorithm, the process with the smallest amount of time remaining until completion is selected to execute. Since the currently executing process is the one with the shortest amount of time remaining by definition, and since that time should only reduce as execution progresses, processes will always run until they complete or a new process is added that requires a smaller amount of time.


References Used:
1) https://www.youtube.com/watch?v=zFnrUVqtiOY&list=PLGF9VeuyJzDfFEeiK2N9NYhHedyEHQHxI
2) https://www.youtube.com/watch?v=EWkQl0n0w5M&list=PLBlnK6fEyqRitWSE_AyyySWfhRgyA-rHk
3) https://ravipatel1309.github.io/CPUScheduler/docs.html
