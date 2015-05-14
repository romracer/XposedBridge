Your local.properties should look something like this:

```
# location of the SDK. This is only used by Ant
sdk.dir=/path/to/android-sdk-linux

key.store=/path/to/release.keystore
key.alias=release

store.pass=password
key.pass=changeme
```

Build with ```./gradlew clean && ./gradlew assembleRelease```
