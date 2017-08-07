# COUNTER-Robots
Official list of user agents that are regarded as robots/spiders by COUNTER

## Purpose of this list
The growing use of web crawler robots have the potential to inflate usage statistics. Only genuine, user-driven usage should be reported in usage statistics. This list can be used to determine whether a request is performed by a bot or if it is performed by a genuine user.

## Pull requests
This list is open for extension and anyone can make a new pull request with new additions to this list. When proposing new bots it is important to give an explanation/argumentation on why you think that is a bot. It would also be appreciated if you can give a small description and eventually an url where the crawler comes from.

## Versioning
Every new release will be tagged with a specific month and year. Versions and changes can be viewed in CHANGES.md

## Format of the list
The list is available in a JSON format, this for the purpose so we can add extra data like date added, a description, an url, ... . Only the pattern field is obligatory. There is a script included called convert_to_text which will convert the list to a text file with a bot on every line. Just run the script in the same folder as the COUNTER_Robots_list.json file and it will generate a COUNTER_Robots_list.txt file (You need jq for this: https://github.com/stedolan/jq).


