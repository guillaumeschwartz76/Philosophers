# Philosophers

The aim of this project is to teach us the basics of threading process

## Overview

There are 1 or more philosophers sitting around a table with a large bowl of spaghetti in the middle.
They must alternately eat, think and sleep.
There are as many forks around the table as there are philosophers.
To eat, they must take two forks from the table.
When they've finished eating, they put the forks back on the table and start to sleep, then think and start again.
The simulation ends when a philosopher die.

Passed as parameter, a time_to_die : it start at the beginning of the last meal and if they didn't eating before the end
of that, time a philosopher die.

## Installing and Compiling Philosophers

Clone the repository

```shell
https://github.com/guillaumeschwartz76/Philosophers.git
```

You can go to the directory for compilation and can do ```make```.

## Executing Philosophers

The program take the following arguments:

 *<number_of_philosophers> : maximum 200 philosophers
 *<time_to_die> : in milliseconds
 *<time_to_eat> : in milliseconds
 *<time_to_sleep> : in milliseconds
 *<[number_of_times_each_philosopher_must_eat]> : an optional argument
 the is the number of meal by philosopher that the simulation need to stop.

for example:
```shell
./philo 4 800 200 200 7
```


