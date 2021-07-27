# How to Learn a Machine Learning Algorithm



The question of how to learn a machine learning algorithm has come up a few times on the email list.

In this post I’ll share with you the strategy I have been using for years to learn and build up a structured description of an algorithm in a step-by-step manner that I can add to, refine and refer back to again and again. I even used it to write a book.

This was just a strategy I used personally and I’ve been really surprised by the positive feedback.



## Algorithm Descriptions are Broken

Learning a machine learning algorithm can be overwhelming. There are so many papers, books and websites describing how the algorithm works mathematically and textually. If you are really lucky you might find a pseudocode description of the algorithm.

![Implement a Machine Leaning Algorithm](https://machinelearningmastery.com/wp-content/uploads/2014/01/Implement-a-Machine-Leaning-Algorithm.jpg)



If you are really really lucky you might find some suggested ways to configure the method for different situations. These descriptions are rare and typically buried deep in the original publication or in technical notes by the original authors.

A fact you learn quickly when you want to implement a method from research papers is that algorithms are almost never described in sufficient detail for you to reproduce them. The reasons vary, from the micro-decisions that are left out of the paper, to whole procedures that are summarized ambiguously in text, to symbols that are used inconsistently. 

 

## Piece it Together

To understand an algorithm you have to piece together an understanding yourself from disparate descriptions. This is the only tactic that I have found to be successful.

Disparate descriptions means resources such as the original descriptions of the method in the primary sources as well as authoritative secondary interpretations made of original descriptions in review papers and books.

It is common for there to be prototype implementations of a method released with the primary sources and reading this code (typically C, FORTRAN, R or Matlab) can be very enlightening for the details you need to reproduce an algorithm.

## Algorithm Descriptions

An algorithm is an island of research and in all reality it can be difficult to pin down the canonical definition. For example, is it the version described in the primary source or is it the version that includes all the fixes and enhancements that are “best practice”.

A solution is to consider a given algorithm from multiple perspectives, each of which can serve a different purpose. For example, the abstract information processing description of the algorithm could be realized by a variety of different specific computational implementations.

I like this approach because it defends the need to telescope in on a specific case of the algorithm from many possible cases at each step of the description while also leaving the option open for the description of variations.

There are many descriptions you could use of varying specificity depending on your needs. Some that I like to use include: inspiration for the algorithm, metaphor or analogy for the strategy, information processing objectives, pseudocode and code.

## Algorithm Prescriptions

When I started my own research projects, I thought the answer to this problem was to read everything on an algorithm and create the definitive implementation in code. Nice idea perhaps, but code is just one way to communicate an algorithm, and it is limited.

There is more to an algorithm description than the computation. There is meta information around an algorithm that can be invaluable for certain use cases.

For example, usage heuristics for an algorithm are embedded in papers. Having a summary of usage heuristics collected together in one place can mean the difference of getting a good enough result quickly and running sensitivity analysis on the algorithm for days or weeks.

Other examples include the standard experimental datasets used to test the algorithm, the general classes of problem to which the algorithm is suited, and known limitations that have been identified and described for the algorithm.

## Design an Algorithm Description Template

An algorithm description template provides a structured way for you to learn about a machine learning algorithm.

You can start with a blank document and list out the section headings for the types of descriptions you need of the algorithm, for example applied, implementation, or your own personal reference cheat sheet.

To figure out what sections to include in your template, list out questions you would like to answer about the algorithm, or algorithms if you are looking to build up a reference. Some questions you could use include:

- What is the standard and abbreviations used for the algorithm?
- What is the information processing strategy of the algorithm?
- What is the objective or goal for the algorithm?
- What metaphors or analogies are commonly used to describe the behavior of the algorithm?
- What is the pseudocode or flowchart description of the algorithm?
- What are the heuristics or rules of thumb for using the algorithm?
- What classes of problem is the algorithm well suited?
- What are common benchmark or example datasets used to demonstrate the algorithm?
- What are useful resources for learning more about the algorithm?
- What are the primary references or resources in which the algorithm was first described?

Once you have settled on some questions, turn them into section headings.

For each section heading clearly define the requirements of the section and the form that the description in that section will take. I like to include motivating questions for each section that once answered will satisfy the section at the minimum level of detail.

## Start Small and Build it Up

The beauty of this approach is that you don’t need to be an expert in the algorithm or in research. As long as you can find some resources that mention the algorithm, you can start to capture notes about an algorithm in the template.

You can start really simply and collect high-level descriptions of the algorithm, its names and abbreviations and the resources you have found and what they talk about. From here you can decide to expand the description further, or not.

You will end up with a one-to-two page description of the algorithm very quickly.

## I Use It

I’ve been using algorithm templates for a long time. Some examples where I have found this strategy practically useful include:

- Implementing machine learning algorithms using a descriptive-focused template.
- Applying a machine learning algorithm using an applied-focused template.
- Building a catalog of algorithms to use and refer to using a general purpose template.

In this last case, I turned my catalog into a book of 45 nature inspired algorithms which I published in early 2011. The book is called [Clever Algorithms: Nature-Inspired Programming Recipes](https://github.com/clever-algorithms/CleverAlgorithms).

## Summary

In this post you learned about using an algorithm description template as a strategy for learning a machine learning algorithm.

You learned that algorithm descriptions are broken and the answer to learning an algorithm effectively is to design an algorithm template that meets your needs and to fill in the template as you read and learn about the algorithm.

You learned that the template is an efficient and structured way to tackle an overwhelming problem.