# Option
This repository contains useful structures to better express intent in code.

## Option<T>
The main structure is Option<T> which can be used to express possible absence of a value.

## Result<T, E>
Result<T, E> can be used to express result of an execution which may fail.
If execution failed for some reason it should fill E (error) type. If everything is ok, it should fill T (ok) type.
This way you can avoid throwing exceptions and notify client of your code about possible errors.
