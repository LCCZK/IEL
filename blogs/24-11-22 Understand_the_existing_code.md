# Understand the existing code

## What I have done

- I spent the past week reading the `map_lib` and `cone_buffer` package. This took much longer than i expected, mainly because:
  - `map_lib` is a package in the localisation team contain all the core logic, it has been around for years and been worked on by many different members, so the package were developed in many different coding style which made it hard to understand
  - variables were named using different arrangement of the words like `cone` `buffer` `c` and `cones`. It is VERY HARD TO READ..........
  - The `map_lib` package were implemented with some advance C++ features such as `concept,` `template` and functions like `std::transform_reduce` and `ternary expressions`.
  - These advance libarary functions could improve the process speed and performance of our code but I have not used these libarary before so i had to spend time on reading documentations.

## Reflection

- I was very frustrated when trying to understand the existing code, and having to ask previous member because of inconsistant coding style. But I do think this is a good training for me to prepare for the industry.
- While researching , I got used to reading the C++ documentation and it gets easier after a while.
- Understanding the advance features in C++ I could use them in my future work to improve the performance.

## What am I going to do?

- I have mostly understand`map_lib` and `cone_buffer`now and will start coding.
- I need to modify some of the variable naming to make them use words that have actual meanings, althought that might make the file longer, but they will be easier to understand.
- Emphasise the importance of follwing coding convensisons sucah as [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html) to my colleagues.
