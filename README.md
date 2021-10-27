# semaphores
Multithreading and locks/semaphores

There is a drive-through COVID testing station at the end of a dead-end road. People who would like to get tested can drop in unannounced and get a test without even leaving their cars. The doctor who performs the tests can only test one patient at a time. When nobody is waiting to get tested, the doctor takes a break. If a car arrives and sees that no one is being tested, it must notify the doctor that they have arrived. If the doctor is performing a test, any additional arriving vehicles will wait in line. The road leading up to the test station can fit a certain number of cars until the queue blocks the previous intersection. Therefore, if a vehicle arrives and sees that the line is full, they will take a detour and try again later.

Using POSIX threads, mutex locks, and semaphores, implement a solution that coordinates the activities of the doctor and the cars.
