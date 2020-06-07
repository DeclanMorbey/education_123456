# How To Git Good
Do you want to become a better version of yourself?
This should contain education materials used throughout the course of a degree in physics.
In order to create this comprehensive course, the material should be designed to the same structure. 
It should all be written in a Latex format, with a title page, contents page, and an abstract overview with what will be covered.  

# Subject Overviews
## Classical Mechanics
Classical mechanics describes the motion of macroscopic objects, 
from projectiles to parts of machinery, and astronomical objects, 
such as spacecraft, planets, stars and galaxies [Wiki](https://en.wikipedia.org/wiki/Classical_mechanics).

This highly broad topic was built upon Newtons methods through various analytical techniques such as Lagrangian, 
Hamiltonian, and Hamilton-Jacobi formulations.
It involves the observations of macroscopic systems using equations of motion 
(such as translational, rotational, oscillatory and circular) from these formulations.
Traditionally, Classical Mechanics brought about the introduction to the concepts of space, time, 
mass, force, momentum, torque, and angular momentum to solve the motion of bodies. 

<p align="center">
![Alt Text](https://i.pinimg.com/originals/e6/bc/26/e6bc26c7a2617dafea44379d5d236b97.gif)
</p>

<p align="center">
  <img src="https://i.pinimg.com/originals/e6/bc/26/e6bc26c7a2617dafea44379d5d236b97.gif"/>
</p>

## Quantum Mechanics
## Relativistic Mechanics
## Quantum Field Theory
## Thermodynamics and Statistical Mechanics 
## Electromagnetism
## Nuclear Physics
## Particle Physics
## Mathematical Methods
## Cosmology
## Condensed Matter Physics
## Semiconductor Device Physics

## August Exams - Declan
### Quantum Field Theory
### Advanced Particle Physics
### Quantum Information Processing
### Atomic and Quantum Physics III
### Laser Physics
### Nano Biophotonics


# How to contribute in an orderly fashion 

In short to add to the knowledge:

1. Create your own branch (eg. `user_how_to_git_good`, `user_subject`).
2. Decide on the category of the sub-subject, or create a new subject folder.
3. Create a `subsubject.tex` file with your desired sub-subject.
4. Add this sub-subject to the `main_subject.tex` file using `\input{filename}` feature in Latex.

## How do the files compile?
Compile the `tex` file with the same name as the folder: 
1. Compile `Classical_Mechanics.tex` with `pdflatex`. 
2. Use `biber` to compile the biliography.
3. Add topics to this main document, use the `\input{foo.tex}`.

The purpose of compiling these files this way is so that upon compilation,
people are able to pick and choose what subjects to include in the output `pdf`.
First remember that this is meant to be an incredible resource for both yourself and others.
As with any notes, you want to be able to look back and understand why you wrote notes on a topic. 
It will be of great importance to ask yourself "What question is this answering?"
and "What is the purpose of knowing this material?" - this may help you learn it more effectively!
It may also be handy to create beamer slides at any point, 
where you wish to present the information to an audience or teach.

