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

We Will Use Postman Which Is Inbuilt in this editor thats why i have choosed this editor of this project - https://codingeditor.netlify.app

QUOTIVE.NETLIFY.APP USES THIS API

Postman provides you the fetch code

This is the fetch code

fetch("https://type.fit/api/quotes", {
  method: 'GET',
})
.then(response => response.text())
.then((text) => {
  let data = JSON.parse(text)
});
