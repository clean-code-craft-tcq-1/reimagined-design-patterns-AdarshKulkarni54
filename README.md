# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.

**Adapter Design Pattern**
 Adapter design pattern helps to reuse the existing code even if the two objects are incompatible to each other
 **Example:** When I have been to Germany for deputation, I was in need of ID card for entering to Bosch campus hence had to inform to HR,but as I am not aware of German language, had to ask my German Colleague to translate my request (which is in English) to German and inform the HR. 
 So here the objects me and HR are incompatible in terms of language hence my colleague acts as "Adapter" here to make it understand/communicate each other. 
 
 **Advantage:**
 We can provide data in requested format even if we do not have so that incompatible code can communicate with each other
 
 **Disadvantage:**
 All the processes might communicate through adapters only so might decrease in performance
 
**Builder Design Pattern**
 Builder pattern can be defined as, a design pattern that separates the construction of a complex object from its representation.
 **Example:** When I need my resume in two formats, one is in PDF and another one is in WORD so here the data which contains in both format is same
 the only thing here is I just need two dependencies/libraries for PDF and WORD hence I can make one object which holds the data and can have two separate
 builders, PDFBuilder and WORD Builder so that I can build my resume in two formats based on need.
 
 **Advantage:**
 Provides control over steps of construction process.
 
 **Disadvantage:**
 Complexity of code might increase 
 
 **State Design Pattern**
  The state pattern is a behavioral design pattern. a state allows an object to alter its behavior during it's life cycle
  **Example:** In my project, we have IBM RTC tool (basically an application life cycle management tool) where we will create an Bug if we found in our application
  so in the later point of time, the bug states will gets change i.e. when it was created then will be in "New" state and once the developer starts working on it then
  will be in "In Progress" state, once if the developer completes the implementation he/she will send for the review hence the bug state change will be in "Implemented",
  if the reviewer rejected the implementation again state will be change from "Implementation" to "In Progress" else if the implementation is approved the bug state will be 
  changed to "Fixed" so this is how design pattern helps implementing such type of feature/application
  
  **Advantage:**
  It also helps in reducing complexity by reducing if-else statements so there by we can easily add state to object.
  
  **Disadvantage**
  It might be difficult in maintaining the code if more states are getting added.
