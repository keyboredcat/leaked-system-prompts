# A Guide to High-Quality Code Generation with LLMs

A collection of prompts for generating high quality code...

I wrote an SOP recently for creating software with the help of LLMs like ChatGPT or Claude. A lot of people found it helpful so I wanted to share some more prompt-related ideas for generating code.

The prompts offered below work much better if you set up a proper foundation for your program before-hand (i.e. provide the AI with more context, as detailed in the SOP), so please be sure to take a look at that first if you haven't already.

## My Standard Prompt for Code Generation

Here's my go-to template for requesting code:

```
I need to implement [specific functionality] in [programming language].
Key requirements:
1. [Requirement 1]
2. [Requirement 2]
3. [Requirement 3]
Please consider:
- Error handling
- Edge cases
- Performance optimization
- Best practices for [language/framework]
Please do not unnecessarily remove any comments or code.
Generate the code with clear comments explaining the logic.
```

This structured approach helps the AI understand exactly what you need and consider important aspects that you might forget to mention explicitly.

## Reviewing and Understanding AI-Generated Code

Never, ever blindly copy-paste AI-generated code into your project. Ask for an explanation first. Trust me. This will save you considerable debugging time and you will also learn a thing or two in the process.

Here's a prompt I use for getting explanations:

```
Can you explain the following part of the code in detail:
[paste code section]
Specifically:
1. What is the purpose of this section?
2. How does it work step-by-step?
3. Are there any potential issues or limitations with this approach?
```

## Using AI for Code Reviews and Improvements

AI is great for catching issues you might miss and suggesting improvements.

Try this prompt for code review:

```
Please review the following code:
[paste your code]
Consider:
1. Code quality and adherence to best practices
2. Potential bugs or edge cases
3. Performance optimizations
4. Readability and maintainability
5. Any security concerns
Suggest improvements and explain your reasoning for each suggestion.
```

## Prompt Ideas for Various Coding Tasks

### For implementing a specific algorithm:

```
Implement a [name of algorithm] in [programming language]. Please include:
1. The main function with clear parameter and return types
2. Helper functions if necessary
3. Time and space complexity analysis
4. Example usage
```

### For creating a class or module:

```
Create a [class/module] for [specific functionality] in [programming language].
Include:
1. Constructor/initialization
2. Main methods with clear docstrings
3. Any necessary private helper methods
4. Proper encapsulation and adherence to OOP principles
```

### For optimizing existing code:

```
Here's a piece of code that needs optimization:
[paste code]
Please suggest optimizations to improve its performance. For each suggestion, explain the expected improvement and any trade-offs.
```

### For writing unit tests:

```
Generate unit tests for the following function:
[paste function]
Include tests for:
1. Normal expected inputs
2. Edge cases
3. Invalid inputs
Use [preferred testing framework] syntax.
```

I've written a much more detailed guide on creating software with AI-assistance here which you might find more helpful.

As always, I hope this lets you make the most out of your LLM of choice. If you have any suggestions on improving some of these prompts, do let me know!

Happy coding!
