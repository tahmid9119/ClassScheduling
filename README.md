# Group Member 
| Name                  | Matric No     |
| -------------         | -------  |
| Ali Mohammed Ali Alattas| 1536481|
| Mohammad Tahmid Lodi  | 1725491  |
| Sultan Syafriyudi     | 1721899  |


# Introduction 
We have taken First Come First Serve Scheduling,  Round Robin and Shortest Job First Scheduling.
To balance the workload we have modified the FCFS scheduling, then created other two which are RR and SJF respectively.

# Consideration 
Here we are considering that arrival time for all processes is 0.

#Analysis
## FCFS 
In this, the process that comes first will be executed first and next process starts only after the previous gets fully executed.

Average waiting time = 18

Average turn around time = 25.2

## RR 
Round Robin is an easy to implement, it is preemptive algorithm. The newly created process is added to end of ready queue and generally employs time-sharing, giving each job a time slot or quantum.

Average waiting time = 22.2

Average turn around time = 29.4
## SJF 
Shortest job first (SJF) or shortest job next, is a scheduling policy that selects the waiting process with the smallest execution time to execute next.

SJN is a non-preemptive algorithm.

Average waiting time = 10.6

Average turn around time = 17.8
