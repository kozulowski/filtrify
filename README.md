# filtrify.js Reloaded


## What was added?

- An 'any' parameter for the trigger() method. Useful when you want to select items that match any of the provided terms in the query

`
ft.trigger ({"genre": ["horror"]}, true);
`
