#### Check your React Native development environment for issues.

 ```html
npx react-native doctor
```
 
<table>
  <tr>
    <td >
    <img src="/images/react-native-doctor.png" alt="react-native-doctor"  />
    </td>
  </tr>
</table>

#### Check JVM and gradle-version

 ```html
gradle -v
```

<table>
  <tr>
    <td >
    <img src="/images/gradle-version.png" alt="gradle-version"  />
    </td>
  </tr>
</table>


#### Kill all running processes

 ```html
taskkill /m /im node.exe
```


 
#### Check running Gradle daemons .

 ```html
gradle --status
gradle --stop
```


#### Run code

 ```html
yarn start --reset-cache
```




####  Remove all previous Build files

>Deletes the build directory. Build starts from a clean slate, without any leftover files from previous builds.
 
  ```html

cd android
./gradlew clean
```



####  Create Apk file


  ```html
cd android
./gradlew :app:assembleRelease
```


####  Create AAB file


 ```html
cd android
./gradlew :app:bundleRelease
```
