# 24-10-09 Identify scope of the issue 2

## What I have done

- Understanding the scope of the issue:
  - Conversation with `Perception` team lead, we talked about how `sensor failure` affects perception:
    1. Component `lidar_grid` stop receives `pointCloud` input.
    2. `lidar_grid` output frequency drops below the critical level.
    3. Object detection with the `camera` alone is not nearly as accurate as using `lidar`.
  - Meeting with Alex, the previous `L&M` team lead, we talked about how `sensor failure` affects Localisation and Mapping:
    1. Components `SLAM` and `Cone_Buffer` stop receive `lidar_grid/cones` inputs
    2. Both components are not using `Camera/cones` hence, the components were not able to produce `local_map` or `global_map` of the environment.
  - Conversation with `P&C` team lead:
    1. The component `Roberto_Planner` could not produce a path plan without a `map`.

- On-boarding new members:
  - Welcome new members to our team.
  - Introduce our team again as [previously](24-10-01%20Identify_scope_of_the_issue_1.md) mentioned, and I made the following diagram to showcase our team's software structure.
   ![localisation_diagram](/evidence/localisation_diagram.png)

## Reflection

- Conversation with team leads during the team meeting was very brief as we all have our own team members to take care of, and a lot of my questions were left unanswered.
- I think I did a good job with making the structure diagram; new team members said they understood different components more clearly, and even some of the senior members found it useful and cleared up some confusion they had previously.  
- While I was making the diagram, I also identified some of the improvements we can make in the future.

## What am I going to do?

- In the future, I will try to arrange proper meetings with team leads outside of the general Tuesday and Thursday meetings, so I can have more time to ask my questions.
- Try to recommend other team-leads also make diagrams like this, it will be beneficial to all team members, and help with knowledge transfer when we leave the society.
