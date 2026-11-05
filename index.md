
---
layout: default
title: Methodology Assignment 4
---

# DSC 180A Methodology Assignment 4

**Name:** Preethi Manne

**Email:** pmanne@ucsd.edu

**Section:** D21

**Mentor:** Armin Schwartzman

## Quarter 2 Project Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

One interesting thing was how much emphasis a lot of people put on improving the accuracy of LLMs or improving the quality of its implementation. We compared two different prompting strategies, but both achieved high accuracy and only gave a small difference between them. LLMs are already very well trained, so it is kind of difficult to actually get a meaningful difference in our experiments.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A potential investigation we could pursue for our Quarter 2 Project is to experiment on whether the effectiveness of test driven reasoning depends on the difficulty of the coding problem at hand. In our current experiment, both chain of thought and TDD performed pretty equally, so there was not much of an improvement of difference to record. So, I think it would be more interesting to see if the TDD gives an advantage for harder programming problems when the model needs to think about more complex logic and edge cases.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One change we would make to our current approach is being more careful in how we choose the coding problems for our experiment. Currently, we evaluated both chain of though and TDD conditions on a subset of 100 LiveCodeBench problems. But, we did not select them based on difficulty, so all the problems were chosen completely randomly. Both conditions gave us high accuracy on the hidden tests, so it was hard to actually conclude if TDD had an advantage. I would change our sample of problems to have different difficulty levels so we could understand where each prompting strategy performs well or does not.

**4. What other techniques would you be interested in using in your project?**

I would be interested in testing whether LLMs perform better when they can actually run the tests they generate and use the results to fix their implementation. Right now, we just ask the model to think about test cases before writing code. So, I think it would be really interesting to see if having the model run the tests it generates and make changes could lead to better solutions.
