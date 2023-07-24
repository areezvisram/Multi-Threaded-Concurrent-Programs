# Java Concurrent Programs

This directory contains concurrent programs implemented in Java, showcased using Jupyter Notebooks for interactive exploration.

## Camping Scouts

The notebook `camping_scouts_monitors.ipynb` demonstrates a thread-safe solution to the Camping Scouts problem using monitors in Java. The program models a scenario where multiple scouts are trying to eat from a pot, and the solution ensures that they can do so without conflicts.

## Fair Reader Writer

The notebook `fair_reader_writer.ipynb` showcases a fair solution to the classic Readers-Writers problem in Java using threads and semaphores. The program ensures that both readers and writers get equal opportunities to access the shared resource without causing starvation.

## Frequency Counter

The notebook `frequency_counter_monitors.ipynb` presents a thread-safe program in Java that counts the number of events, allowing only one thread to access each event at a time. Additionally, the notebook also implements `HighFrequencyCounter`, which allows multiple threads to access different events simultaneously.

## Village Pub

The notebook `pub_with_monitors.ipynb` simulates a concurrent village pub in Java, where villagers can enter a limited space pub concurrently. The program uses monitors as synchronization mechanisms to ensure the proper management of villagers accessing the pub.
