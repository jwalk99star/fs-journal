# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, Delete |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | C- post, R- get, U,- put, D- remove |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | Object Relational Mapper |

04. Which two `HTTP` request types include a body?

  > | post & put |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | 1 - synchronous / 2 - asynchronous |

06. What are the three types of data relationships? Provide an example of each.

  > | One to one/1:1 - Author to Address, where the author lives at a single address and the address only contains the one author.
    | One to Many/1:N - Blog to Comments, where the Blog has many comments, but A comment is only related to a single Blog.
    | Many to Many/N:M - Book to Author, where the book was written by more than one Author, and those Authors may have written more than one book. |

07. What is middleware?

  > | A security check between your database and another application; i.e., .use in our constructor.|

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | client request,  server response |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | http://localhost:8080/?tag=winter |

10. What is a ***virtual property***?

  > | Additional fields for a given model; i.e., a full name consisting of first AND last. |
