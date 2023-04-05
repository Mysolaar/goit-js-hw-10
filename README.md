## About

This code sets up a search input box that allows users to search for countries. 

- When user enters a search term, the code sends a request to an API to fetch information about the matching countries. 
- If there are too many matching countries, a message is displayed to ask for a more specific search. 
- If there are multiple matching countries, a list of countries with their flags is displayed. 
- If there is only one matching country, detailed information about that country is displayed, including its flag, capital city, population, and official languages. 

User can enter multiple search terms, but the search is debounced, with a 300ms delay before the search is performed after the user stops typing. 
The code also imports the debounce function from the Lodash library, and the Notify function from the Notiflix library.
