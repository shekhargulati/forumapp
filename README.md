forumapp
========

Demo application for JUDCon Brazil OpenShift workshop


```
rhc app create forumapp tomcat-7 postgresql-8.4
````

##Step 1 Basic Setup##

```
git rm -rf src pom.xml
git commit -am “deleted template project”
git remote add upstream -m master https://github.com/shekhargulati/forumapp.git
git pull -s recursive -X theirs upstream master
git checkout 3e8b88198bd981c27db562b8fd970beb05373f2b
```

## Step 2  Application Configuration Bootstraping##
```
git checkout 0771fd2445b06103895d1b10dfce5f35eb7f58ca
```

## Step 3 Enable JPA Repositories##
```
git checkout a8848ac0a0afcd6b4bb3a3cfa5a438d93487007c
```

## Step 4 Declarative Query##
```
git checkout f9baeb9ef4049d7d6e4a74572716c9a0d586c501
```

## Step 5 Enable Spring MVC##
```
git checkout fb4912ff379138bc099a67c97ee50e32950169f2
```

## Step 6 Application UI##
```
git checkout e8633490ef42068cb89184e07b74cfab72d46253
```

## Step 7 Enable OpenShift Profile##
```
git checkout e574b21844feded9b8838319c937f8b7c78b7ff5
```


