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

## Anganwadi
## Create
#### URL
```
https://kitintellect.tech/api_anganwadi/public/anganwadi/create
```
#### Method
```
POST
```
#### Payload
```
{
    "prakalpa_id": "123",
    "bit_id": "12",
    "name": "sdf",
    "aganwadi_no": "123",
    "year": "33ed",
    "state_id": "123123",
    "dist_id": "12",
    "taluka_id": "12",
    "grampanchayat_id": "12",
    "village_id": "12",
    "zip": "213"
}
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "5",
    "prakalpa_id": "123",
    "bit_id": "12",
    "name": "sdf",
    "aganwadi_no": "123",
    "year": "2033",
    "state_id": "123123",
    "dist_id": "0",
    "taluka_id": "12",
    "grampanchayat_id": "12",
    "village_id": "12",
    "zip": "213"
  },
  "error": null
}
```
## List All
#### URL
```
https://kitintellect.tech/api_anganwadi/public/anganwadi/listAll
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
      "prakalpa_id": "23",
      "bit_id": "8",
      "name": "asachj",
      "aganwadi_no": "ravanhje",
      "year": "2023",
      "state_id": "41",
      "dist_id": "0",
      "taluka_id": "45",
      "grampanchayat_id": "77",
      "village_id": "74",
      "zip": "12345"
    },
    {
      "id": "3",
      "prakalpa_id": "23",
      "bit_id": "8",
      "name": "asachj",
      "aganwadi_no": "ravanhje",
      "year": "2023",
      "state_id": "41",
      "dist_id": "0",
      "taluka_id": "45",
      "grampanchayat_id": "77",
      "village_id": "74",
      "zip": "12345"
    },
    {
      "id": "2",
      "prakalpa_id": "23",
      "bit_id": "8",
      "name": "asachj",
      "aganwadi_no": "ravanhje",
      "year": "2023",
      "state_id": "41",
      "dist_id": "0",
      "taluka_id": "45",
      "grampanchayat_id": "77",
      "village_id": "74",
      "zip": "12345"
    },
    {
      "id": "1",
      "prakalpa_id": "0",
      "bit_id": "0",
      "name": "asachj",
      "aganwadi_no": "ravanhje",
      "year": "2023",
      "state_id": "0",
      "dist_id": "0",
      "taluka_id": "0",
      "grampanchayat_id": "0",
      "village_id": "0",
      "zip": "12345"
    }
  ],
  "error": null
}
```
## Read
#### URL
```
https://kitintellect.tech/api_anganwadi/public/anganwadi/{id}
```
#### Method
```
show
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "5",
    "prakalpa_id": "123",
    "bit_id": "12",
    "name": "sdf",
    "aganwadi_no": "123",
    "year": "2033",
    "state_id": "123123",
    "dist_id": "0",
    "taluka_id": "12",
    "grampanchayat_id": "12",
    "village_id": "12",
    "zip": "213"
  },
  "error": null
}
```
## Update
#### URL
```
https://kitintellect.tech/api_anganwadi/public/anganwadi/update/{id}
```
#### Method
```
PATCH
```
#### Payload
```
{
       "aganwadi_no": "asas"
}
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "4",
    "prakalpa_id": "23",
    "bit_id": "8",
    "name": "asachj",
    "aganwadi_no": "asas",
    "year": "2023",
    "state_id": "41",
    "dist_id": "0",
    "taluka_id": "45",
    "grampanchayat_id": "77",
    "village_id": "74",
    "zip": "12345"
  },
  "error": null
}
```
## DELETE
#### URL
```
https://kitintellect.tech/api_anganwadi/public/anganwadi/delete/{id}
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

## BIT
## Create
#### URL
```
https://kitintellect.tech/api_anganwadi/public/bit/create
```
#### Method
```
POST
```
#### Payload
```
{
    "title":"Aslkjsl"
}
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "4",
    "title": "Aslkjsl"
  },
  "error": null
}
```

## Read
#### URL
```
https://kitintellect.tech/api_anganwadi/public/bit/{id}
```
#### Method
```
SHOW
```
#### Response
```
{
  "status": 204,
  "data": [],
  "message": "No Record Found",
  "error": null
}
```

## Update
#### URL
```
https://kitintellect.tech/api_anganwadi/public/bit/update/{id}
```
#### Method
```
PATCH
```
#### Payload
```
{
    "title":"Askjkas"
}
```
#### Response
```
{
  "status": 200,
  "data": {
    "id": "2",
    "title": "Askjkas"
  },
  "error": null
}
```

## List All
#### URL
```
https://kitintellect.tech/api_anganwadi/public/bit/listAll
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
      "title": "Aslkjsl"
    },
    {
      "id": "3",
      "title": "33434"
    },
    {
      "id": "2",
      "title": "example"
    }
  ],
  "error": null
}
```

## Delete
#### URL
```
https://kitintellect.tech/api_anganwadi/public/bit/delete/{id}
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
