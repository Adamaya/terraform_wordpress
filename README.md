# terraform_wordpress
### how to run

create a empty pem file named mykey.pem

run command to download terraform package
``` 
terraform init
```

run command to download terraform package
``` 
terraform apply --auto-approve
```

### Error may come
- *operation invaild update*
this error come because windows support CR and LF both bu unix support LF only to resolve this issue update userdata file as given in following link ![https://www.youtube.com/watch?v=obqYfwzR-bQ]
