# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
https://catfact.ninja/fact
{
    "fact": "A cat's whiskers are thought to be a kind of radar, which helps a cat gauge the space it intends to walk through.",
    "length": 113
}
1. A list of 150 random users in English.
https://randomuser.me/api/?results=150
{
    "gender": "female",
    "name": {
    "title": "Miss",
    "first": "Meral",
    "last": "Akar"
}
1. All the repos on Github with Pursuit their name
https://api.github.com/search/repositories?q=pursuit

{
    "total_count": 1552,
    "incomplete_results": false,
    "items": [
        {
            "id": 22592439,
            "node_id": "MDEwOlJlcG9zaXRvcnkyMjU5MjQzOQ==",
            "name": "pursuit",
            "full_name": "purescript/pursuit",
            "private": false,
            "owner": {
                "login": "purescript",
                "id": 6556677,
                "node_id": "MDEyOk9yZ2FuaXphdGlvbjY1NTY2Nzc=",
                "avatar_url": "https://avatars2.githubusercontent.com/u/6556677?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/purescript",
                "html_url": "https://github.com/purescript",
                "followers_url": "https://api.github.com/users/purescript/followers",
                "following_url": "https://api.github.com/users/purescript/following{/other_user}",
                "gists_url": "https://api.github.com/users/purescript/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/purescript/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/purescript/subscriptions",
                "organizations_url": "https://api.github.com/users/purescript/orgs",
                "repos_url": "https://api.github.com/users/purescript/repos",
                "events_url": "https://api.github.com/users/purescript/events{/privacy}",
                "received_events_url": "https://api.github.com/users/purescript/received_events",
                "type": "Organization",
                "site_admin": false
            }
1. All the JavaScript repos on Github with Pursuit in their name
https://api.github.com/search/repositories?q=pursuit+language:javascript
{
    "total_count": 167,
    "incomplete_results": false,
    "items": [
        {
            "id": 29826657,
            "node_id": "MDEwOlJlcG9zaXRvcnkyOTgyNjY1Nw==",
            "name": "argo",
            "full_name": "albertosantini/argo",
            "private": false,
            "owner": {
                "login": "albertosantini",
                "id": 328179,
                "node_id": "MDQ6VXNlcjMyODE3OQ==",
                "avatar_url": "https://avatars2.githubusercontent.com/u/328179?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/albertosantini",
                "html_url": "https://github.com/albertosantini",
                "followers_url": "https://api.github.com/users/albertosantini/followers",
                "following_url": "https://api.github.com/users/albertosantini/following{/other_user}",
                "gists_url": "https://api.github.com/users/albertosantini/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/albertosantini/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/albertosantini/subscriptions",
                "organizations_url": "https://api.github.com/users/albertosantini/orgs",
                "repos_url": "https://api.github.com/users/albertosantini/repos",
                "events_url": "https://api.github.com/users/albertosantini/events{/privacy}",
                "received_events_url": "https://api.github.com/users/albertosantini/received_events",
                "type": "User",
                "site_admin": false
            },
1. All the Swift repos on Github with Pursuit in their name
https://api.github.com/search/repositories?q=pursuit+language:swift

{
    "total_count": 168,
    "incomplete_results": false,
    "items": [
        {
            "id": 99703757,
            "node_id": "MDEwOlJlcG9zaXRvcnk5OTcwMzc1Nw==",
            "name": "Pursuit-Core-iOS",
            "full_name": "joinpursuit/Pursuit-Core-iOS",
            "private": false,
            "owner": {
                "login": "joinpursuit",
                "id": 5825944,
                "node_id": "MDEyOk9yZ2FuaXphdGlvbjU4MjU5NDQ=",
                "avatar_url": "https://avatars2.githubusercontent.com/u/5825944?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/joinpursuit",
                "html_url": "https://github.com/joinpursuit",
                "followers_url": "https://api.github.com/users/joinpursuit/followers",
                "following_url": "https://api.github.com/users/joinpursuit/following{/other_user}",
                "gists_url": "https://api.github.com/users/joinpursuit/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/joinpursuit/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/joinpursuit/subscriptions",
                "organizations_url": "https://api.github.com/users/joinpursuit/orgs",
                "repos_url": "https://api.github.com/users/joinpursuit/repos",
                "events_url": "https://api.github.com/users/joinpursuit/events{/privacy}",
                "received_events_url": "https://api.github.com/users/joinpursuit/received_events",
                "type": "Organization",
                "site_admin": false
            }
1. A list of all Pokemon
https://pokeapi.co/api/v2/pokemon
{
    "count": 964,
    "next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
    "previous": null,
    "results": [
        {
            "name": "bulbasaur",
            "url": "https://pokeapi.co/api/v2/pokemon/1/"
        }
1. A list of all items in Fortnite
https://fortnite-api.theapinetwork.com/items/list
{"success":false,"location":"nyc","error":{"code":"xx002","message":"Access denied."},"data":{}}
1. A list of all Game of Thrones Episodes.
https://api.got.show/api/map/episodes
{
    "message": "Success",
    "data": [
        {
            "characters": [
                "Viserys Targaryen",
                "Catelyn Stark",
                "Cersei Lannister",
                "Jaime Lannister",
                "Eddard Stark",
                "Robert Baratheon",
                "Jorah Mormont",
                "Daenerys Targaryen",
                "Jon Snow",
                "Petyr Baelish",
                "Arya Stark",
                "Sansa Stark",
                "Bran Stark",
                "Robb Stark",
                "Joffrey Baratheon",
                "Tyrion Lannister",
                "Jeor Mormont",
                "Alliser Thorne",
                "Jory Cassel",
                "Barristan Selmy",
                "Rodrik Cassel",
                "Benjen Stark",
                "Yoren",
                "Renly Baratheon",
                "Maester Aemon",
                "Syrio Forel",
                "Grenn",
                "Irri",
                "Pypar",
                "Rakharo",
                "Lancel Lannister"
            ],
            "_id": "5cc0743604e71a0010b85729",
            "director": "Tim Van Patten",
            "airDate": "2011-04-24T04:00:00.000Z",
            "totalNr": 2,
            "season": 1,
            "nr": 2,
            "name": "The Kingsroad",
            "predecessor": "Winter Is Coming",
            "successor": "Lord Snow",
            "createdAt": "2019-04-24T14:35:34.594Z",
            "updatedAt": "2019-04-24T14:35:34.594Z",
            "__v": 0
        }
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
https://itunes.apple.com/search?term=leonardo+dicaprio

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
1. 301
1. 400
1. 401
1. 403
1. 404
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



