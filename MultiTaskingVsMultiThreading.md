## MultiTasking vs MultiThreading

| Feature of OS | Feature of process |
| ------ | ------ |
| Logical extension of MultiProgramming | Thread based MultiTasking |
| Allows CPU to perform multiple tasks (program, process, task) simultaneously | Allows multiple threads of the same process execute simultaneously|
| Separate memory and resource are for each program | Sharing common memory and resource (for the process) |
| Context switching costly | Switching between threads is less expensive |
| Heavy-weight | Light-weight |
| Communication cost between tasks are high  | Communication cost between threads are low |