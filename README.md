SpringSkelleton
===============
A little spring skelleton for initialize spring apps, I use this build.gradle file to init my spring apps.
Copy the build.gradle that you need and modify it as you need.


Build on Terminal
===============
```
gradle build - This will download all the necessary sources and librarys
gradle eclipse - This will generate eclipse meta data
gradle bootRun - This will run the project too
gradle war - This will generate the WAR for tomcat run
gradle wrapper - This will generate a gradle 2.2.1 wrapper based (high recommended)
```

Directory structure:
===============
```
|----src
   |----main
      |----java
         |----(package)
      |----resources
         |----templates
            |----(templates.html)
```

Licence
===============
```

   Copyright 2014 Leonardo Rossetto <leonardoxh@gmail.com>

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
   
```
