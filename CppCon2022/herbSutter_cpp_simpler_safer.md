# Can C++ be 10x Simpler & Safer? - Herb Sutter - CppCon 2022

### __Video__:  
https://youtu.be/ELeZAKCN4tY

### __Download ppt__:  
https://github.com/CppCon/CppCon2022/raw/main/Presentations/CppCon-2022-Sutter.pdf

### __Mapped CS fundamentals__:  
To fully understand the contents of the video, the following computer science subjects are fundamental:

<details>
<summary>Programming languages</summary> 
A basic understanding of programming languages, their features, and how they work is necessary to comprehend the video.
</details>

<details>
<summary>C++ Syntax and semantics</summary>  
The video discusses the importance of good syntax in a language and how it can affect its safety and simplicity. Understanding syntax and semantics is necessary to understand the proposed changes to the C++ language.
</details>

<details>
<summary>Compilers</summary>  
The video talks about a pre-alpha compiler running on Microsoft Visual C++ and GCC, and how the instructions can be used to compile C++ code into CPP files. Knowledge of compilers and their functionalities is necessary to understand this aspect of the video.
</details>

<details>
<summary>Memory management</summary>  
The video discusses memory safety issues in C++ and how they can be addressed. A basic understanding of memory management in programming languages is necessary to understand this aspect of the video.
</details>

<details>
<summary>Type safety</summary>  
The video discusses the concept of type safety in C++ and how it offers strong type checking by default. Understanding type safety is essential to understand this aspect of the video.
</details>

<details>
<summary>C++ Standard library functions</summary>  
The video discusses the usage of safer, standardized pointer type and standard library functions such as “unique.newshared.new” and “gc.new” instead of less safe “bitwise manipulation.” Knowledge of standard library functions is necessary to understand this aspect of the video.
</details>

<details>
<summary>Constraints</summary>  
The video also discusses the use of constraints to make code more concise and easier to read. Knowledge of constraints and how they work is necessary to understand this aspect of the video
</details>
</br>

###  __Video summary__:
_This is an AI generated summary. There may be inaccuracies_

### First Hour  
Herb Sutter discusses simplification of C++ code in order to make it 10x safer and simpler. He demonstrates how this can be achieved by using a safer, standardized pointer type and by teaching developers to use the standard library functions "unique.newshared.new" and "gc.new" instead of less safe "bitwise manipulation."

#### timestamps
<details>
<summary>00:00:00</summary>  
Herb Sutter discusses his idea for making C++ simpler and safer, arguing that 100% syntax compatibility would be a major step in that direction. He goes on to discuss a strategy for achieving this, which revolves around applying zero overhead abstraction to C++. If this strategy works, it would result in fewer vulnerabilities and bugs, as well as faster and more frictionless development.
</details>
<details>
<summary>00:05:00</summary>  
Herb Sutter talks about the possibility of creating a new syntax for C++ that is simpler and safer. This syntax would have less concept count, but would still be able to express all the features that C++ programmers need. He has been working on this project for the past seven years and has recently presented a detailed proposal for this new syntax at CppCon.
</details>
<details>
<summary>00:10:00</summary>  
Herb Sutter discusses how simplification of C++ can make it 10x safer and simpler, and how his own experiments are leading to a syntax two compiler in progress. These instructions can be used to compile C++ code into CPP files which can be run through your compiler of choice.
</details>
<details>
<summary>00:15:00</summary>  
In his talk at CppCon 2022, Herb Sutter discusses the potential for simplification of C++ code by moving to a left-to-right syntax. He also discusses the importance of context-free parsing and order-independence, and stresses the need for good syntax in a language.
</details>
<details>
<summary>00:20:00</summary>  
The author describes his experiment to make C++ simpler and safer, and how the default syntax for functions and lambdas works well. He also points out that the default syntax for composite data types is convenient and efficient.
</details>
<details>
<summary>00:25:00</summary>  
Herb Sutter discusses how C++ can be 10x simpler and safer than it is today, highlighting how generating code is easier with C++20. He also demos a pre-alpha compiler running on Microsoft Visual C++ and GCC.
</details>
<details>
<summary>00:30:00</summary>  
This YouTube video demonstrates how C++ can be 10x simpler and safer than the current standard. The first example uses the cpp2 syntax which is order independent and emits C++ code directly from P2. The second demo uses the pure cpp2 switch and demonstrates how the free store works.
</details>
<details>
<summary>00:35:00</summary>  
The author of the video discusses how C++ can be simpler and safer, and how various safety features help to mitigate potential risks. He also discusses how source compatibility allows for easy adoption of the language.
</details>
<details>
<summary>00:40:00</summary>  
Herb Sutter discusses how C++ is not 10x simpler or safer than other languages, and that memory safety is an important issue. The Department of Commerce released guidance on software security in response to the Executive Order on Cyber Security in the United States in 2021. This year, they are funding projects to rewrite existing infrastructure in other languages.
</details>
<details>
<summary>00:45:00</summary>  
In this video, Herb Sutter discusses how C++ can be 10x simpler and safer than it is currently. He starts by discussing the concept of type safety, and how C++ offers strong type checking by default. He then goes on to discuss how C++ supports dynamic typing, and how it is important for generic code. Finally, he shows how C++ can be even more efficient by using generic functions.
</details>
<details>
<summary>00:50:00</summary>  
This video demonstrates how simple and safer C++ can be when compared to its predecessor, C. Herb Sutter argues that C++ should adopt a more modern, type-safe approach, and demonstrates how this can be achieved by using the C++ standard library.
</details>
<details>
<summary>00:55:00</summary>  
In this video, Herb Sutter discusses how C++ can be made 10x simpler and safer by teaching developers to use a safer, standardized pointer type known as "stood span." He also recommends using the standard library functions "unique.newshared.new" and "gc.new" instead of the less safe "bitwise manipulation" when dealing with pointers.
</details>
<br/>

### Second hour
In this part, Herb Sutter discusses how C++ could be 10x simpler and safer by teaching the standard syntax and by using the unified C++ syntax. He also covers the benefits of using a STANDARD file extension and CONSTRAINTS to make code more concise and easier to read.

#### timestamps
<details>
<summary>01:00:00</summary>  
Herb Sutter discusses the possibility of C++ being 10x simpler and safer than it is currently, and how he implemented a bounds checking mechanism into his code using compiler switches. He also shows how this can be turned on or off depending on the situation.
</details>
<details>
<summary>01:05:00</summary>  
This video discusses how C++ can be 10x simpler and safer than it is currently, with a focus on the bound safety features that Herb Sutter has been working on. It covers topics such as conditions and assertions, contract groups, and lifetime safety. Finally, it shows an example of how these features can be used to improve an application.
</details>
<details>
<summary>01:10:00</summary>  
In this video, Herb Sutter discusses how C++ can be 10x simpler and safer than it is currently. He starts by discussing how C++ guarantees an initialization before use, and goes on to discuss how uninitialized variables can be safely handled in C++. He then discusses parameter passing and initialization, showing how they go together and how they can be made more efficient. Finally, he discusses how essential and accidental complexity can be distinguished, and how C++ can be improved by removing unnecessary complexity.
</details>
<details>
<summary>01:15:00</summary>  
Herb Sutter discusses how c++ can be simpler and safer by cataloging which rules are essential and which are accidental. He also introduces concepts of definite first and last use.
</details>
<details>
<summary>01:20:00</summary>  
This YouTube video discusses how C++ can be 10x simpler and safer than the current language, CPV2. The main points made are that with the new concept of "constructible initialization," code can be written more easily and with less littering of the namespace. Additionally, by generating a return struct, the programmer does not have to worry about forgetting to initialize a variable before returning it.
</details>
<details>
<summary>01:25:00</summary>  
In this video, Herb Sutter discusses how C++ can be simpler and safer than it is currently, and how cpp2 provides many automatic safety features. He also shows how to declare functions in cpp2, and how forwarding works with concrete types.
</details>
<details>
<summary>01:30:00</summary>  
Herb Sutter discusses how C++ can be 10x simpler and safer than it is currently, highlighting the benefits of lambda capture and postconditions. He also discusses how the language's constructs are familiar to developers, and how he plans to further simplify them in the future.
</details>
<details>
<summary>01:35:00</summary>  
Herb Sutter discusses how C++ can be 10x simpler and safer, and how some of these changes could be implemented in the near future. He includes the idea of a "directed evolution" of C++ that would keep the language honest and compliant with modern standards.
</details>
<details>
<summary>01:40:00</summary>  
Herb Sutter discusses how C++ could be 10x simpler and safer, and introduces a new experiment to try to achieve this goal.
</details>
<details>
<summary>01:45:00</summary>  
Herb Sutter discusses the benefits of using STANDARD file extensions, STANDARD formatting, and CONSTRAINTS to make code more concise and easier to read. He also discusses the challenges of teaching these concepts, and how he hopes to overcome them in the future.
</details>
<details>
<summary> 01:50:00</summary>
Herb Sutter discusses the benefits of using a unified C++ syntax and how C++2y will help make teaching and learning 10x easier. He also mentions the need for backward compatibility and the need for a name for the syntax.
</details>