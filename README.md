# Thread_Yield

1. Complete the Java program that is provided by implementing 4 threads so that the client, the server and the network all run concurrently. The client has 2 threads, one for sending the transactions and another for receiving the completed transactions.
In case the input and output network buffers are full or empty each client or server thread must yield the cpu using the Java method Thread.yield(). The network thread executes an infinite loop that ends when both client and server threads have disconnected. In case the client or sever threads are still connected the network thread must continuously yield the cpu.

2. Record the running times of both client threads and the server thread using the Java method System.currentTimeMillis().
3. Provide output test cases with the appropriate running times for the client and the server threads. Perform 3 different runs of the program and explain why there is a difference in the running times.
