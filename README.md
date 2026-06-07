Although this README file will be put on my profile, I use it as a quick note of my numerous ideas. Some may be interesting, but I do not have time to implement everything, so they are just ideas.
## Some ideas that may implement
### Smart Heating System
a system that can control heating time depending on energy consumption, using AI model to analise, satisfying the users' demands.
1. User gives a require like "I hope my house keep 25°C (or higher) in next 12 hours"
2. A basic assumption: due to weather reason, energy sources such as solar and wind generate energy somtimes high sometimes low. More energy generating at the same time, the price of energy are less at that moment.
3. Our goal: satisfy the user's require use less energy, and the price as cheap as possible.
4. Task: design an AI model as smart controller, control when to consume energy to heat the house to which tempreture and contain how long. For example, the traditional heating system keep heating in all 12 hours. But if energy are cheaper in first 2 hours(that means produce more), then controller can decide to heat higher than 25°C in the 2 hours, and turn off the heating system until tempreture drop down under 25°C. As long as computing correctly, this method can reduce the cost from 2 aspects: first, use cheaper energy, second, save the cost, because once heating to given tempreture, the system will not heat continuly.
5. attention: we need time to collect data, so the model need to be have the analize ability as quick as possible.
ap. relevant ideas: build strong links between energy generating regions to energy neeeded regions.
### University Course Helper
an individualized AI model for each course to save confused stduents.
