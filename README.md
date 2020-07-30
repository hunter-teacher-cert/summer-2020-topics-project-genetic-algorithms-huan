# Evolutionary/Genetic Algorithms 
# Team Members
1. Huan Wang


# Instructions

## Context
These lessons were designed specifically for a biology-centric classroom that is supplemented with CS principles in a middle school setting. Therefore, its lofty goal is to simultaneously elevate understanding of biological evolution and computer science through comparison and contrast between biological phenomena and its analogues. That said, even if this kind of lesson doesn't fit your classroom, the resources posted for learning about genetic algorithms, especially the first 2, should give you a good foundation for designing your own lessons.

The timeline of the eventual lessons would stretch across units, with the chromosome analogue being introduced before December in conjunction with the heredity unit, and the rest of the genetic algorithm presented 2 units later (around February) when teaching about evolution.

With regards to the language chosen, never did I think I would appreciate Java, but trying to implement a genetic algorithm in Scratch did make me understand how useful object-oriented proramming can be. 


## Educator Resources for Learning about Genetic Algorithms
* https://natureofcode.com/book/chapter-9-the-evolution-of-code/ (This chapter is a great primer on genetic algorithms)
* https://www.youtube.com/watch?v=9zfeTw-uFCw&feature=emb_logo (This is the first of an extensive set of videos of live-coded genetic algorithms in JavaScript; it is the YouTube series version of the book above)
* http://boxcar2d.com/about.html (explains algorithm for orignal Flash boxcar2d, which you can still open in 2020 by allowing Flash in your browser settings)
* http://moe.stuy.edu/~dw/boxcardw/ (to get around Flash issues, you can alternatively play around with this version hosted by Stuyvesant)
* https://blog.otoro.net/2017/10/29/visual-evolution-strategies/ (Some maths for those so-inclined, and also useful visualizations to help illustrate difference between basic genetic algorithms and evolution strategies, as well as more complex hybrid algorithms) 
* https://www.ceas3.uc.edu/ret/archive/2018/ret/docs/readings/Project%203/2018RET_ReadingMaterial_Introduction%20to%20Genetic%20Algorithms.pdf (If you are ready to get deep in the weeds of the historical "evolution" of the different branches of evolutionary algorithms: genetic algorithms and evolutionary strategies are the focus. Honestly, after reading tons of different opinions on what distinguishes them, I'm still not sure what to think.)
* https://pdfs.semanticscholar.org/153e/8bdb5b57c9606d40c09f685372a5c9dcdc9e.pdf?_ga=2.108973510.55027939.1596109018-341954781.1596109018 (aircraft engineering implementation)
* https://www.researchgate.net/profile/Vittorio_Maniezzo/publication/2253354_A_Genetic_Algorithm_To_Solve_The_Timetable_Problem/links/0fcfd50ff95b8c862d000000.pdf (school timetabling implementation)
https://www.geeksforgeeks.org/traveling-salesman-problem-using-genetic-algorithm/ (traveling salesman implementation, though the Shiffman also has a live coding version that is digestible: https://www.youtube.com/watch?v=M3KTWnTrU_c)

## Educator Resources for Learning Scratch
* https://www.youtube.com/playlist?list=PLSgUBfi51uldLxNsADEYyXoXMuBTuR7om (Playlist tutorial for Scratch)
* https://www.amazon.com/Everything-Kids-Scratch-Coding-Book/dp/1507207972/ (Designed for kids, but useful for adults too)

## Educator Resources for Reviewing Biological Evolution 
* https://www.youtube.com/watch?v=aTftyFboC_M (Natural Selection with classic peppered moths example that is relevant to lesson materials)
* https://www.youtube.com/watch?v=WhFKPaRnTdQ (Population Genetics)

## Lesson Overview
* Teach biological structure of genetic material (cell, nucleus, chromosome, gene, DNA)
* Teach biological genotype/phenotype
* Have students program an analogue to a chromosome in Scratch, leading to discussion on what can be simplified
* Have students explore a simulation of moth evolution
* Teach biological artificial selection and natural selection
* Introduce CS analogue of genetic algorithms
* Have students look under the hood of the moth simulation and comment on it, while identifying genetic algorithm components
* Provide broader context of applications of genetic algorithms

## Lesson Materials

* Chromosome Design Task Template: https://scratch.mit.edu/projects/414758735/editor/

* Version 1 of Moth Evolution Simulation (uses averages of parent color values instead of crossing over): https://scratch.mit.edu/projects/413457430/editor/

* Version 2 of Moth Evolution Simulation, which was a failed and aborted attempt at managing individual chromosomes for Scratch clones as list variables. I would not try this approach with students or yourself for your own sanity. Posted as an example of what not to do: https://scratch.mit.edu/projects/413742155/editor

* Version 3 that manages a chromosome analogue using a global list storing all the genetic information of the entire population (named populationGenome) and includes a random "crossover" point with the potential for mutation during reproduction (also allows you to control chromosome size to see how this parameter can affect performance): https://scratch.mit.edu/projects/414228785/editor

* Presentation Slides: https://docs.google.com/presentation/d/1FrXVjYjByMVlmpGpHO0c_ZG3XEvSFvDgWnJzmA2Di3I/edit?usp=sharing

