# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact 
https://catfact.ninja
{
  "fact": "string",
  "length": 0
}

1. A list of 150 random users in English.
https://randomuser.me
{
"results": [
  {
    "gender": "male",
    "name": {
      "title": "mr",
      "first": "brad",
      "last": "gibson"
    },
    "location": {
      "street": "9278 new road",
      "city": "kilcoole",
      "state": "waterford",
      "postcode": "93027",
      "coordinates": {
        "latitude": "20.9267",
        "longitude": "-7.9310"
      },
      "timezone": {
        "offset": "-3:30",
        "description": "Newfoundland"
      }

1. All the repos on Github with Pursuit their name
https://stackoverflow.com/questions/25022016/get-all-file-names-from-a-github-repo-through-the-github-api
{
"sha": "9fb037999f264ba9a7fc6274d15fa3ae2ab98312",
"url": "https://api.github.com/repos/octocat/Hello-World/trees/9fb037999f264ba9a7fc6274d15fa3ae2ab98312",
"tree": [
  {
    "path": "file.rb",
    "mode": "100644",
    "type": "blob",
    "size": 30,
    "sha": "44b4fc6d56897b048c772eb4087f854f46256132",
    "url": "https://api.github.com/repos/octocat/Hello-World/git/blobs/44b4fc6d56897b048c772eb4087f854f46256132"
  }
1. All the JavaScript repos on Github with Pursuit in their name
1. All the Swift repos on Github with Pursuit in their name
1. A list of all Pokemon
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 - HTTP 200 OK success status response code indicates that the request has succeeded 
1. 301 - HTTP response status code 301 Moved Permanently is used for permanent URL redirection
1. 400 - The 400 Bad Request error (the request was incorrect or corrupted and the server couldn't understand it.)
1. 401 - The 401 Unauthorized Error ( Unauthorized Error indicates that the requested resource is restricted and requires authentication)
1. 403 - The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it.
1. 404 - 404 Not Found, 404, Page Not Found, or Server Not Found error 
1. 418 - The HTTP 418 I'm a teapot client error response code indicates that the server refuses to brew coffee because it is a teapo
1. 500 - The 500 Internal Server Error 


For each of the questions below, write:

1. The website which generated the HTTP status code
https://www.anapioficeandfire.com/api/books/500


2. A description of what the status code means
HTTP status code 404 - Not Found

3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?
See what particular issue that status code is referring to and depending on that try to find a solution

For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



