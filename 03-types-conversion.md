---
layout: lesson
subtitle: Data Types and Type Conversion
---
> ## Learning Objectives
>
> * Learner will explain key differences between integers and floating point numbers.
> * Learner will explain key differences between numbers and character strings.
> * Learner will use built-in functions to convert between integers, floating point numbers, and strings.
{: .objectives}

FIXME: lesson content.

> ## Choose a Type
>
> What type of value (integer, floating point number, or character string)
> would you use to represent each of the following?
>
> 1. Number of days since the start of the year.
> 2. Time elapsed since the start of the year.
> 3. Serial number of a piece of lab equipment.
> 4. A lab specimen's age.
> 5. Current population of a city.
> 6. Average population of a city over time.
{: .challenge}

> ## Division Types
>
> The `//` operator returns the whole-number result of division,
> while the '%' operator returns the remainder from division:
>
> ~~~
> print('5 // 3:', 5//3)
> print('5 % 3:', 5//3)
> ~~~
> {: .python}
>
> ~~~
> 5 // 3: 1
> 5 % 3: 2
> ~~~
> {: .output}
>
> If `num_subjects` is the number of subjects taking part in a study,
> and `num_per_survey` is the number that can take part in a single survey,
> write an expression that calculates the number of surveys needed
> to reach everyone once.
{: .challenge}

> ## Strings to Numbers
>
> `float` will convert a string to a floating point number,
> and `int` will convert a floating point number to an integer:
>
> ~~~
> print("string to float:", float("3.4"))
> print("float to int:", int(3.4))
> ~~~
> {: .python}
>
> ~~~
> 3.4
> 3
> ~~~
> {: .output}
>
> Given that,
> what do you expect this program to do?
> What does it actually do?
> Why do you think it does that?
>
> ~~~
> print("fractional string to int:", int("3.4"))
> ~~~
> {: .python}
{: .challenge}
