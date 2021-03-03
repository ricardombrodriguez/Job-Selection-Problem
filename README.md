# Job Selection Problem

This job selection problem is the first project of the *Algorithms and Data Structures* class, written in the C language.

## Introduction

Given T programming tasks, each one with a starting date, an ending date, and a profit, and given P programmers, the generalized weighted job selection problem asks for the best subset of programming tasks such that:
- the sum of the profits of the programming tasks belonging to the subset is maximized,
- each programming task is done by a single programmer
- each programmer cannot work on more than one task at a time

Under the rules given above a programmer cannot interrupt a programming task to do another programming task; once she/he is commited to a programming task, she/he is busy until that task ends.

## How to compile and run

To compile the program, you need to be inside the *A01/* folder and type the following string in the command line:

```
make job_selection
```

After this, you can now execute the main program by entering the following line:

```
./job_selection (mec. number) (number of programs) (number of programmers) (seed)
```

To simplify our work and to produce data for some graphs, we run the *job_selection_do_all*, a BASH file that allows us to execute all possible combinations of the *job_selection.c* program. It will store the data of each possible combination in a directory. To run this BASH file we give the user permission to execute it and we type:

```
chmod u+x job_selection_do_all
./job_selection_do_all
```

## Authors

- Alexandre Serras
- [João Reis](https://github.com/joaoreis16)
- [Ricardo Rodriguez](https://github.com/ricardombrodriguez)
