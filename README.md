# getvba

A web interface for olevba, a script included in [oletools](https://www.decalage.info/python/oletools).
You can extract VBA macros from your *.xlsm files, without running Microsoft Excel.

## how to build

```sh
git clone https://github.com/takehiko/getvba.git
cd getvba
docker build --rm -t takehiko/getvba .
```

## running

```sh
docker run --rm -d -p 8000:8000 --name getvba takehiko/getvba
```

## browsing

<span>http</span>://(docker host):8000/cgi-bin/vba
