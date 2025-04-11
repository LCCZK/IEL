# 25-02-08 Evaluate solutions

## Description

I had a commitee meeting with the team today and I presented [my analysis](25-02-05%20Analysing_Rowen's_solution.md) on `System_monitor` during the meeting. The commitee had discussion about whether we want to goahead and implement the changes in each team in order to get `System_monitor` to work. We came to the conclusion that we should implement a temporary solution instead. This is because we do not think we will be able to get the changes done in time for competition and also none of the solutions to bridge ROS1 and ROS2 are well tested and will very likely cause performance drop and if we code the node from the scrach for ROS2, we will not be able to get it done in time befor competition. We then design a solution togeather as a team which will also tackals the Lidar issue we currently facing but less generic for other `sensor faliure` issues.

- --> condensed ver?

    Going to the meeting I thought I have found the best soultion to the `sensor failure` because using `system monitor` node would prevent for all sensor failure reather than just Lidar, the one we currently facing. However I have ignored the fact that I will not be able to get it done before FSUK25, yet we are in need of a solution to deal with what we are actually facing. We then design a solution togeather as a team which will tackals the `Lidar issue` we currently facing but less generic for other `sensor faliure` issues.

## Feelings

I am happy that other members was able to point out the impracticality of `system monitor` and also dispointted at myself was not able to come up with this solution at the start.

## Evaluation

The thing did not went well was that `system monitor` was not the solution we were looking  for as i thought initially.

The things went well were the fect that other members pointed out the issue with `system monitor` which prevents me for wasting my time on sothing won't get deliivered before comp. Also we were able to design a solution very effeciently.

## Analysis

I think when I approch the topic of `sensor faliure` I was asking more of the question that "what will be a good solution to this problem" but I should also be asking "What will be a solution we need" hence althought `system monitor` by it self is a good solution but it is not sutable for the issue we are currently facing.

Committee meeting is vewry useful, I was able to hear openion form different teams

## Conclusions

While it is important to have a "perfect" solution to an issue, but if the  solution is addressing an issue with high priority, temporary solution should be implemented instead.

## Action plan

- Improve my problem solving workflow:
  1. Identify the issue
     - What is the issue?
     - How does the issue expressing itself?
     - How severe it is?

  2. Analysis the issue
     - what is expected behaviour?
     - which component is at fault?
  
  3. What we need for the solution?
     - Deadlines
     - What the solution should change in the current bahaviour?
     - What the solution should not change in the current bahaviour?  

  4. How do we implemente it
  5. implement it
  6. Identify future work
     - What is the solution solving?
     - What is the solution not solving?
     - What can we built on top of it ?

- Suggest more committee meetings in the future.
- Use labaling system to remind myself when putting togeather a solution.![label](img/labeling_system.png)
