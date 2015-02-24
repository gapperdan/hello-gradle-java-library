#hello-gradle-java-library
Just a quick demo project for using gradle to create a java project structure.

Inside the directory you want to create your new java project in:
> \> gradle init --type java-library

###Setting the grade wrapper version in the project
Update **build.gradle** to add the wrapper task
>```javascript
task wrapper(type: Wrapper) {
	gradleVersion = ‘2.0'
}
```

Run the wrapper task:
> \> gradle wrapper

To check the gradle wrapper version:
> \> ./gradlew --version