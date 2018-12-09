+++
title = "Course Overview"
date = "8 Jan 2019"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
type = "page"
hidden = false
weight = 01105  # wwdpp
+++


{{<revealjs theme="psu" transition="slide" controls="true" progress="true" history="false" center="false" loop="false" pdfSeparateFragments="false" showNotes="true" >}}
## Welcome
Penn State Astro 528 <br>
High-Performance Scientific Computing for Astrophysics <br>
Eric Ford


---
## Course goals

Enhance your skills for scientific computing
- Increase your productivity
   + Choose right tool for right task
   + Reduce time debugging
   + Improve reproducibility
   + Increase impact of your software
- Enable you to
   + Analyze "Big Data"
   + Increase resolution of simulations
   + Include more complex physics

---
<!-- .slide: data-background="#093162" -->
### Course outline

- Software Development Practices
- Writing efficient serial code
- Parallelizing code efficiently
___
### Software Development Practices
- Version control
<!-- .element: class="fragment" -->
- Testing & Continuous Integration
<!-- .element: class="fragment" -->
- Debugging
<!-- .element: class="fragment" -->
- Documenting & Literate Programming
<!-- .element: class="fragment" -->
- Coding standards
<!-- .element: class="fragment" -->
- Reviewing code
<!-- .element: class="fragment" -->
- Reproducibility
<!-- .element: class="fragment" -->
- Workflow
<!-- .element: class="fragment" -->

Note:
Ask what students think of when they hear "software development practices".
___
### Writing efficient serial code
- Processor architectures
- Memeory heirarchy
- Networking
- Programming languages
- Choosing algorithms
- Benchmarking
- Profiling
- Compilzer optimizations
- Optimizing
___
### Parallelizing code efficiently
- Shared-memory
- Distributed-memory
- Accelerators
   + GPUs
   + Intel Phis
- Cloud

Note:
Ask if any students already using parallel codes.  If so, how were they parallelized?
---
### Specific Objectives

- Increase technical knowledge
    + Readings, online lessons & class discussion
- Practice fundamentals on a small scalle
    + Lab/homework exercises
    + Make lots of mistakes quickly & learn from them
    + Make good habits rouine
- Transfer skills into real work environment
    + Class project
    + Apply new skills to your research
    + Build deeper expertise in special topics most relevant to you
    + Share what you learn with the class
___
### Readings, presentation
- Textbooks
   + _Writing Scientific Software: A Guide to Good Style_
   + _ThinkJulia: How to Think like a Computer Scientist_
   + _Introduction to High Performance Computing for Scientists and Engineers_ (optional)
- Online PDFs
- Online tutorials
- Audio?

Note:
Ask students if they like the idea of an audio lesson prior to class.
___
### Class discussions
- Let's learn from each other
- Introductions
   + Name
   + Department (if not Astro)
   + What skill you hope to strengthen through this course
---
<section id="setup">
## Let's get you set up
### Accounts
- [Github](https://github.com)
- [JuliaBox](https://juliabox.com)
- Penn State
- [ICS-ACI](https://ics.psu.edu/computing-services/account-setup/)
- [Travis-CI_.com_](https://travis-ci.com/)

Note: For travis-ci, it's a dot com and not a dot org (in order to link to private github repos with the assignments).
</section>
___
### Get started
For your first lab session, you'll
- Accept invitation for Lesson 1
- View your new repository on [Github](https://github.com)
- Login to where you'll run your Jupyter notebooks (with Julia 1.0 kernel)
   + [JuliaBox](https://juliabox.com)
   + [ICS-ACI Portal](http://portal.aci.ics.psu.edu/)
   + [Install locally](https://julialang.org/downloads) (not for today)
- Clone repo for Lesson 1
- Start working through intro.ipynb
- Ask questions as you go
- Commit your changes to your repo and push them to github
- If/when you're done, create a pull request to merge your work into the original branch.

For this first lab/assignment, there are [more detailed instructions](lessons/how-to-use-aci.md) about doing these using the ICS-ACI Portal.


---

# Questions?
<a href="#/0/0">Jump to start.</a>