# What Could Go Wrong - LLM Edition

This repository hosts the files used for the What Could Go Wrong? digital card game. Nikolas Martelaro and Wendy Ju developed and presented the game at a Workshop at AutoUI 2020. The game was then modified by Nik and his team at CMU to be more generalized for AI-based systems.

The version here presents a further iteration on the game. In this iteration, prompts focus on applications of large language models. Example applications are drawn from two sources: Kaddour et al.(2023) and FlowGPT.com. The list of potential ethical issues stems from the AI4People framework (Floridi et al., 2021) and a business ethics enumeration (Baker and Comer, 2012). Besides, this iteration of the game includes a LaTeX template, which can be used to convert the digital card game into a physical card game. 

The digital card game can be loaded into and played on PlayingCards.io. Custom cards can be added using the `csv` files for `prompts` and `responses`

### References
Baker, S.D. and Comer, D.R. (2012) ‘“Business Ethics Everywhere”: An Experiential Exercise to Develop Students’ Ability to Identify and Respond to Ethical Issues in Business’, Journal of Management Education, 36(1), pp. 95–125. Available at: https://doi.org/10.1177/1052562911408071.

Floridi, L. et al. (2021) ‘An Ethical Framework for a Good AI Society: Opportunities, Risks, Principles, and Recommendations’, in L. Floridi (ed.) Ethics, Governance, and Policies in Artificial Intelligence. Cham: Springer International Publishing (Philosophical Studies Series), pp. 19–39. Available at: https://doi.org/10.1007/978-3-030-81907-1_3.

Kaddour, J. et al. (2023) ‘Challenges and Applications of Large Language Models’. arXiv. Available at: https://doi.org/10.48550/arXiv.2307.10169.


## Abstract
While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.

## Game Title: "What Could Go Wrong - Online Communities Edition"
Platform:  
The game will be hosted on a web platform or app, allowing players from different locations to participate simultaneously. The platform should support game rooms, chat for discussions, and a system for dealing with cards and points.

Game Setup:  
•	Players join a game room, either publicly available or privately created by a host.
•	Each player is dealt a hand of digital response cards.
•	One player is chosen or volunteers to be the first "Moderator" (similar to the Card Czar in the physical game).

Game Components:  
•	Prompt Cards: Digital cards that present scenarios or challenges related to managing or participating in online communities. These could range from dealing with a wave of negative comments to engaging a passive community.
•	Response Cards: Digital cards offering potential solutions or strategies to the presented challenges. These responses would include actions like implementing new moderation tools, starting community events, or revising community guidelines.

Gameplay Instructions:  
1.	Round Start:  
•	The Moderator draws a prompt card from the digital deck, which is displayed to all players.  
•	Players choose one of their response cards that they believe best addresses the prompt, submitting it anonymously through the platform.  
2.	Selection and Discussion:  
•	The Moderator reviews the submitted response cards and selects the one they find most fitting or effective for the scenario.  
•	The chosen response is revealed to all players, and the player who submitted it is awarded a point.  
•	The platform then facilitates a discussion period, allowing players to discuss the scenario and chosen solution. This can be done via a chat function or voice chat, depending on the platform's capabilities.  
4.	Scoring and Progression:  
•	Players can be awarded additional points for contributing valuable insights during the discussion phase.  
•	After the discussion, the role of Moderator rotates to the next player, and a new round begins.  
•	The game continues for a predetermined number of rounds or until players decide to conclude.  

Additional Features:  
•	Real-time Interaction: The online platform can incorporate features like live polling or quick reactions to make discussions more interactive.  
•	Educational Insights: After discussing a scenario, the game can provide real-world examples or expert tips related to the challenge addressed.  
•	Customization: Allow players to create custom prompt and response cards, tailoring the game to specific types of online communities or focusing on particular issues of interest.  
  
Conclusion:  
Adapting "What Could Go Wrong - LLM Edition" into an online game about online communities not only modernizes the gameplay but also expands its educational potential. By simulating real-world online community scenarios, players can develop a deeper understanding of digital communication dynamics, ethical considerations, and effective management strategies—all within an engaging and interactive environment.  


### Video Demonstration
[![What could go wrong card game demonstration](https://img.youtube.com/vi/DlqgWnhEqoc/0.jpg)](https://youtu.be/DlqgWnhEqoc)

## Adding new cards
Edit the `prompts.csv` and `responses.csv` to add new cards to the decks. Follow instrcutions for adding new cards here: https://playingcards.io/docs/custom-decks

## Suggested Citation
Nikolas Martelaro and Wendy Ju. 2020. What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles. In *12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications* (*AutomotiveUI '20*). Association for Computing Machinery, New York, NY, USA, 99–101. DOI:https://doi.org/10.1145/3409251.3411734

### Bibtex
```@inproceedings{10.1145/3409251.3411734,  
author = {Martelaro, Nikolas and Ju, Wendy},  
title = {What Could Go Wrong? Exploring the Downsides of Autonomous Vehicles},  
year = {2020},  
isbn = {9781450380669},  
publisher = {Association for Computing Machinery},  
address = {New York, NY, USA},  
url = {https://doi.org/10.1145/3409251.3411734},  
doi = {10.1145/3409251.3411734},  
abstract = { While autonomous vehicles have the potential to greatly improve our daily lives, there are also challenges and potential downsides to these systems. In this workshop, we intend to foster discussions about the potential negative aspects of autonomous cars in hopes of surfacing challenges that should be considered during the design process rather than after deployment. We will spur these conversations through a review of participant position statements and through group discussion facilitated by a card game called “What Could Go Wrong?” Our goal is to consider the autonomous vehicle’s benefits—improving safety, increasing mobility, reducing emissions—against potential drawbacks. By identifying potential harms and downsides, the workshop attendees, and the AutoUI community more broadly can design well-considered solutions.},  
booktitle = {12th International Conference on Automotive User Interfaces and Interactive Vehicular Applications},  
pages = {99–101},  
numpages = {3},  
keywords = {game with a purpose, failure modes, autonomous vehicles},  
location = {Virtual Event, DC, USA},  
series = {AutomotiveUI '20}. 
}
```

For some motivation on why we want to develop new hazard analysis games.

```@article{martelaro2022exploring,
  title={Exploring Opportunities in Usable Hazard Analysis Processes for AI Engineering},
  author={Martelaro, Nikolas and Smith, Carol J and Zilovic, Tamara},
  journal={arXiv preprint arXiv:2203.15628},
  year={2022}
}
```


