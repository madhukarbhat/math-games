# math-games
A collection of command-line games to challenge number skills of children and the interested.

## Multiply
The perl code multiply.pl prompts a series of multiplications to be performed mentally within a timeout. There are three levels of difficulty to challenge users with different skill levels. Usage:

```xterm
% ./multiply.pl
Usage:
    ./multiply.pl <1|2|3|4> <easy|normal|challenging>

<1|2|3>: This is the round number. The round completes once all the
       multiplication questions are asked.

 - Round 1: In round 1, multiplication tables from 2 to 6 will be
   asked in random sequence.

 - Round 2: In round 2, multiplication tables from 6 to 9 will be
   asked in random sequence.

 - Round 3: In round 3, multiplication tables from 9 to 14 will be
   asked in random sequence.

 - Round 4: In round 4, multiplication tables from 14 to 19 will be
   asked in random sequence.

<easy|normal|challenging>: This determines the time available for a
single question.

 - easy        : Question must be answered in roughly 10 seconds.
 - normal      : Question must be answered in roughly 6 seconds.
 - challenging : Question must be answered in roughly 4 seconds.

%
```

