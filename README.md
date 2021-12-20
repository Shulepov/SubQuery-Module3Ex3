# Query to run

```shell
query{
  accounts(first:5){
    nodes{
      id
      myToAddress{
        nodes{
          id
          amount
        }
      }
    }
  }
}
```

# Output

````json
{
  "data": {
    "accounts": {
      "nodes": [
        {
          "id": "1124RsfEgJEZvEq4HbtGFcpqoxnqSy79EjNZY9tzPct3AB6o",
          "myToAddress": {
            "nodes": [
              {
                "id": "444722-123",
                "amount": "150000000000"
              }
            ]
          }
        },
        {
          "id": "112A3784ssUTCFQJvygzhCt4eiVkXft4RFixknBT3jsT8nb5",
          "myToAddress": {
            "nodes": [
              {
                "id": "241591-235",
                "amount": "1000000000000"
              }
            ]
          }
        },
        {
          "id": "116x7oVBcDjFo3bMeGdMYGwW8uS2ca7o4Wn7kQy65mkDwtd",
          "myToAddress": {
            "nodes": [
              {
                "id": "744556-4",
                "amount": "1000000000000"
              }
            ]
          }
        },
        {
          "id": "11AguFdYDRuNrfNo6AxoVyd6Y15EsDRzv841WtrS523aAF1",
          "myToAddress": {
            "nodes": [
              {
                "id": "198072-460",
                "amount": "100000000000"
              },
              {
                "id": "200865-275",
                "amount": "900000000000"
              }
            ]
          }
        },
        {
          "id": "11gh7WpYe5CKN82opEkrZUJsHeaFZa3pdEkEZFSMkV3k1Xj",
          "myToAddress": {
            "nodes": [
              {
                "id": "299922-5",
                "amount": "200000000000000"
              }
            ]
          }
        }
      ]
    }
  }
}
````