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
<img width="1920" height="1080" alt="tambahdata" src="https://github.com/user-attachments/assets/977f02f1-692a-4dda-9ef0-00ef56c80966" />

2. update data
<img width="1920" height="1080" alt="updatedata" src="https://github.com/user-attachments/assets/732e6b1d-7dc5-4658-80c7-189fe46872fb" />

3. delete data
<img width="1920" height="1080" alt="deletedata" src="https://github.com/user-attachments/assets/3c041c51-285a-404f-bcab-10581e59d9ee" />

4. hasil tambah,delete,update
<img width="1920" height="1080" alt="hasill" src="https://github.com/user-attachments/assets/3cdc8cca-9720-4d11-8233-c27b27debbb6" />

