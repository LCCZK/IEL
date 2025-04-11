# 24-10-01 Identify scope of the issue 1

## What I have done

- Understanding the scope of the issue:
  - It was clear to me that the problem of Sensor failure originated from our Lidar will sometimes stop sending signals when the car is running, and it resulted in the car running off the racing track during FSUK24.
  - However, our software stack consists of many components, ehich can be roughly divided into 4 [Software stacks](/technical/software_stacks.md). So, I wanted to pinpoint the components that are affected by this issue.

- Interview new members for EUFS:
  - In the past month, I have been conducting interviews to recruit new members for the Localisation and Mapping team in EUFS.
  
## Reflection

- The structure of our code was not clearly documented, and since I have only been working with the `L&M` team, I am having a very difficult time understanding the scope of the issue in other components.
- The team was not introduced properly, applicants applied without knowing what Localisation do. Potentially caused the reduce in number of applicants when compared to previous years.
  
## What am I going to do?

- Keep going, and talk to other team leads more frequently and improve the documentation in future.
- We have missed the opportunity for recruiting this year, but I am planning to add "team-lead should introduce their team rather than just letting one person introduce all the teams" into my handover note to the next team lead.
- I need to give new members a presentation of our team structure when they join, and given the experience I am having when trying to understand our software structure, i need to improve our current documentation.
