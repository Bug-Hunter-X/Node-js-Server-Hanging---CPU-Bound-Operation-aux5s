# Node.js Server Hanging - CPU-Bound Operation

This repository demonstrates a common issue in Node.js where a long-running, CPU-bound operation within the request handler causes the server to hang and become unresponsive.  The example uses a simple loop to simulate a CPU-intensive task.  The solution shows how to address this using asynchronous operations and worker threads.