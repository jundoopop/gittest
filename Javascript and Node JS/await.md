#### from [[https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await |  await - JavaScript in MDN (mozilla.org)  ]]

It is an operator. It's used to wait for [[Promise]] and gets its fulfilment value.

Used inside an [[async]] function or at the top level of a [[module]].

#### Promises

An object that represents the completion or failure of an asynchronous operation. The guide explains how to consume and create promises, and how they can help avoid the callback pyramid of doom.
 
#### Promise chaining

A technique to execute multiple asynchronous operations sequentially, using the then () method to register callbacks and return new promises.

#### Error handling:

How to catch and handle errors or exceptions in promise-based code, using the catch () method or the async / await syntax.

#### Promise composition:

How to run multiple promises concurrently or conditionally, using methods like Promise.all (), Promise.allSettled (), Promise.any (), and Promise.race ().

#### Promise creation:

How to create a new promise from scratch using the Promise constructor, and how to wrap old APIs that use callbacks with promises.

#### Promise timing:

How and when the callbacks registered with promises are executed, and how they relate to the JavaScript event loop, tasks, and microtasks.