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

