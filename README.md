## SIB FD api documentation



https://github.com/slatedocs/slate/wiki/Using-Slate-in-Docker

```
$ git clone https://github.com/slatedocs/slate
$ cd slate
# remove all files other than the `source` directory
$ docker pull slatedocs/slate
$ docker run --rm --name slate -v $(pwd)/build:/srv/slate/build -v $(pwd)/source:/srv/slate/source slatedocs/slate build
$ sudo chown -R suhail:suhail build/
```

open file build/index.html 

different theme: https://github.com/bestbuyapis/api-documentation