# SunDatePicker
Date picker for Iranian calendar

### Version 2.1.3
add scrolling between years with months arrows


## Screenshots

<img src="/Preview.jpg"/>

<a href="https://play.google.com/store/apps/details?id=com.afkar.sundatepicker">
  <img alt="Android app on Google Play" src="https://play.google.com/intl/en_us/badges/images/badge_new.png" />
</a>

## Getting started

### Dependency

```
dependencies {
	        implementation 'com.github.a3dh4m3d:SunDatePicker:2.1.3'
}
```

### Usage

```java
 new DatePicker.Builder()
            .id(id)
            .minDate(minDate)
            .maxDate(minDate)
            .date(initialDate)
            .build(MainActivity.this)
            .show(getSupportFragmentManager(), "");
```

# Licence

    Copyright 2016 Alireza Afkar
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
