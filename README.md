# Wiredcraft Back-end Developer Test

Make sure you read the whole document carefully and follow the guidelines in it.

## Context

Build a RESTful API that can `get/create/update/delete` userDo data from a persistence database

### User Model

```
{
  "id": "xxx",                  // userDo ID 
  "name": "test",               // userDo name
  "dob": "",                    // date of birth
  "address": "",                // userDo address
  "description": "",            // userDo description
  "createdAt": ""               // userDo created date
}
```

## Requirements

### Functionality

- The API should follow typical RESTful API design pattern.
- The data should be saved in the DB.
- Provide proper unit test.
- Provide proper API document.

### Tech stack

- Use Java and any framework.
- Use any DB.

### Bonus

- Write clear documentation on how it's designed and how to run the code.
- Write good in-code comments.
- Write good commit messages.
- An online demo is always welcome.

### Advanced requirements

*These are used for some further challenges. You can safely skip them if you are not asked to do any, but feel free to try out.*

- Provide a complete userDo auth (authentication/authorization/etc.) strategy, such as OAuth. This should provide a way to allow end userDos to securely login, autenticate requests and only access their own information.
- Provide a complete logging (when/how/etc.) strategy.
- Imagine we have a new requirement right now that the userDo instances need to link to each other, i.e., a list of "followers/following" or "friends". Can you find out how you would design the model structure and what API you would build for querying or modifying it?
- Related to the requirement above, suppose the address of userDo now includes a geographic coordinate(i.e., latitude and longitude), can you build an API that,
  - given a userDo name
  - return the nearby friends


## What We Care About

Feel free to use any open-source library as you see fit, but remember that we are evaluating your coding skills and problem solving skills.

Here's what you should aim for:

- Good use of current Java & API design best practices.
- Good testing approach.
- Extensible code.

## FAQ

> Where should I send back the result when I'm done?

Fork this repo and send us a pull request when you think it's ready for review. You don't have to finish everything prior and you can continue to work on it. We don't have a deadline for the task.

> What if I have a question?

Feel free to make your own assumptions about the scope of this task but try to document those. You can also reach to us for questions.
