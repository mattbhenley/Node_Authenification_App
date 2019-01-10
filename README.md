# Node_Authenification_App
API for registering users using MongoDB. Authentication using a json web token. 

### Version
1.0.0

## Usage

```bash
npm install
```

```bash
npm start
```

## Endpoints
```bash
POST /users/register
```

```bash
POST /users/authenticate   // Gives back a token
```

```bash
GET /users/profile         // Needs json web token to authorize
```
