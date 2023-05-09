## Assignment 5: Low Fidelity Prototype

Nathan Koketsu | DH 110 | Spring 2023

### Introduction

The primary focus of this project is to address the need for grocery list apps to inform users about the dietary restrictions of people close to them, namely family members. A key defining characteristic of the target audience members is that they have a consistent responsibility to provide food for their family, often encountering barriers such as a lack of technological understanding or a lack of time. However, for the purposes of testing, the insights of anyone who can use the functions of the app can prove useful.

The purpose of this low-fidelity prototype is to test whether my implementation of specific features in the app is intuitive for people who would be expected to use it. Through this, I hope to receive feedback to bring into later iterations of the design while avoiding the potentially wasted time of creating refined features with inherent flaws.

### Supported Tasks

These tasks were based on findings from contextual inquiry and usability testing of an existing app called Errands To-Do List. They are intended to incorporate new capabilities while keeping any working design elements from Errands.

1. Adding new friends to profile. Note that users can add their dietary restrictions to their personal profile
2. Linking friends to an existing grocery list
3. Implementing a suggested grocery for a grocery list

### Prototype and Prototype Testing

Videos of prototype testing are [here](https://drive.google.com/drive/folders/10SIknLv--9SRCWhXdw9CYMAaxvbhBO-5?usp=sharing), with one video for each task.

Download [PDF of wireframes and wireflows](https://github.com/ntkokets/DH110-NathanKoketsu/files/11431220/DH.110.-.Low.Fidelity.Prototype.pdf)

### Reflection

This was a helpful exercise in understanding the work that is needed in creating an interface for an app, and I learned a lot from seeing the tester experience the prototype himself. While I was aware of how I would navigate through the app, this exercise allowed me to clarify aspects of the wireflows that worked intuitively and those that needed revision. The test user was able to complete all tasks but also provided helpful insights to the process.

**Task 1: Adding new friends to profile**

> Fortunately, this task proved to be relatively intuitive for the user. There was one point where the user did not know where to navigate after selecting the search bar for adding new friends, which was mostly caused by a missing wireflow arrow. In the future, I would make sure to implement a clearly-visible keyboard with a search button to ensure that the app appeals to their familiarity in using app search bars. 

**Task 2: Linking friends to an existing grocery list**

> This task yielded significant feedback. For one, the user found that there was not a supported way to link friends to an existing list that does not already have them linked. Additionally, he found that it would be difficult to manage a longer listing of linked friends without search bars for the listing of existing linked friends and the "link new friends" feature. For future iterations, I would implement a button to link new friends, which may be accessed through a separate page to edit all details of the grocery list. Additionally, I would add a search bar for the listing of linked friends and the feature for linking new friends.

**Implementing a suggested grocery for a grocery list**

> The user was able to navigate this task relatively easily, though he had suggestions for the grocery list interface. For example, he mentioned that it could be useful if a user could know whether a grocery item is restricted for another user before committing it to the list. I think this could be difficult to revise since the app would likely need to read the full word input to the list in order to determine whether it is restricted. However, I could potentially implement an autofill type of feature that includes this preliminary restriction information.
