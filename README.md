# Documentation
https://docs.mongodb.com/manual/tutorial/install-mongodb-on-red-hat/#install-mongodb-community-edition


# Install of MongoDb

fill new repo data into "/etc/yum.repos.d/mongodb-org-4.2.repo" with :

[mongodb-org-4.2]
name=MongoDB Repository
baseurl=https://repo.mongodb.org/yum/redhat/$releasever/mongodb-org/4.2/x86_64/
gpgcheck=1
enabled=1
gpgkey=https://www.mongodb.org/static/pgp/server-4.2.asc


Then, launch the install with:

```
sudo yum install -y mongodb-org
```


# Run MongoDB (service)

```
sudo service mongod start
sudo chkconfig mongod on
```

To stop
```
sudo service mongod stop
```

To restart
```
sudo service mongod restart
```



# Tutorials
## To test mongo in nodejs
http://mongodb.github.io/node-mongodb-native/2.2/quick-start/quick-start/
## Mongoose
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/mongoose
## MEAN
https://www.supinfo.com/articles/single/4571-todo-app-une-introduction-au-mean-stack-mongodb-express-angular-2-nodejs

