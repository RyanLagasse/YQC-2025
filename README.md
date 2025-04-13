## Inspiration 

We were inspired by our love for Quantum Computing, as well as the destructive fires that have happened recently, primarily ones like the LA wildfires. Many people lost everything in those fires, and the realization that Quantum Computing could help people in times of need inspired us to push harder and keep working, despite the challenges we faced. 

 

## What it does 

The algorithm solves a maximally independent set problem given a set of points in 2D space. This set of points can be generated from satellite data and we designed a custom algorithm to show how this can be used in the real world – specifically in our testcase of Almeda County  -a community that was narrowly saved from California Wildfires – but what if? We wanted to see what could have happened and what we could have done.  

 

## How we built it 

We used Bloqade’s local python quantum computer simulator as a base for our quantum algorithm. In theory this could be built on a stack based off a real quantum computer, but we also show how his can be scaled further with some of our simulations that exceeded our quantum compute budget. -More details and pseudocode in the github 

 

## Challenges we ran into 

One of the biggest challenges we ran into was trying to run our code on the actual Quantum Computer. There were errors preventing teams from running it, so we had to rely on local simulations for our results. While this was a challenge it got us to think far more about what might be possible with future quantum computers that will not be limited by the same hardware challenges we face today. Focusing on simulation allowed us to successfully run our algorithm on 20+ qubits, which we would not have bn able to do on Quera’s Aquilla today. 

 

## Accomplishments that we're proud of 

We are quite proud that we were able to successfully run our code on a challenge that has real world impact. We didn’t expect to get results as good as we got as we are aware how tricky it can be to tune parameters on quantum computers so the physics matches the vision we have in mind. We hope that our works shows that this is a promising application of quantum computers and should be  investigated more with more qubits and data. It it was so cool to make something that could be used in the future to help so many people in our communities! 

 

## What we learned 

We learned that scaling some classical algorithms wouldn’t work and moving them to Quantum Computing would allow us to scale them further with exponential efficiency. Using Quantum Computing for insurance and safety wasn’t an expected application, but through this hackathon, we learned about how helpful and beneficial it could be. 

 

## What's next for Wildfire Risk Quantum Graph Coloring 
Next, would be expanding to a larger set of points as quantum computing expands. If we have more qubits to use, we can increase the granularity of our algorithm all the way to the scale of individual properties. This would allow us to really advance our algorithm to the next level, while also helping citizens as well. 

 

## To Run 

### Quantum 

pip install bloqade.analog, matplotlib, numpy 

run main.ipynb 

### Classical 

pip install networkx, matplotlib 

run the final code cell in classic-ims.ipynb 

 
