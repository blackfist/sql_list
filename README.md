# sql_list
Take stdin and creates a list for sql queries

# Examples
Let's say you've got a bunch of usernames in your paste buffer and they all have a space at the front and you want to query some database for those values

```
pbpaste | cut -d" " -f2 | sql_list
```
