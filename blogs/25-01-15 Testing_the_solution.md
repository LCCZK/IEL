# 25-01-15 Testing the solution

## What I have done

- In the meeting yesterday I tested my solution with the help from the perception team lead.
- The solution solves case where the `IMU` and `Lidar` fail at the same time, however, it does not fully resolve the topic I proposed due to:
  - cones observed by sensor are filtered before passed into map_lib, so the maximum association error could not be used to identify when single sensor stop working.
  - It couldn't identify case where sensor failure occurs at the start time, because SLAM map won't have any cones at that time.

## Reflection

- The whole testing process was easier that I previously thought and I could have done it by myself. If i have done the testing earlier I would have found out the solution doesn't work and will have more time to fix it or come up with a new solution. This teaches me do not assume how hard a task is without actually analysing it.
- the reason I thought testing would be hard is because, It involves using packages I have not previously used and due to poor documentation, I did not want to touch it. Which shows we do need to work on to improve our documentation.

## What am I going to do?

- I am going to investigate the `system monitor` solution and give feedback to the perception team on how they should improve their documentation.
- suggest workshop session within the team: At the start of the semester, we decided not to have weekly committee meetings, I think this have led to my lack of understanding on the software structures of other teams.
- As for myself, I need to improve my messaging ability: I am very bad at messaging people online, so I always leave things until i can talk to the people involved face to face. I believe being able to message people over Teams will boost my efficiency while working on projects.
