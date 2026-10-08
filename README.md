# The Reading Room Library Assignment

Adapted from the class Product Management example. The same two-file structure, Express routes, array storage, async functions and fetch requests are used.

Your personal version uses forest green, warm ivory and subtle sage accents, with serif headings, clean form fields, restrained outlines and a mobile-friendly layout. No external fonts or images are required. Add, Show, Edit and Delete work the same way as the class-based assignment.

## Run

1. Open a terminal in this folder.
2. Run `npm install`.
3. Run `npm start`.
4. Open http://localhost:3011 in your browser. Open the page through the server instead of double-clicking index.html.

If the class server is already running on port 3011, stop it before starting this assignment.

## Use the web page

- Enter a title, author and category, then click **Add Book** (POST).
- Click **Show Books** to display all books (GET). The page also loads them automatically.
- Click **Edit** beside a book, change its details, then click **Update Book** (PUT).
- Click **Delete** beside a book and confirm (DELETE).

All four operations can be performed from the web page.

## Files and changes

- `index.html`: renamed product fields to book fields, added CSS, edit/delete buttons and their JavaScript functions.
- `server.js`: renamed `/products` to `/books`, assigned IDs, added PUT and DELETE routes and simple validation.
- `package.json`: Express dependency and start command.

Books are stored in an array, just like the class code. Restarting the server clears the records.

