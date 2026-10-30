# n8n---Who-lives-where
This workflow retrieves and returns people whose city starts with an A from a JSON.

How it works:
1. Manual trigger
2. HTTP Request, retrieves JSON data with a GET action
3. Filter, to extract objects whose city starts with an A
4. Edit fields, to only maintain the necessary fields to return in the final output (name, email, city).

What I learned:
n8n provides a comfortable drag and drop feature, to drag the keys to filter from.

Known limits:
Currently, real life applicability further than this test.
