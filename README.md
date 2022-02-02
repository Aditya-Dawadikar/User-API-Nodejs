
# User APIs

Nodejs Assignment

## API Reference

#### signup

```http
  POST /api/user/signup
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| Body | JSON | **Required**. username and password |

#### login

```http
  POST /api/user/login
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| Body | JSON | **Required**. username and password |

#### get all users

```http
  GET /api/user/all
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Authorization` | `Bearer Token` | **Required**. Your JWT |

#### get user by username

```http
  GET /api/user/:id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Authorization` | `Bearer Token` | **Required**. Your JWT |

#### update user by username

```http
  PUT /api/user/:id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Authorization` | `Bearer Token` | **Required**. Your JWT |
| `Body` | `JSON` | **Required**. parameters to be updated |

#### delete user by username

```http
  DELETE /api/user/:id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Authorization` | `Bearer Token` | **Required**. Your JWT |

#### update user password

```http
  PUT /api/user/:id/changepassword
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Authorization` | `Bearer Token` | **Required**. Your JWT |
| `Body` | `JSON` | **Required**. password to be updated |
