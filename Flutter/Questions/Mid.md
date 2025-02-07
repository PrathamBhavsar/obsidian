- [[Flutter/Keys|What are keys?  ]]
    What keys do you know? When do you use them?  
    Bonus points for mentioning how the framework utilizes them.

- What is the extension method? Do you use them? Why they are great?

- What is isMounted property, why is it important, when to use it?  
    In an async method before using set State to see if the widget is still in the tree, otherwise, you get the exception.

- What is a mixin? When to use it? (When you need code sharing without using inheritance)

- State restoration. What is it? Have you used it? Custom objects? Any cases supported out of the box?

- How do you handle l10n in your apps?  
    **There are a few approaches, so just to know if they are aware of that and what was their attitude.**  
    Any troubles with .arb?  
    How do you handle plurals (maybe they did not need to)?  
    How do you handle Dates?

- Did you do any cross-platform above iOS & android?  
    **That is not so important if you do mobile-only in your company**  
    Any struggles? Adaptive GUI? Platform-specific widgets?

- How do you theme your app?  
    ThemeData, ColorScheme, or something else?  
    How do you handle dark mode?  
    What if you use MaterialApp but want to use the Cupertino widget?

- What is sound null safety? Why is it important? How to enable it?

- Immutability How to provide it? Why is it important?

- What is Navigator 2.0?  
    How does it differ from navigator 1.0?  
    Why was it introduced?  
    Did you use it, how did you implement it?

- Lifecycle of android or ios app?  
    **Asked to verify native experience, general mobile knowledge.  
    **How do you handle that in flutter? (plugin ofc)

- You have a Text but you want it to do something when you click it, how do you approach it?  
    **That is a bit tricky, elements should give feedback when pressed so Ink would be a better answer than GestureDetector.  
    **From UX perspective, would you wrap GestureDetector with anything? (helper to get to the visual feedback part)

- What are AOT and JIT and when it is used? Or in another way around, what is the difference between an app run in release mode and in debug mode.