# Event-B Rodin `integral` function

This function allows you to sum all the elements in the range of a function in Rodin. \
It is based on verified recursive sum algorithm and proven automatically in Rodin with ProB.

This can also be used as an inspiration to do some more advanced things with Event-B Rodin.

## Usage

Simply imports the files from /integralFunction into your project and add `integral_ctx` to the clause `SEES` of the machine in which you need it.

You can then use the function as any other function: `integral(S)`
For animations, you can mute the first line `integral : (INT --> INT) --> INT &` into the comment if you don't want to see an error.

## Rodin's style reference
integral -- integral  -- Sum of each image of a function INT --> INT \

| | |
| -:| :- |
| __Description__ | integral(S) is an expression that gives the discrete integral of the given function.|
|__Definition__ | integral(S) = s_1 + s_2 + ... + s_n where s_n are integers elements of the range of S.
|__Types__ | integral(S) is an integer (:INT -or Z-) with S being a INT --> INT (function between integers)
|__WD__ | ?

## Compatibility

Made with Rodin Platform Version: 3.4.0-6980ca1 on Windows 10 amd64.

## Contribution

Any contribution is welcome !
