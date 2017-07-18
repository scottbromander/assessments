# Logic Challenge - jQuery and AngularJS

## Overview
This is a series of challenges that is completely focused on business logic using both jQuery and AngularJS. You will only
be using one of the two libraries for each of the challenge steps, meaning that you are not to mix jQuery and Angular for 
any of the challenges. 

### Recommended Time: 2.5 hours
### Recommended Time at Prime Academy: Tier 2, Week 7

## jQuery

### Challenge 1
Create an application that loads a button on the DOM when the application starts along with 4 different paragraphs. 
The four different paragraph tags should read:
```
Red Count: 0
Blue Count: 0
Green Count: 0
Yellow Count: 0
```

When the button is clicked, it should create a div on the DOM that is either Red, Green, Yellow, or Blue. The color 
itself should be selected at random. The size of the div should be 50 pixels by 50 pixels. A count of each color 
should be calculated as it is added to the DOM. Meaning that if clicking the button produces a Red Div, 1 should be added
to the `Red Count`, making the paragraph tag for red read `Red Count: 1`.

Below is a GIF of how the challenge should look and work once complete:
![Image of Challenge](https://media.giphy.com/media/l3DdCD2KZOg6sbkoU/giphy.gif)


## AngularJS

### Challenge 2
Create an Application that has an input field and a button when the DOM loads. The user should be able to enter a value into the input field then click on the button. When the button is clicked, the entry should be stored in an array and the input field should be cleared out. Using `ng-repeat`, show a list of input entries along with a button that reads `delete`. When the user clicks on the delete button, the entry should be deleted from the list. 

Below is a GIF of how the challenge should look and work once complete:
![Image of Challenge](https://media.giphy.com/media/3ohz6CjVr4OdTlDTMc/giphy.gif)
