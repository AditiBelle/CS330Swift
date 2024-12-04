
# SWIFT- CS330

This repo serves as a tutorial for the Swift Programming language. 



Author: Aditi Belle


## __HISTORY__: 

Swift was first announced at Apple's Worldwide Developer Conference in 2014, making it a relatively new language. Its development first began in 2010 by a team over at Apple led by Chris Lattner with Doug Gregor, John McCall, Ted Kremenek, and Joe Groff. The reason for developing Swift was to ease up the process of app development for Apple's devices. Prior to the release of Swift, this process was done through Objective-C. The objective to switching over to Swift was to make programming more accessible and faster in addition to reducing chances of error. 



## __VARIABLES & DATATYPES__: 

Swift has several reserved words. Linked right here is the entire list of the reserved words in the langauge in order for you to reference: https://swiftbydeya.com/swift-keywords/
Swift's keywords are crucial to how the language functions and are used for declarations, statements, expressions, types, patterns, bitwise operators as well as some reserved for particular contexts. 

In order to name variables in Swift, they must start with either a letter, _, or a $. They CANNOT start with numbers. The language is also case-sensitive, so two variables with the same name but different capitalizations (ex. hello & Hello) are different variables. 

Swift is statically-typed, meaning that every single object is checked while the code is compiling, rather than on run-time. This makes Swift more efficient as a langauge and easier to debug. 

In addition to being efficient, Swift is also strongly-typed, meaning that when you set a vraible, Swift checks during compiling, if the variable is the correct type. 

Operators available for each datatype in Swift are: Arithmetic Operators, Assignment Operators, Comparison Operators, Logical Operators, Bitwise Operators, Ternary Operator, Nil-Coalescing Operator, and Range Operator. 

## __FUNCTIONS__:

In order to declare a function in Swift, you must include a keyword that is used to declare the function, a name for the function itself, parameters, and the return value. 
                  `func = NameofFunction(parameters) -> returnType {
                  }` [8]
When creating a function, there are no rules regarding where in the code file it is placed. Additionally, Swift allows for recursive functions. Furthermore, Swift allos for functions to take in many parameters of different datatypes. 

Swift allows you to return multiple values from your functions but NOT multiple datatypes. In order to be able to return multiple datatypes however, it should be in a tuple, array or dictionary. 

The langauge carries out both pass-by-value and pass-by-reference. For pass-by-value, the parameter must not be in-out. For pass-by-reference, the parameter must be in-out. In-out refers to any constant value type that passes a function. 

In a stack operation, local variables are stored on the stack. In a heap, a dynamic allocation of memory is allowed. It does not follow the same strict rues of the stack and is used for storing large amounts of data as well as for accessing data throughout the application as well. 

In Swift there are three different types of Scope:
            
              
              -  Global: This is where variables are defined outside of the classes and functions at the highest level of the code. This can be used in all of the functions and classes. 
              - Local: This is present within a specific function and that function only. Often called the function scope. 
              - Class: This is where the class and functions are defined.

When it comes to side effects, it is hard to tell what changes functions make internally to the object. This can get tricky and it can be had to tell what exact changes are ocucuring. The onChange property details all the changes in state of the object to further understand any side effects occurring.

In Swift, local variables are stored in a stack. The stack also manages call frames. It is managed by the compiler. 


## SELECTION, LOOPS & CONDITIONALS:

In Swift, Boolean values print as either true or false. They are not capitalized like typical languages. Swift allows you to write if/else if/else statements, which are different than what you would typically come across in Python. 

In order to delimit a code block, Swift utilizes curly brackets {}. This in turn organizes the if-else statements, eliminating the "dangling-else" problem. 

Swift allows for short circuiting by using && for 'and' and || for 'or'. In this case, if the first condition is false, the second condition will not be checked. In order for the statement to be considered true, both of the conditions must be true. 

```  An example of short-circuiting in Swift: 
let isCold = false

let isHot = true


if isCold && isHot {


  print("It is warm!")


}
```

For control flow in swift, 'if', 'guard', and 'switch' statements allow the code to branch off into different condtions. The 'break' and 'continue' are used to transfer the flow of electution to another location in the code [22]. 

## CLASSES & INHERITANCE:

Swift is an object oriented language. Objects are called in an instance of a class. Unlike Java and Python, in Swift there is no need to convert the objects to a string in order to get printed out. Simpply using the print statement will suffice. 

Swift also supports inheritance by allowing the ability to create a new class from an existing class. Unlike using multiple files t carry out inheritance, Swift allows for inheritance to happen on the same file. In Swift, the same method in a subclass overrides the same method in the superclass. 


          















## __REFERENCES__:
  In order of when they are mentioned throughout this file.  

1. https://www.javatpoint.com/history-of-swift#google_vignette
2. https://www.educative.io/courses/swift-programming-mobile-app/history-of-swift
3. https://swiftbydeya.com/swift-keywords/
4. https://www.programiz.com/swift-programming/variables-constants-literals
5. https://www.alibabacloud.com/tech-news/a/swift/gv9vmn13zh-swifts-type-system-leveraging-safety#:~:text=The%20type%20system%20in%20Swift%20is%20static%2C%20which%20means%20that,effectively%2C%20leading%20to%20better%20performance.
6. https://www.aidanf.net/learn-swift/types_and_type_inference#:~:text=Swift%20is%20strongly%20typed.,(since%20it's%20statically%20typed).
7. https://www.programiz.com/swift-programming/operators
8. https://www.programiz.com/swift-programming/functions
9. https://docs.swift.org/swift-book/documentation/the-swift-programming-language/functions/#
10. https://www.hackingwithswift.com/quick-start/understanding-swift/how-can-you-return-two-or-more-values-from-a-function#:~:text=Swift's%20functions%20have%20a%20single,an%20array%20or%20a%20dictionary.
11. https://sarunw.com/posts/swift-inout-parameter/
12. https://stackoverflow.com/questions/27364117/is-swift-pass-by-value-or-pass-by-reference
13. https://medium.com/@vinodh_36508/understanding-memory-allocation-in-swift-stack-vs-heap-03682b528bff
14. https://www.appypie.com/scope-context-swift-how-to#:~:text=What's%20“scope”%20in%20Swift%20programming,challenging%20to%20grasp%20at%20first.
15. https://goksel.codes/identifying-side-effects-using-swift/
16. https://medium.com/@vinodh_36508/understanding-memory-allocation-in-swift-stack-vs-heap-03682b528bff#:~:text=Stack%20Operation%3A&text=Control%20Flow%3A%20It%20keeps%20track,are%20stored%20on%20the%20stack.
17. https://theswiftdev.com/all-about-the-bool-type-in-swift/
18. https://www.geeksforgeeks.org/swift-if-else-if-statement/
19. https://docs.swift.org/swift-book/documentation/the-swift-programming-language/statements/
20. https://medium.com/@ayshindhe/short-circuiting-in-swift-a-simple-explanation-5be8358f20ca#:~:text=Swift%2C%20like%20many%20programming%20languages,and%20%7C%7C%20(OR)%20operators.&text=If%20the%20first%20condition%20is,entire%20expression%20to%20be%20true.
21. https://stackoverflow.com/questions/967511/how-do-different-languages-handle-the-dangling-else
22. https://docs.swift.org/swift-book/documentation/the-swift-programming-language/controlflow/
23. https://www.programiz.com/swift-programming/classes-objects
24. https://www.programiz.com/swift-programming/inheritance
