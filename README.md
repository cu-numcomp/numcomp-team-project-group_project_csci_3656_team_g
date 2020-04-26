# Team Project: Numerics in Open Source Software

You've found some interesting methods and software during the individual
projects, and still have some open questions.  Now you'll decide as a team what
to focus on and push it to the limit.  You'll design an experiment or comparison
and write it up in the [project notebook](project.ipynb].  It's great if this
strives to answer one of your open questions, but some good strategies include

* Design a convergence or performance test that compares methods in this package
  to some competitors.  Try to present results in a way that helps a user decide
  what package to use for what kind of problem.
  
* Find a way to "break" the software, perhaps by violating some assumptions on
  the inputs.  This could mean exposing instability, such as we've seen with
  `log(1+x)` versus `log1p(x)`, or creating an ill-conditioned problem (like
  polynomial interpolation on evenly spaced points).
  
* Attempt to reproduce a figure from a paper about related methods.  Many
  software packages reference papers for methods, and those papers will usually
  have some comparisons showing why their methods are good.  See if you can
  reproduce their comparison using this software.
  
You're also welcome to design different experiments.  Attempt to describe your
study and present your results in a way that will help a prospective user or an
existing user understand the capability and limitations of the software.

### To complete the assignment:

1. Clone this repository (to your laptop or [Coding CSEL](https://coding.csel.io))
```
    $ git clone https://github.com/cu-numcomp/numcomp-team-project-GROUPNAME
```
   This creates a new directory.

2. Open the Jupyter notebook [project.ipynb](project.ipynb) and write about the project.
   There are some prompts in the notebook, but feel free to modify as you see fit.

3. Commit your changes in the terminal and push
```
    $ cd numcomp-team-project-GROUPNAME
    $ git commit -am done
    $ git push
```

Note that you'll be collaborating with your team members and may need to pull
their changes.  This should give you practice collaborating using Git.

