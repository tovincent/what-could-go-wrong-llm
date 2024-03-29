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

## Game Setup Instructions
1. Download this repository
2. Go to https://playingcards.io/game/standard-deck to start a custom deck
3. Enter the virtual card table
4. Click the `Edit Table` icon in the green toolbard
5. Select `Room Options`
6. Select  `Import From File`
7. Upload `what-could-go-worng-av.pcio`
8. Click `Edit Table` to exit editing mode and go into gameplay mode

# Game Overview  
"Online Communities: Navigating the Digital Frontier" is a card-based discussion game where players explore the complexities of online community participation and management. Through scenario-based prompts and strategic response options, players will navigate the challenges of digital ethics, content moderation, privacy concerns, community engagement, and more.  

## Game Components  
Prompt Cards (Black Cards): These cards present scenarios or challenges commonly faced by online communities. Scenarios could range from dealing with trolls, managing misinformation, handling privacy breaches, to fostering inclusive environments.  
Response Cards (White Cards): These cards offer potential actions, policies, or strategies to address the challenges presented in the prompt cards. Responses could include implementing new moderation tools, creating community guidelines, launching educational campaigns, and more.  

## Game Setup Instructions for Real Life  
Print the Card Decks: Use the provided LaTeX template to print physical copies of the prompt and response cards. Ensure there's a diverse mix of scenarios and strategies relevant to various types of online communities.  
Prepare the Play Space: Arrange a comfortable area where players can gather around a table. Each player should have enough space to hold their cards.  
Shuffle and Deal: Shuffle the prompt and response decks separately. Deal 5 response cards to each player.  

## Gameplay Instructions  
Choosing the Card Czar: The game begins by randomly selecting a player to be the Card Czar. This role rotates clockwise after each round.  
Drawing a Prompt Card: The Card Czar draws the top card from the prompt deck and reads the scenario aloud to the group.  
Submitting Response Cards: Players select one of their response cards that they believe best addresses the scenario, placing it face down.  
Review and Discussion: The Card Czar reads each submitted response aloud. The group then discusses the merits and potential outcomes of each strategy.  
Scoring: The Card Czar selects the response they believe is most effective, awarding a point to the player who submitted it. Optionally, additional points can be awarded for insightful contributions to the discussion.  
Continuing the Game: The next player becomes the Card Czar, and everyone draws a new response card to maintain a hand of 5 cards. The game continues for a predetermined number of rounds or until all prompt cards have been used.  

## Encouraging Discussion  
Deep Dives: Allow for detailed discussions after each round to explore the complexities of managing online communities.  
Real-World Examples: Encourage players to bring up real-life instances that relate to the game's scenarios.  
Reflection: After the game, have a debrief session where players can reflect on what they've learned and share thoughts on how the game's scenarios relate to their experiences in online communities.  

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


