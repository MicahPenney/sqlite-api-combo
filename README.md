# sqlite-api-combo
ACM meeting where we will be talking about getting data from an API and storing it in a database.

We will be using an API that gives us cat facts (yayy!!!!).
The documentation and API can be found here https://catfact.ninja/

## The file that is in this initial commit is a python script that will create the SQLite database.
The structure of the single table database looks like the following:
| id             | fact         | rating       |
| :------------- | :----------: | -----------: |
|integer (auto increments)| text   | integer   |

The rating will not come from the API that we are using, but we may be building a simple flask website in the future that we can rate the facts ourselves.
