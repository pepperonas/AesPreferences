# AesPreferences
This tiny Android library provides encryption for the SharedPreferences.


## How to use
### 1. Import
Add JitPack to your repositories:

```
   repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
```

and add the library to your dependencies:

```
    compile 'com.github.pepperonas:aespreferences:0.0.6'
```


## ProGuard
```
-keep class com.pepperonas.aespreferences.** { *; }
-dontwarn com.pepperonas.aespreferences.**
```


## Developed By

* Martin Pfeffer - https://celox.io - <martin.pfeffer@celox.io>


## License

    Copyright 2017 Martin Pfeffer

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


