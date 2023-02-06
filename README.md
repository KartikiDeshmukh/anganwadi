## Prakalpa
## Create 
#### URL
```
https://kitintellect.tech/api_anganwadi/public/prakalpa/create
```
#### Method
```
POST
```
#### Payload
```
{
    "title":"skdajalsd"
}
```

## List All
#### URL
```
https://kitintellect.tech/api_anganwadi/public/prakalpa/listAll
```
#### Method
```
GET
```
#### Response
```
{
  "status": 200,
  "data": [
    {
      "id": "4",
      "title": "skdajalsd"
    },
    {
      "id": "3",
      "title": "skdajalsd"
    },
    {
      "id": "2",
      "title": "skdajalsd"
    },
    {
      "id": "1",
      "title": "ertyhbv"
    }
  ],
  "error": null
}
```
## Read
#### URL
```
https://kitintellect.tech/api_anganwadi/public/prakalpa/{id}
```
#### Method
```
GET
```
#### Response 
```
{
  "status": 200,
  "data": {
    "id": "1",
    "title": "ertyhbv"
  },
  "error": null
}
```
## Delete
#### URL
```
https://kitintellect.tech/api_anganwadi/public/prakalpa/delete/{id}
```
#### Method
```
DELETE
```
#### Response
```
{
  "status": 200,
  "error": null,
  "messages": {
    "response": "Record successfully deleted"
  }
}
```
## Update
#### URL
```
https://kitintellect.tech/api_anganwadi/public/prakalpa/update/{id}
```
#### Method
```
PATCH
```
#### Payload
```
{
    "title":"sdsdassd"
}
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "2",
    "title": "sdsdassd"
  },
  "error": null
}
```
