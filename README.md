SRJSON
======

The very simple class that handling JSON object

# Example

JSON String Data Example:

```
{ 
    "results": [
        {
            "name": "first",
            "value": 0
        },
        {
            "name": "second",
            "value": 1
        },
    ]
}
```

Let this string to 'inputString'

# Usage

```swift
let json = SRJSON.jsonWithString(inputString)

print(json["results"]?[0]?["name"]?.stringValue)
// "first"
```
