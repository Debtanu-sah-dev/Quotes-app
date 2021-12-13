Today We Are Going To Make A Quote App

WE ARE GOING TO USE TYPE.FIT API

LINK - https://type.fit/api/quotes

All the quotes comes for this api

The Structure of api is below

[ - array
    {
        "text": string,
        "author: string
    },
    follwed object
]

We Will Use Postman Which Is Inbuilt in this editor thats why i have choosed this editor of this project

QUOTIVE.NETLIFY.APP USES THIS API

Lets firstly see how can we use the api

This postman provides you the fetch code

This is the fetch code

fetch("https://type.fit/api/quotes", {
  method: 'GET',
})
.then(response => response.text())
.then((text) => {
  let data = JSON.parse(text)
});

lets start coding

this is editor spots error before the runtime

Block code is taking to much space i will disable it for now

you can see that smooth animation

code link will be in description
