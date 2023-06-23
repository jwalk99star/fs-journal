# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | Inheritance and Encapsulation.|

02. How does `export` differ from `export default`?
  
  > | 'export' allows a file that it is imported in to  to access all the code in the exported file.  export default is more specific, relaying only the specified information.  |

03. What is Encapsulation?
  
  > | Bundling data to restrict access from outside of that bundle. |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | 'custom functionality', we can also use proxy objects to override a get operator to prevent accessing properties, and we can add 'custom validation'.  |

05. What the difference between a `class` and an instance of a `class`?
  
  > | a class is like a rule that is applied to objects inside it. an instance of a class refers to one of those objects.|

06. What is a computed Property?
  
  > | a property thats value has been changed based on its interaction with another value |

07. What is the purpose of the `MVC` pattern?
  
  > | Organization |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | reflect the users input. like a game controller reflects the input of the gamer, or a waiter reflects the input(order) of a customer. It also updates the view based on changes in the model.  (Per the MVC article, it's the "brains of the operation".)|

09. What is the job of the `Service` in `MVC`?
  
  > | manage the action directed by the controller, isolated from the rest of the application. (Like the kitchen in a restaurant, that receives an order from a waiter.) |

10. What is the job of the `Model` in `MVC`?
  
  > | it handles the data representation. its the file where we can store static information which can be modified/used when exported from model and imported into other files.|
