## Steps to reproduce

1. Try to build project
```shell script
      ./gradlew build
```
2. Build fails with error:
```
Task :shadowJar FAILED
A problem was found with the configuration of task ':shadowJar' (type 'ShadowJar').
> No value has been specified for property 'mainClassName'.
``` 

