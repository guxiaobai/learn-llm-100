

## MaxKB



```bash
mkdir /Volumes/THAWSPACE/.maxkb
mkdir /Volumes/THAWSPACE/.python-packages
```



```bash
docker run -d --name=maxkb --restart=always -p 8080:8080 -v /Volumes/THAWSPACE/.maxkb:/var/lib/postgresql/data -v /Volumes/THAWSPACE/.python-packages:/opt/maxkb/app/sandbox/python-packages 1panel/maxkb
```



## Ref



* <https://github.com/1Panel-dev/MaxKB>