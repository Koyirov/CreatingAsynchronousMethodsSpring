### Creating Asynchronous Methods

This guide walks we through creating asynchronous 
queries to GitHub. The focus is on the asynchronous 
part, a feature often used when scaling services.

### What We Will build

We will build a lookup service that queries GitHub 
user information and retrieves data through GitHub’s 
API. One approach to scaling services is to run 
expensive jobs in the background and wait for the 
results by using Java’s CompletableFuture interface. 
Java’s CompletableFuture is an evolution from the 
regular Future. It makes it easy to pipeline multiple 
asynchronous operations and merge them into a single 
asynchronous computation.

### Dependencies

* **Spring Web**