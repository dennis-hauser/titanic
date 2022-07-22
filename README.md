# Titanic
> The "Hello World" of Data Analytics

The notebook is the foundation for answering some interesting questions.

# Answer the questions
### 1. Do female passengers have a better chance to survive than male passengers?
**YES** the following statistics support this statement:
- Out of 314 women 233 of them survived (only 81 did not survive)
  - The probability of surviving given beeing female P(Survived = 0|female) is at 74%
- Out of all Passengers the chance of survival and beeing female P(Survived = 1 ∧ female) is with 26% much higher than surviving and beeing male 12%

> Maybe they saved "women and children first" <br>
> See: https://en.wikipedia.org/wiki/Women_and_children_first

### 2. Do passengers traveling alone have a better chance to survive than other passengers?
**NO** it's even worse 
- Out of all passengers 42% where alone and didn't survive
- The conditional probability P(Survived = 0|IsAlone=True) is at around 70%

### 3. Does the passengers class inﬂuence the chance for surviving the disaster?
**YES** 
- The probability of surviving given beeing in the first class is at 63%, second and third class are at 47% and 24%

### 4. Does the place of embarkment inﬂuence the chance for surviving the disaster?
**YES** 
- Surviving given beeing embarked at Cherbourg is at 55% and higher than the other two.

> The passengers which embarked in Cherbourg are maybe in a area of higher income and therfore are more first class passengers which had a higher chance of survival

### 5. Do you think the age of a passenger has an inﬂuence on the chance for surviving the disaster?
**YES**
- Most of the elderly passengers didn't survive
