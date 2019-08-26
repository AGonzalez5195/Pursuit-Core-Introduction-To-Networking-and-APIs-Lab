# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
Apple.com. 200 code means that the get request was successful and the website was returned with no issue. Nothing needs to be fixed in the app.

1. 301
This error code means the website was permanently redirected. Sends traffic from other URLs to preferred URL. Fix is to make sure that the redirect leads to where the actual address is.

1. 400
Error code means that server was unable to process the client-sent request due to invalid syntax. Fix is to know how to type.

1. 401
Error code means that page cannot be accessed until logged in with valid user id/password. Unauthorized error.  Fix is to make sure that user is logged in with their valid credentials.

1. 403
Error code means page is forbidden. Permissions-based. Fix is to properly set permissions/make sure that page is forbidden on purpose or not.

1. 404

Error code means server is reachable, but specific page isn't. Fix is to use the correct URL.

1. 418
Joke

1. 500
Error code means server cannot process request for unknown reason. Fix is idk.


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

## A random cat fact
https://cat-fact.herokuapp.com/facts

## A list of 150 random users in English.
https://randomuser.me/api/?results=100
{
"results": [
{
"gender": "male",
"name": {
"title": "mr",
"first": "angel",
"last": "herrero"
},
"location": {
"street": "4350 avenida de la albufera",
"city": "alcobendas",
"state": "comunidad de madrid",
"postcode": 63458,
"coordinates": {
"latitude": "-16.6216",
"longitude": "-95.4933"
},
"timezone": {
"offset": "-7:00",
"description": "Mountain Time (US & Canada)"
}
},
"email": "angel.herrero@example.com",
"login": {
"uuid": "26261089-4f0c-439f-9ccc-6095cce5a74b",
"username": "silverpeacock470",
"password": "rockwell",
"salt": "s7dWnK0v",
"md5": "a4225b512aa61ef02e09df58221987a0",
"sha1": "fcfb9fcba86871f2809d09f219314998c8393492",
"sha256": "3149502ea856b5382c4bbf788656135dabb30f6e34eb5c79433b70bdb1e7daae"
},
"dob": {
"date": "1947-05-07T11:25:41Z",
"age": 72
},
"registered": {
"date": "2011-10-15T04:46:30Z",
"age": 7
},
"phone": "978-836-427",
"cell": "696-111-259",
"id": {
"name": "DNI",
"value": "14697644-O"
},
"picture": {
"large": "https://randomuser.me/api/portraits/men/31.jpg",
"medium": "https://randomuser.me/api/portraits/med/men/31.jpg",
"thumbnail": "https://randomuser.me/api/portraits/thumb/men/31.jpg"
},
"nat": "ES"
},
{
"gender": "male",
"name": {
"title": "mr",
"first": "cristiano",
"last": "melo"
},
"location": {
"street": "6666 rua dezenove de outubro",
"city": "paranaguá",
"state": "mato grosso",
"postcode": 16524,
"coordinates": {
"latitude": "82.2276",
"longitude": "68.1961"
},
"timezone": {
"offset": "+4:00",
"description": "Abu Dhabi, Muscat, Baku, Tbilisi"
}
},
"email": "cristiano.melo@example.com",
"login": {
"uuid": "22138f27-afcb-4778-9239-9a4961d7e0c4",
"username": "goldengorilla553",
"password": "clippers",
"salt": "2D6aUr7Y",
"md5": "8014eb86b8a47b1dbce6cabb5482831e",
"sha1": "540cf5f48311f4daa7037728f4448739247b10f5",
"sha256": "687182f95039e7915f31fcae2eda9afeaf35cdfc42e798e202c3433ca88c3467"
},
"dob": {
"date": "1948-06-11T04:41:14Z",
"age": 71
},
"registered": {
"date": "2009-09-02T21:18:38Z",
"age": 9
},
"phone": "(16) 8480-5143",
"cell": "(84) 6360-3278",
"id": {
"name": "",
"value": null
},
"picture": {
"large": "https://randomuser.me/api/portraits/men/52.jpg",
"medium": "https://randomuser.me/api/portraits/med/men/52.jpg",
"thumbnail": "https://randomuser.me/api/portraits/thumb/men/52.jpg"
},
"nat": "BR"
},


1. The current stock price of Microsoft. (IEX API)
https://ws-api.iextrading.com/1.0/tops?symbols=MSFT
[
{
"symbol": "MSFT",
"sector": "softwareservices",
"securityType": "commonstock",
"bidPrice": 133.95,
"bidSize": 100,
"askPrice": 134.99,
"askSize": 200,
"lastUpdated": 1566845452794,
"lastSalePrice": 134.975,
"lastSaleSize": 1,
"lastSaleTime": 1566845440294,
"volume": 361642,
"marketPercent": 0.02871
}
]

## The 5 year history of Apple stock prices (IEX API)
https://api.iextrading.com/1.0/hist?date=20170515

## All the Swift language repos on Github with Pursuit in their name

## A list of all Pokemon
https://pokeapi.co/api/v2/pokemon?limit=964
{
"count": 964,
"next": null,
"previous": null,
"results": [
{
"name": "bulbasaur",
"url": "https://pokeapi.co/api/v2/pokemon/1/"
},
{
"name": "ivysaur",
"url": "https://pokeapi.co/api/v2/pokemon/2/"
},

## A list of all items in Fortnite
https://fortnite-api.theapinetwork.com/items/list

## A list of all Game of Thrones Episodes.
https://api.got.show/api/show/episodes
[
{
"written_by": [
"David Benioff",
"D.B. Weiss"
],
"characters": [
"Will",
"Waymar Royce",
"Gared",
"Wildling girl",
"White Walker 1",
"White Walker 2",
"Bran Stark",
"Jon Snow",
"Robb Stark",
"Catelyn Stark",
"Eddard Stark",
"Rickon Stark",
"Sansa Stark",
"Mordane",
"Arya Stark",
"Jeyne Poole",
"Rodrik Cassel",
"Jory Cassel",
"Theon Greyjoy",
"Lady",
"Grey Wind",
"Shaggydog",
"Summer",
"Nymeria",
"Ghost",
"Jaime Lannister",
"Cersei Lannister",
"Maester",
"Tommy",
"Joffrey Baratheon",
"Sandor Clegane",
"Preston Greenfield",
"Hodor",
"Mikken",
"Robert Baratheon",
"Tommen Baratheon",
"Myrcella Baratheon",
"Tyrion Lannister",
"Ros",
"Daenerys Targaryen",
"Viserys Targaryen",
"Pentoshi servant",
"Illyrio Mopatis",
"Khal",
"Qotho",
"Cohollo",
"Haggo",
"Benjen Stark",
"Jorah Mormont",
"Mago"
],
"deaths": [
"Waymar Royce",
"Gared",
"Will",
"Jon Arryn",
"Dothraki"
],
"places": [
"Beyond the Wall",
"In Pentos",
"In King's Landing",
"In the North",
"First",
"Deaths",
"Cast notes"
],
"_id": "5cc074bf04e71a0010b85a1a",
"title": "Winter Is Coming",
"season": 1,
"episode": 1,
"runtime": 62,
"directed_by": "Tim Van Patten",
"createdAt": "2019-04-24T14:37:51.759Z",
"updatedAt": "2019-04-24T14:37:51.759Z",
"__v": 0
},
{
"written_by": [
"David Benioff",
"D.B. Weiss"
],
"characters": [
"Doreah",
"Irri",
"Jhiqui",
"Rast",
"Catspaw assassin",
"Ilyn Payne",
"Mycah",
"Lannister guardsman"
],
"deaths": [
"Catspaw assassin",
"Mycah",
"Lady"
],


## A list of all songs with "Love" in the title.

## All information about Petyr Baelish from the Game of Thrones books
https://anapioficeandfire.com/api/characters/823
{
"url": "https://anapioficeandfire.com/api/characters/823",
"name": "Petyr Baelish",
"gender": "Male",
"culture": "Valemen",
"born": "In 268 AC, at the Fingers",
"died": "",
"titles": [
"Master of coin (formerly)",
"Lord Paramount of the Trident",
"Lord of Harrenhal",
"Lord Protector of the Vale"
],
"aliases": [
"Littlefinger"
],


## All the movies Leonardo Dicaprio has acted in
