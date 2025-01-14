# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://alexwohlbruck.github.io/cat-facts/

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is to send cat facts.

- What is the URL of the documentation?

> https://alexwohlbruck.github.io/cat-facts/docs/

- What is the full URL of one endpoint?

> https://cat-fact.herokuapp.com/facts

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json

[
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e00b5f0aac31001185ed24",
        "user": "58e007480aac31001185ecef",
        "text": "When asked if her husband had any hobbies, Mary Todd Lincoln is said to have replied \"cats.\"",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-02-19T21:20:03.434Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "feedback": "",
            "sentCount": 1
        },
        "_id": "5887e1d85c873e0011036889",
        "user": "5a9ac18c7478810ea6c06381",
        "text": "Cats make about 100 different sounds. Dogs make only about 10.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-09-03T16:39:39.578Z",
        "type": "cat",
        "createdAt": "2018-01-15T21:20:00.003Z",
        "deleted": false,
        "used": true
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e008780aac31001185ed05",
        "user": "58e007480aac31001185ecef",
        "text": "Owning a cat can reduce the risk of stroke and heart attack by a third.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-03-29T20:20:03.844Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e009390aac31001185ed10",
        "user": "58e007480aac31001185ecef",
        "text": "Most cats are lactose intolerant, and milk can cause painful stomach cramps and diarrhea. It's best to forego the milk and just give your cat the standard: clean, cool drinking water.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-03-04T21:20:02.979Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e00af60aac31001185ed1d",
        "user": "58e007480aac31001185ecef",
        "text": "It was illegal to slay cats in ancient Egypt, in large part because they provided the great service of controlling the rat population.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-09-16T20:20:04.164Z",
        "type": "cat",
        "createdAt": "2018-01-15T21:20:02.945Z",
        "deleted": false,
        "used": true
    }
]

```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=utf-8

> `Content-Length` 1877

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... The cat fact, when it was created and updated, whether the fact was used and deleted, and its source. 

- How could you use this data in an application?

> I could imagine integrating this API into an app that ... shows information on cats while sharing random photos of cats. 

- What did you like about the documentation?

> The documentation was ... simple and straight forward. You ask for cat facts, it gives you cat facts. Its pretty straight forward.

- What did you find challenging about the documentation?

> I found the documentation ... to be easy to understand but hard to see how to implement in some of the examples they gave on how it could be used.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because... Yes. All of the objects and data are explained well with what they are and what they do. The end points are also explained well enough for us to understand.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... sticking with the API that we selected and working our way through it.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is where computers communicate between one another by transferring information.

- In your own words, describe what an API is.

> An API is ...  collection of functions and or data that allows other computers/applications to interact with it.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... allows for easy interaction with web APIs and puts the information in a format that users can mroe easily understand/interact with.
