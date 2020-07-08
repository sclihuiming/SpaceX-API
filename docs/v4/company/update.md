# Update company info

**Method** : `PATCH`

**URL** : `https://api.spacexdata.com/v4/company/:id`

**URL Parameters** : `id=[string]` where `id` is the ID of the company

**Auth required** : `True`

**Body** :

```json
{
  "employees": 8000
}
```

## Success Response

**Code** : `200 OK`

**Content example** : `OK`

## Error Responses

**Code** : `400 Bad Request`

**Content** : Mongoose error is shown, with suggestions to fix the query.
