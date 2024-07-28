---
layout: project_page
permalink: /

title: LA-RCS (LLM-Agent Based Robot Operating System)
authors:
    Teak-Hyun Park, Seung-Hun Shin, Young-Jun Choi
affiliations:
    National Korea Maritime & Ocean University
paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
video: https://www.youtube.com/results?search_query=turing+machine
code: https://github.com/topics/turing-machines
data: https://huggingface.co/docs/datasets
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
LA-RCS (LLM-Agent Based Robot Control System) is a sophisticated robot control system designed to autonomously plan, task, and analyze external environments based on user requirements, leveraging an LLM-Agent. Utilizing a dual-agent framework, LA-RCS generates plans based on user requests, executes these plans while observing the external environment, and modifies the plans as needed to adapt to external conditions, ensuring user requests are satisfactorily fulfilled. By autonomously evaluating observations, providing feedback on its actions, and continuously executing commands based on ongoing environmental monitoring, this system significantly reduces the need for user intervention. Consequently, LA-RCS interprets user natural language commands and translates them into commands compatible with the robot's interface, enabling the robot to execute the tasks. We categorized the scenarios that LA-RCS needs to perform into four distinct types and conducted a quantitative assessment of its performance in each scenario. The results showed an average success rate of 85%, demonstrating the system's capability to fulfill user requests satisfactorily. For more extensive results, please visit our project page: <a href="https://www.Github.com/blabladd" target="_blank">Github</a>
        </div>
    </div>
</div>

---
## Request : Move forward avoiding obstacles
![Test1](/static/image/test1.gif)
![Test2](/static/image/test2.gif)
![Test3](/static/image/test3.gif)
![Test4](/static/image/test4.gif)

---
## Request : Turn 360 degree

![Test-360 1](/static/image/Request-turn3601.gif)
![Test-360 2](/static/image/Request-turn3602.gif)
![Test-360 3](/static/image/Request-turn3603.gif)
![Test-360 4](/static/image/Request-turn3604.gif)

---

---
## Request : Move around and find out where the refrigerator is
![Test-r10](/static/image/Request-refrigerator1.gif)

![Test-r20](/static/image/Request-refrigerator2.gif)

![Test-r30](/static/image/Request-refrigerator3.gif)

![Test-r40](/static/image/Request-refrigerator4.gif)

---





















## Background
The paper "On Computable Numbers, with an Application to the Entscheidungsproblem" was published by Alan Turing in 1936. In this groundbreaking paper, Turing introduced the concept of a universal computing machine, now known as the Turing machine.

## Objective
Turing's main objective in this paper was to investigate the notion of computability and its relation to the Entscheidungsproblem (the decision problem), which is concerned with determining whether a given mathematical statement is provable or not.


## Key Ideas
1. Turing first presented the concept of a "computable number," which refers to a number that can be computed by an algorithm or a definite step-by-step process.
2. He introduced the notion of a Turing machine, an abstract computational device consisting of an infinite tape divided into cells and a read-write head. The machine can read and write symbols on the tape, move the head left or right, and transition between states based on a set of rules.
3. Turing demonstrated that the set of computable numbers is enumerable, meaning it can be listed in a systematic way, even though it is not necessarily countable.
4. He proved the existence of non-computable numbers, which cannot be computed by any Turing machine.
5. Turing showed that the Entscheidungsproblem is undecidable, meaning there is no algorithm that can determine, for any given mathematical statement, whether it is provable or not.

![Turing Machine](/static/image/Turing_machine.png)

*Figure 1: A representation of a Turing Machine. Source: [Wiki](https://en.wikipedia.org/wiki/Turing_machine).*

## Table: Comparison of Computable and Non-Computable Numbers

| Computable Numbers | Non-Computable Numbers |
|-------------------|-----------------------|
| Rational numbers, e.g., 1/2, 3/4 | Transcendental numbers, e.g., π, e |
| Algebraic numbers, e.g., √2, ∛3 | Non-algebraic numbers, e.g., √2 + √3 |
| Numbers with finite decimal representations | Numbers with infinite, non-repeating decimal representations |

He used the concept of a universal Turing machine to prove that the set of computable functions is recursively enumerable, meaning it can be listed by an algorithm.

## Significance
Turing's paper laid the foundation for the theory of computation and had a profound impact on the development of computer science. The Turing machine became a fundamental concept in theoretical computer science, serving as a theoretical model for studying the limits and capabilities of computation. Turing's work also influenced the development of programming languages, algorithms, and the design of modern computers.

## Citation
```
@article{turing1936computable,
  title={On computable numbers, with an application to the Entscheidungsproblem},
  author={Turing, Alan Mathison},
  journal={Journal of Mathematics},
  volume={58},
  number={345-363},
  pages={5},
  year={1936}
}
```
