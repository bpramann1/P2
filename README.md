# EECS731P1DataExplorer

Creation Steps
  Step 1:
    Project Structure set up in this Git Repository
  Step 2:
    Downloaded the Shakespeare plays dataset
  Step 3:
    Loaded the dataset into panda data frames
  Step 4:
    One idea I have for feature engineering is to find the most used words in the dataset and then make new features out of some of the most used words that the features is how many times each of the words is used in the player lines. The idea is that a players speech might have a certain structure in general. This idea probably should be worked on as there is probably a more effecient and affective feature to exract from the original data.
    The second idea I have is to count how many of each type of punctuation is used and then make each punction type a new feature with the value of the feature being the number of times that punctuation is used in the playerline. This follows the same reasoning that the first feature idea followed.
    The third idea I have for a feature is just the length of the playerline! This follows the same reasoning that the first feature idea followed.
    The forth idea I have for a feature is just a 1 or 0 based off whether a name was inside of the playerline. The idea is that players address other players and so if we know who is being address we can take a good guess at who is saying it.
  Step 5:
    The idea is to make a neural network with the explainitory variables as "m" of the top words and then the period, exclaimation, and question mark features, as well as the length of the sentence to give a relitive marker feature, and then the top "x" used names as explanitory features. The explained feature of the nueral network would of course be the player.
  Step 6:
    I am sorry I didn't work much on this project. I have had some other responsibilties
  
