# libdate
liveCode library to handle date and time functions

## Usage

To use this library, don't use *string* for date, but just *commas*. 

For example this is **wrong**:

    put "2010,1,1" into temp
    put  libDate_DayNumber(temp)

On the contrary this is **correct**:

    put 2010,1,1 into temp
    put  libDate_DayNumber(temp)

## Installation

You have 2 ways to use it:

1. You can copy the the content of **libdate.livecodescript** from line 2 in mainstack script of your program
2. Or you can just copy the **libdate.livecodescript** file and use this code:
```
on PreOpenStack
   start using "libdae.livecodescript
End PreOpenStack
```
