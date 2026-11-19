# Observing HTTP Requests in DevTools

## Request 1: Posts
- **Method:** GET
- **URL:** https://jsonplaceholder.typicode.com/posts
- **Status Code:** 304 Not Modified
- **Purpose:** Retrieves the list of posts. The browser uses its cached copy because the content has not changed.

## Request 2: Users
- **Method:** GET
- **URL:** https://jsonplaceholder.typicode.com/users
- **Status Code:** 304 Not Modified
- **Purpose:** Retrieves the list of users. The browser uses its cached copy because the content has not changed.

## Request 3: Comments
- **Method:** GET
- **URL:** https://jsonplaceholder.typicode.com/comments
- **Status Code:** 304 Not Modified
- **Purpose:** Retrieves the list of comments. The browser uses its cached copy because the content has not changed.

## What I Learned
I used browser DevTools to observe HTTP requests. I learned how to identify request methods, URLs, and status codes. I also learned that a 304 Not Modified response means the browser can use its cached version of the resource.