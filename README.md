# Task-scheduler

A daily task scheduler that orders tasks using a priority queue

The task scheduler input:
 1. task id
 2. description
 3. duration
 4. dependencies id "if any"
 5. starting time "if any"

The scheduler assigns a priority value to each task based on its duration, dependencies, and starting time using a formula then insert it in the queue.
After all the tasks have been inserted into the queue, the scheduler starts printing tasks in 10 minutes intervals with task status (complete/in progress)
