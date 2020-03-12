# JSON(JavaScript Object Notation)
- Data Representation Format
- Commonly used for APIs and Configs
- Lightweight and Easy to Read/Write(request and response)
- Superset of javaScript
- Esaily integrates with most known languages

## JSON Types

**JSON natively supports the following :**
- **Strings** "Hello World" ,"Kyle", "I"
- **Numbers** 10 , 1.5 , -30 ,1.2e10
- **Booleans** true ,False
- **null** null
- **Arrays** [1,2,3] ,["Hello","Man"]
- **Objects**  {"key":"value"} {"age":30}

## To use JSON 
- First create a file with json extention filename.json
- We can put one of the types that are listed above and put it in the file 
- But it is not usefull when you have single input or output, so if there are more stream of inputs then it would be usefull for using json file.
- Most of the time we working with json we either have an array or an object.
- To create a object we use the curly braces**{}** and inside this we use define the key value pairs.
- The key value pairs key is in double quots
``` 
{
"name":"wild",
"emp_no":3,
"isprogrammmer": true,
"hobbies":["Weight Lifting","Bowling"],
"friends":[{
    "name":"croft",
    "isprogrammmer": true,
    "hobbies":["Weight Lifting","Bowling"],
    "friend":[..]
    }]
}
```
To access the json we have to use JSON.parse
