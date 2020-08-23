### To create user
```
use id
db.createUser({
    user: 'id',
    pwd: 'password',
    roles: [
        { role: 'readWrite', db: 'nera' }
    ]
})
```
```
mongodb://id:password@mongo.csuos-infra.svc/id?authSource=id&retryWrites=true&w=majority
```

### Admin id/password
https://vault.csuos.ml/ui/vault/secrets/admin/show/mongo