# PasswordGen
Module3 Password Generator


# Password Generator Starter Code
**Project Description:** 
  Creating a Password Generator using JavaScript that enables employees to generate random passwords based on criteria that they’ve selected.

## User Story

```
AS AN employee with access to sensitive data
I WANT to randomly generate a password that meets certain criteria
SO THAT I can create a strong password that provides greater security
```

## Acceptance Criteria

```
GIVEN I need a new, secure password
WHEN I click the button to generate a password
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is either displayed in an alert or written to the page
```

## Starter code
We already have the starter code that starts with generating the generateBtn element and the addEventListener method. Basically it will initiate the Writepassword function when the generate button is press or click on. (shown below) 

<div class="card-footer">
          <button id="generate" class="btn">Generate Password</button>


## Process
First of all we need to add a user prompt so it ask the user to create a password when they click on the generate button. 

We need to add the while loop inside the Prompt function so if the user answers no it will continue to loop the question until the user answer yes. 

Then we edit the writePassword function and creating a password length that allow user to choose from 8 to 128 characters from lowercase, to uppercase, to symbols, to numbers, by using the while loop, we would need to create one for each of those choices.  

After the user is done we will output the choice from an array into a string using (output.join = passwordOut).  If user's respond is invalid they will be alerted.  

If instead user's respond is valid then the passlength is set to true the while loop will end and display the user's choice. The loop will continue to run if the user's passlength is invalid or false. 

The passwordText variable will then be set equal to the password itself generating from the function generatePassword which was pass on to the Prompt function, which is how we will be able to display the password that was generated on the page after it was done created by the user.


## Credits
(https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)

https://css-tricks.com/snippets/javascript/select-random-item-array/ 

(https://www.w3schools.com/js/js_popup.asp)

(https://www.w3schools.com/js/js_htmldom_eventlistener.asp)




## Links

Github Repo - Password Gen github (https://github.com/ceewizz/PasswordGen)

Deployed Application - Password Gen live (https://ceewizz.github.io/PasswordGen/)
