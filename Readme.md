#User API Spesification

##Create User 
Endpoint : POST /api/users

Request Body :

```json
{
  "nama" : "salsa",
  "usia" : 21
}
```


Response Body (success) :

```json
{
  "data": {
    "id": "97a0b858-4a51-4fb4-b189-e03c9a0cfaa4",
    "name": "salsa",
    "usia": 21
  }
}
```


Response Body (failed) :

```json
{
  "error": "User not found"
}
```

##Delete User
Endpoint : DELETE /api/users/id

```json
{
  "message": "User deleted successfully"
}
```

Response Body (failed) :
```json
{
  "error": "User not found"
}
```

1. tambah data 
![tambahdata.png](../../../Users/Lenovo/Pictures/Screenshots/tambahdata.png)
2. update data
![updatedata.png](../../../Users/Lenovo/Pictures/Screenshots/updatedata.png)
3. delete data
![deletedata.png](../../../Users/Lenovo/Pictures/Screenshots/deletedata.png)
4. hasil tambah,delete,update
![hasill.png](../../../Users/Lenovo/Pictures/Screenshots/hasill.png)