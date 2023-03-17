# OS-Assignment CPU scheduling algorithms for Shortest job first (SJF) and Round Robin (RR)
This project contain java implementation of two CPU scheduling algorithms Shortest job first (SJF) and Round Robin (RR)

## SJF Algorithm
The SJF Algorithm in which the process having the smallest execution time is chosen for the next execution. This scheduling method can be preemptive or non-preemptive. It significantly reduces the average waiting time for other processes awaiting execution. The implementation of SJF Algorithm can be found in the <a href ="https://github.com/tasneem1412/OS-Assignment/blob/main/SJF%20OS/src/com/company/Main.java ">SJF.JAVA</a> file

![SJF](https://user-images.githubusercontent.com/128141527/225900593-3ae65a31-f4be-4d49-8831-9e0af58b3a9e.png)

# RR Algorithm
The Round Robin scheduling algorithm is one of the CPU scheduling algorithms in which every process gets a fixed amount of time quantum to execute the process. In this algorithm, every process gets executed cyclically. This means that processes that have their burst time remaining after the expiration of the time quantum are sent back to the ready state and wait for their next turn to complete the execution until it terminates. This processing is done in FIFO order which suggests that processes are executed on a first-come, first-serve basis. The implementation of RR Algorithm can be found in the <a href ="https://github.com/tasneem1412/OS-Assignment/blob/main/RR%20OS/src/com/company/Main.java">RR.JAVA</a> file
  ![RR](https://user-images.githubusercontent.com/128141527/225909997-d5be0882-d6c6-4eb0-af20-92264edc3eaf.png)

