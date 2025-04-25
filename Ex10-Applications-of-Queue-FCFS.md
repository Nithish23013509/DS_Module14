Ex2E Applications of Queue – FCFS
DATE: 12-03-2025
AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.

Algorithm
Start with process, burst time, and waiting time arrays.
Loopthrough each process from i= 0 to n-1.
Compute tat[i] = burst_time[i] + wait_time[i].
End the algorithm.
Program:
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: NITHISH S
RegisterNumber: 212223220070

int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
// calculating turnaround time byadding
// burst_time[i] + wait_time[i] int i;
for ( i = 0; i < n ; i++)
tat[i] = burst_time[i] + wait_time[i]; return 0;
}

*/
Output:
image

Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
