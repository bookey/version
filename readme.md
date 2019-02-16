# doc version control



1. create a new folder
2. Create a new file
3. init git lib

``` sh
pushd ~/Desktop

git init
```





1st commit

``` sh
# pack
git add h1.py

# deliver to library
git commit -m"first commit nothing in there"
```



update after 1st commit

update source code h1.py

``` python
# before
```



``` python
# after
print('new content!')
```



status review

``` sh
git status
```



check update (diff between before and after)

``` sh
git diff
```



2nd commit

```sh
# pack
git add h1.py

# deliver to library
git commit -m"2nd commit add 1 one code"
```





## version review


``` sh
git log
```





## version select









## code updated!


``` sh
git pull
```

