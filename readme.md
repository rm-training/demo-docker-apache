# More exploration of docker

# Based on...

Create an `index.html` file

Then run this:
```
docker run -ti -v "$PWD":/usr/local/apache2/htdocs/ -p 8080:80 httpd:2.4
```

Then visit `http://localhost:8080`

# Sources

* https://increment.com/development/an-introduction-to-local-development-with-containers/