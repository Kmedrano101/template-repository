# API Reference

## Base URL

```
https://api.example.com/v1
```

## Authentication

Describe the authentication method used (e.g., API key, OAuth 2.0, JWT).

## Endpoints

### `GET /resource`

**Description:** Retrieve a list of resources.

**Headers:**

| Header          | Value              | Required |
|-----------------|--------------------|----------|
| Authorization   | Bearer `<token>`   | Yes      |

**Query Parameters:**

| Parameter | Type   | Description          | Required |
|-----------|--------|----------------------|----------|
| page      | int    | Page number          | No       |
| limit     | int    | Items per page       | No       |

**Response:**

```json
{
  "data": [],
  "total": 0
}
```

### `POST /resource`

**Description:** Create a new resource.

**Request Body:**

```json
{
  "name": "string",
  "description": "string"
}
```

**Response:** `201 Created`

## Error Codes

| Code | Description              |
|------|--------------------------|
| 400  | Bad Request              |
| 401  | Unauthorized             |
| 403  | Forbidden                |
| 404  | Not Found                |
| 500  | Internal Server Error    |
