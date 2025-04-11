# LO1: Analysis

I am able to demonstrate how I have actively developed my critical understanding of the topic of my SLICC.

All SLICC Learning Outcomes will focus on analysis which is the ability to break something down into separate aspects to increase understanding. However, Learning Outcome 1 has a primary focus on this and the topic you have chosen to investigate throughout your experience.

## Final Reflective Report

<!-- ### What
- In your own words, what are you focusing on for this learning outcome? Make this as specific as possible. How does this differ from what you expected in your Proposal?
- What have you done since your Proposal to progress this learning outcome? 
- What unexpected changes, challenges and/or problems have you encountered?
### So what
- What are the main things you have learned from your experiences in relation to this learning outcome?
- What experiences contributed the most to this learning?
- How have you learned from anything that was unexpected, challenging, or difficult?
### Now what 
- What are your next steps for this learning outcome – whether during your SLICC or beyond?
- How could what you have learned be useful in other parts of your life (academic, personal, and professional), now and in the future? -->

When I first proposed my SLICC topic, it focused on building a software solution to respond to sensor failure for autonomous driving systems. I had the idea that the impact of sensor failure could be completely avoided by simply implementing a fail-safe mechanism in the software. My initial opinion was shaped by a limited understanding of sensor failure, the [EUFS software stack](https://github.com/LCCZK/IEL/blob/main/technical/software_stacks.md), and the [chain effect on the software components](https://github.com/LCCZK/IEL/blob/main/blogs/24-10-09%20Identify_scope_of_the_issue_2.md) that would be caused by sensor failure. I thought that I could implement algorithms tested by the automobile industry directly into the EUFS autonomous driving system to compensate for the missing sensor input.
 
In the early stage of my investigation on the topic, I primarily read academic papers, studied the software structure and designed and implemented a solution. However, the [first solution](https://github.com/LCCZK/IEL/blob/main/blogs/24-11-30%20Coding_the_solution.md) I developed did not work effectively due to my [oversight of a conflict between algorithms](https://github.com/LCCZK/IEL/blob/main/blogs/25-01-15%20Testing_the_solution.md); this led to the development of a [second solution](), which [improved the software's behaviour]() when encountering Lidar failure, but still, it was not a generic solution to sensor failure like I initially hoped.

Although a temporary solution was developed at the end of my SLECC for the EUFS software team, I realised that developing a generic solution for sensor failure was far more complex than I had anticipated. Through a critical engagement with [reading research papers, investigating study cases](https://github.com/LCCZK/IEL/blob/main/blogs/24-11-05%20Analysis_and_discuss_potential_solutions.md) and developing solutions, I discovered that sensor failure involves much more than what I expected — ranging from the technical side, such as system communication, limitations of sensor fusion algorithm, fault detection, and the integration challenges posed by the existing software architecture, and non-technical concerns such as metric to measure effectiveness and ethical issues. Therefore, improving software algorithms will not be enough to provide a generic solution for systems to react to sensor failure.

The first solution I developed turned out to be ineffective was something I did not expect, but also a good demonstration of the integration [challenges between the existing system and solutions](https://github.com/LCCZK/IEL/blob/main/blogs/25-01-15%20Testing_the_solution.md). I learnt from this experience that when working with a complex system like the autonomous driving software in EUFS, a simple change in a component could cause system conflicts anywhere, and it is almost impossible to predict unless I have a deep understanding of the system structure, so other than efficient implementation; unit tests, integration tests and clear documentation are also crucial in software developing, and even if a solution is well tested by the industry and works well on paper, it does not mean it is a suitable solution in every system.

The main takeaway from investigating my topic is that sometimes I am too idealistic when trying to apply what I learnt from lectures or papers without realising real-world engineering requires more case-specific considerations. I will need to obtain more experience by putting my knowledge into practice more consistently. After the end of my SLICC, I would like to learn more about how autonomous vehicles implement their localisation and mapping algorithms to anticipate sensor failure to keep the passengers safe when autopilot is enabled in real-world traffic, so I have applied to an internship with the autonomous vehicle research group in the school of informatics. On top of that, I also want to study the ethical side of sensor failure to answer questions such as the classic "trolley problem" but with an unpredictable outcome due to sensor failure.

