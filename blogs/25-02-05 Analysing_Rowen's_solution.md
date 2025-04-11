# 25-02-05 Analysing_Rowen's_solution

## Description

[Last week](25-01-30%20Still_investigating_and_found_some_useful_old_code.md) I discovered an project(System-monitor) by our privious member Rowen which address a similar  issue I am trying to address. I decided to have a meeting with the commitee members in a few days to discuss if we should use this solution for FS25 and  develiope upon it.

So I spent this week investigating those code and preparing a presentation for the software commitee to discuss whether we if we should develope on top of it should use this solution.

I identitied the main complication is that that the project was built for ROS1 instead of the ROS2 framwork we are using right now and I found solutions that how we could run it with our ROS2 framwork.
<!-- 
see if the solution would work well with our current stack and came to the conclusions that the project was built for ROS1 instead of the ROS2 framwork we are using right now. 
 
It contain dependencies to other ROS1 packages which nolonger provide in ROS2 but I was able to I dentify some open sourced solutions to bridge nodes run with ROS1 to work with ROS2 nodes.

After that, I had a meeting with other software commitee had a discussion which turned into a debat about whether or not we should run this node during  

Althought there exist some , however none of those solutions are well tested and came with drawbacks. After discussion with other team-leads it was decided this node need to be re-built with the ROS2 framework but we will not be able to get it done in time before FS25 . -->

Also decided to try out the Gibbs' Reflective Cycle this week :)

## Feelings

I am quite happy with what I have achieved this week.

## Evaluation

I was able to realise very quickly that the package was built for ROS1 instead of ROS2 from the comment, because this package actually have good documentation. Then I made the decision to look for work arounds.

Since this is a very comment competability issue, the research for workarounds went very smoot, and I was able to find many useful infomation prettt quickly.

After I found a package to bridge ROS1 and ROS2, I was not able to get the `System-monitor` node to run with our current stack, because there exist some broken dependencies that requires changes to be made in few of the existing nodes.

## Analysis

As mentioned above, the system monitor package contain very detailed documentation (I think this was Rowean's IEL project?) so I could understand the node and its function pretty quickly.

When reading into ROS documentation and furm, because I had a clear objective and i knew what I should be searching for, that massively reduced the time i spent to find relevant infomation.

Since I am preparing these infomation to present is on the committe meeting, I feel more motivated when researching these.

The reason for I was not able to get things to work is because `system monitor` was outdated, and when designing the dependencies in other nodes we did not accomendated the dependancies which `system monitor` will need.

## Conclusions

I learnt that having a well written documentation will help future developer to spend less of their time on unnessary tasks. Having a clear objective and placing deadlines on tasks will boost my productivity significantly.

## Action plan

When I program next time I should learn from the comment style of Rowans's code, compose and update README with useful infomation such as package description, dependancies, expected behaviour, inputs and outputs. And when researching I need to figur out a clear list of objective before researching, and place deadlines.
