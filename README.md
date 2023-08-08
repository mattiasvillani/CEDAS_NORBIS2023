## CEDAS-NORBIS Summer School 2023 :cloud_with_rain:

This is material is for my talk at the CEDAS-NORBIS Summer School 2023, mainly my slides, the Julia Turing.jl code that I showed in my talk, and some links to resources.

## Slides :man_teacher:
Here are the [slides](https://github.com/mattiasvillani/CEDAS_NORBIS2023/blob/raw/CEDASBergen2023Villani.pdf) from my talk.

## Further reading :books:

Some good Bayesian textbooks (there are many more!):
- Gelman et al (2013). [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)
- Bishop (2006). [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/people/cmbishop/#!prml-book)
- McElreath (2022).  [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)
- Bernardo and Smith (1994). [Bayesian Theory](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470316870)

## My own materials :bearded_person:
- [Bayesian Learning - a gentle introduction](https://mattiasvillani.com/BayesianLearningBook/). Book in progress.
- [Bayesian Learning course](https://github.com/mattiasvillani/BayesLearnCourse) - slides, computer labs and exams.
- [Advanced Bayesian Learning course](https://github.com/mattiasvillani/AdvBayesLearnCourse) - slides and computer labs.
- [Bayesian Learning - Observable Javascript widgets](https://observablehq.com/collection/@mattiasvillani/bayesian-learning).
[Turing.jl tutorials](https://turinglang.org/dev/tutorials/)

## Julia/Turing.jl code

The file [JuliaCode.zip]() contains the following files:
- **iidnormalturing.jl** for the iid normal model with both parameters unknown.
- **poissonregturing.jl** for the Poisson regression model, including HMC and Variational Inference for that model. Also the negative binomial regression extension is in that code.

Here is what you need to do in order to run the code:
- [Download Julia](https://julialang.org/downloads/) and install it. I used version 1.9.2. 
- Download my [JuliaCode.zip]() with the code and extract it to a folder and open a terminal in that folder.
- Start Julia by typing `julia` in the terminal.
- In Julia, type `]` and ENTER to enter the package manager. The prompt should change to something with `pkg>`.
- activate the environment by typing `activate .` and ENTER. 
- Instantiate the environment with all dependencies by typing `instantiate` and ENTER.
- Press BACKSPACE to exit the package manager.
- Type for example `include("iidnormalturing.jl")` and ENTER to run the code. After the sampling, a plot should appear.

If you get serious with Julia and want to use it for your own work, I recommend that you use an IDE such as [VS Code](https://www.julia-vscode.org/) with the [Julia extension](https://www.julia-vscode.org/docs/stable/).