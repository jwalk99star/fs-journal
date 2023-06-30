# Understanding Asynchronous Code, and API's
01. What is the difference between `asynchronous` code and `synchronous` code?

  > |  Asynchronous code allows multiple things to happen at the same time. In synchronous code, things happen one at a time. |

02. What is an event listener?

  > "Its like a guy we hire to watch a certain thing, and if anything happens - he will tell that other guy." - Jeremy    The "certain thing" being watched/listened to - is the function in which the listener is placed. "that other guy" is the Application State.

03. What does *REST* stand for, and in simple terms what does it mean??

  > | Representational State Transfer. It's "an architectural style, or design pattern, for APIs". So, when you get information from a RESTful API,  it is a representation of the data that the API has about it's resource, presented to the client in the APIs predetermined way. |

04. What is a callback / higher order function?

  > | After the completion of another function, a callback function uses the result data from the first function as an argument to perform its own function. |

05. What is a `promise`? How do you capture an error from a `promise`?

  > It's "an asynchronous action that may complete at some point and produce a value."  ("I'll tell you when I find out.")  Using a "try / catch" can capture an error from a promise.

06. Name three processes used to make requests over `HTTP`?

  > get, post, put

07. What does the `API` acronym stand for?

  > Application Programming Interface

08. What must you do in order to `await` a promise inside of a function?

  > Make it an asynchronous function by adding the word "async" before its declaration, and then adding the word "await" before the request method that is inside the function.

09. What is the purpose of encapsulation in programming?

  > | The grouping or bundling of data to keep it separate from other data, sometimes for privacy/security and sometimes to keep functions or programs from mixing data and "polluting" their end results. |

10. What is `HTTP` response code for a successful request?

  > Status: 200

11. What is a 400 error?

  > Page not found. "Usually a 'front end' problem." - Jeremy
