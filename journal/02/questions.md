# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > var, let, const

02. What is the definition of a function?

    > a subprogram designed to perform a particular task. 
    > also, "functions are objects."

03. What are the `SOLID` principles?

    > Single responsibility: A class should only have one function and one reason to change.
    > Open/closed: Open to extension, but closed for modification.
    > Liskov substitution: Objects of the same type should be replaceable with others from the same category without changing the function of the program.
    > Interface segregation: A programmers interfaces should be kept seperate from one another.
    > Dependency Inversion: High level modules shouldn't depend on low level modules, but both should depend on abstractions. Also, abstractions should not depend on details but details should depend on abstractions.


04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > let removedFruit = fruit.splice(2, 1);

    > // console.log(fruit)  // ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    > // console.log(removedFruit) // [ 'pineapple' ]


05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > them.friends.push(you)
    > you.friends.push(them)

06. Give an example of a JavaScript `Conditional`:

    > if (num % 2 == 0) {
    >   return 'even'
    > }

07. What is the main difference between `parameters` and `arguments`?

    > parameters are used when defining a function. they are the names created in the function definition.
    > arguments are the values the function receives from each parameter when the function is executed/invoked.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > the "debugger" in the chrome dev tools (found in the sources tab) can be used to add breakpoints and check code in smaller pieces.

09. What is the difference between a `primitive` value and a `reference` value?

    > a primitive value is something like a boolean or a number, that is not an object. There are 7 of them.
    > a reference value is one that "points" at something else.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = -100, i <= 100, i++) {
        console.log(i)
    }
