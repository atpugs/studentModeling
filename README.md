# Student Modeling for Game-Based Learning Environments
[In collaboration with the IntelliMedia group (https://www.intellimedia.ncsu.edu/about/), under the supervision of Dr. James Lester]

Game-based learning environments have emerged as a promising approach to support student learning by providing immersive and engaging experiences. However, to effectively leverage the potential of these environments, it is important to understand the student's approach to the game-based problem solving and predict their learning outcomes for providing adaptive scaffolding. A promising direction for predicting student learning outcomes and solution paths is gaining insight into students' self-regulatory processes, of which students' natural language written reflection is an integral component. Students’ written reflections can provide insights into their learning process, including their understanding of concepts and approach to solving the game. Prior research has investigated the potential benefits of using students' written reflections in conjunction with their game-trace logs for predicting their post-test score and depth of future reflections using multi-task learning. Previous studies have also demonstrated the potential benefits of using reflections alongside game-trace logs for predicting which goal a student is trying to accomplish next, that will contribute towards solving the overarching problem of the game. These findings suggest that incorporating students' written reflections with their game-trace logs can provide a more comprehensive picture of their learning process and aid in the design of effective game-based learning environments.

Our experiments are conducted on Crystal Island: Lost Investigation (https://projects.intellimedia.ncsu.edu/crystalisland/), a game-based learning for middle school microbiology and literacy. The narrative of the game revolves around the investigation of a mysterious outbreak on a remote island, and the students play the role of a medical field detective tasked with identifying the disease and suggesting an appropriate treatment. 

![image](https://github.com/atpugs/studentModeling/assets/31329834/a9d562b8-9d8c-485b-b0e9-fc61a5fc2b9e)

The game has in-game prompts to encourage students to reflect on their learning in the game and write short natural language responses about their progress in the game and their plan moving ahead. 

<p align="center">
 <img src="https://github.com/atpugs/studentModeling/assets/31329834/19303903-a97a-42bc-a8f0-010654808db5" width="500">
</p>

We use students' game trace logs and their written reflections to model their learning outcomes and in-game goals, with a goal of combining the two prediction tasks in a unified model.

![Screenshot 2023-09-22 at 4 33 10 PM](https://github.com/atpugs/studentModeling/assets/31329834/d1129b74-3d25-49d8-b15b-5709f07e322c)


To learn more about the project and experimental results, please check out our publications:
Gupta, A., Carpenter, D., Min, W., Rowe, J. P., Azevedo, R., & Lester, J. C. (2021). Multimodal Multi-Task Stealth Assessment for Reflection-Enriched Game-Based Learning. In MAIED@ AIED (pp. 93-102). (https://ceur-ws.org/Vol-2902/paper9.pdf)
Gupta, A., Carpenter, D., Min, W., Rowe, J., Azevedo, R., & Lester, J. (2022, October). Enhancing multimodal goal recognition in open-world games with natural language player reflections. In Proceedings of the AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment (Vol. 18, No. 1, pp. 37-44). (https://ojs.aaai.org/index.php/AIIDE/article/download/21945/21714)

Due to confidentiality reasons, dataset is not uploaded in this repository. Please contact authors for more information. 
