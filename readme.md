# Objectives
This course teaches the basic principles of Model-Driven Engineering - MDE. Students should learn:

1. The fundamental concepts of MDE, its role in a critical system’s development and safety assessment processes, and the importance of having precise models in this context.
2. How to identify and write functional and non-functional requirements for critical systems, using the best practices and ensuring that they respect the expected quality standards (verifiable, traceable, unambiguous, correct, etc.)
3. Formal models capable of precisely capturing different aspects of UML diagrams, such as labelled transition systems and different logical systems.
4. Understand domain specific standards common in critical systems’ development, and apply them when using an MDE approach; and
5. How to use tools that support requirement specification and management, system modelling and its safety assessment, and the formal models described.


# Syllabus

<!-- 1. Fundamental concepts and principles of MDE, and its specificities when applied to critical systems.
2. Fundamentals of requirement engineering.
3. UML as software and system modelling languages for enabling critical systems MDE.
4. Formal specification and model checking of critical systems: principles and tools.
5. Software development standards for critical systems.
6. Case studies.
 -->
<!-- 6. Fundamentals of testing and fault analysis, and its usage in MDE -->


- High-level overview or requirements and associated processes
- Mathematical Preliminaries
  + Basic mathematical notations
  + Set theory
  + PropositionalLogic
    * Syntax, semantics, and reasoning
  + First Order Logic
    * Syntax, semantics, and reasoning
  + The Z3 automatic theorem prover
    * Rise4fun interface: get acquainted with the tool
    * Python API: automating search for solutions
- Behavioural modelling
  + Single component
    * State diagrams and Flow charts
    * Formal modelling: Automata, Process Algebra
  + Many components
    * Communication diagrams and Sequence
  diagrams
    * Formal modelling: Process algebra with interactions
  + Equivalences
    * (Bi)similarity
    * Realisability
  + Verification
    * Verification of requirements
    * Formal modelling: modal logics
    * Tools: model checking with mCRL2


# Material

### Slides


<!--
- [Introduction to MDE and SysML; Visual Paradigm]() (Lecture 1)
- [SysML: Structural Diagrams]() (Lecture 2)
- ...
 -->

<ul>
  <li><a href="" class="hide">
    Introduction to MDE and Requirement engineering; Structural diagrams (Week 1)
  </a></li><li><a class="hide" href="">
    Logics for states: Modelling requirements and using SMT solvers (Week 2-3)
  </a></li><li class="hide"><a class="hide" href="slides/3-modelling.pdf">
    <div class="hide">Modelling behaviour: Automata and Process Algebra (Week 4-5)</div>
  </a></li><li><a class="hide" href="slides/4-equivalence.pdf">
    Analysing behaviour: Equivalence of systems; Realisability (Week 6-7)
  </a></li><li><a class="hide" href="slides/5-modal-logic.pdf">
    Logics for behaviour: Modal logics; Model-Checking (Week 8-9)
  </a></li><li><a class="hide" href="slides/6-mcrl2.pdf">
    Modelling and verification in mCRL2 (Week 2-9)
   </a></li>
   <!--<li><a class="hide" href="">
    Standards and use-cases in Critical Systems (Lecture 9-10)
  </a></li> -->

</ul>



### Assignments
<ul>
  <li><a href="" class="hide">A1: Modelling Requirements (individual)</a></li>
  <li><a href="assignments/a2-modelling.pdf" class="hide">A2: Modelling Behaviour (group)</a></li>
  <li><a href="assignments/a3-verification.pdf" class="hide">A3: Analysing Behaviour (group)</a></li>
</ul>


### Useful links

<!-- - [Visual Paradigm](https://www.visual-paradigm.com) -->
- [mCRL2](https://www.mcrl2.org)
- [Z3 in Python](https://ericpony.github.io/z3py-tutorial/guide-examples.htm)


### Bibliography
<!-- - [__SysML Distilled: A Brief Guide (2013)__](https://www.amazon.com/SysML-Distilled-Systems-Modeling-Language/dp/0321927869),
  by Lenny Delligatti
  [![link to pdf](assets/img/PDF.png)](https://app.ute.edu.ec/content/4915-114-4-1-6-19/SysML%20Distilled_%20A%20Brief%20Guide%20-%20Lenny%20Delligatti.pdf)
 -->

- [__Reactive Systems: Modelling, Specification and Verification (2007)__](http://www.cambridge.org/us/academic/subjects/computer-science/programming-languages-and-applied-logic/reactive-systems-modelling-specification-and-verification"),
  by Luca Aceto et al.
  [![link to pdf](assets/img/PDF.png)](http://www.cs.ioc.ee/yik/schools/win2007/ingolfsdottir/sv-book-part1.pdf)

- [__Modeling and Analysis of Communicating Systems (2014)__](https://mitpress.mit.edu/books/modeling-and-analysis-communicating-systems),
  by Jan Friso Groote and Mohammad Reza Mousavi
  [![link to pdf](assets/img/PDF.png)](https://www.researchgate.net/publication/228689169_Modelling_and_analysis_of_communicating_systems)


# Pragmatics

<!-- ### Remote and physical lectures

[To be confirmed:] This course unit consists of 11 weeks, each with 2h of theoretical and 3h of practical lectures. Due to the current pandemics, this course unit will have both remote and physical lectures:
 - all _theoretical lectures_ will be remote, via a video-conference tool (e.g., Teams or Zoom) ; and
 - every 2nd week the _practical lectures_ will alternate between being remote and physical, and in the last week there will be a 1.5h practical physical lecture.
 -->

### Evaluation

 * __Final mark__ = Individual Exercises (10%) + Assignments (60%) + Literature Review (30%)

__Individual Exercises__ are to be developed individually. These exercises are included in the lecture slides, some of which will be done during lessons. Marks will reflect mainly the effort, and the feedback will be provided during the practical lessons.

__Assignments__ are either individual (A1) or to be developed by teams of 4 students (A2 and A3). Each team has a dedicated `git` repository that will contain the software artefacts and a report for each assignment. Most work is expected to be done within the practical lessons. Feedback will be provided within 2 weeks after each submission deadline, and marked only at the end of the unit.

__Literature Review__ is to be developed by the same groups of 4 students, and consists of a written _critical_ review of maximum 4 pages using a LaTeX template that will be made available.
The review will be presented in an oral presentation, and the review will be partial evaluated by peers.

<!-- ### Evaluation

 * __Final mark__ = Group Project (70%) + Literature Review (30%)

__Group Project__ is developed by teams of 4 students, submitted together with a report using a dedicated `git` repository, divided into 3 parts (to be confirmed).

__Literature Review__ is developed by the same team, and consists of a written _critical_ review of maximum 4 pages using a LaTeX template that will be made available.

Both the project and the review will be presented in an oral presentation, and the review will be partial evaluated by peers.
 -->


### Deadlines

__Individual exercises__ must be submitted until Sunday @ 23:59 of the following week of being shown during lessons. For example, all exercises presented in the slides used in the week 8 Nov - 12 Nov must be submitted until Sunday 21 Nov.

  - __Slides [`3-behaviour.pdf`](slides/3-behaviour.pdf), slides 1 - TBD:__ 28 Nov @ 23:59 (Sunday)
  - ...


__Assignments__ have the following deadlines, that may still suffer changes.

  - __A1:__ tbd
  - __A2:__ tbd
  - __A3:__ tbd



### Lecturers

- [_David Pereira_](http://www.cister.isep.ipp.pt/people/david_pereira/),
  `drp arroba isep ponto ipp ponto pt`
- [_José Proença_](https://jose.proenca.org),
  `pro arroba isep ponto ipp ponto pt`



 We will use a team in Microsoft Teams where all questions regarding this course unit should be placed, and where we can schedule virtual meetings if needed.

