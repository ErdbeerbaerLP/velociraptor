![Icon](./app/src/main/res/mipmap-mdpi/ic_launcher.png) Velociraptor
=========
Floating speed limit monitor for Android with speedometer and warning features.

[![Get it on GitHub](https://raw.githubusercontent.com/ErdbeerbaerLP/velociraptor/master/badge.png)](https://github.com/ErdbeerbaerLP/velociraptor/releases)

Get unmodified version here: [PlayStore](https://play.google.com/store/apps/details?id=com.pluscubed.velociraptor) | [GitHub](https://github.com/pluscubed/velociraptor)

### Modifications
Due to the original app being left discontinued, I have decided to fix a few issues

This version of the app fixes the following bugs:
- App list settings not saving since 1.7.0

### Development
- Put `google-services.json` from Firebase in /app/
- (Optional) Put `fabric.properties` in /app/ with apiSecret
- (Optional) Put `apis.xml` with overpass_api and debug_id in /app/src/main/res/values/
- (Optional) Put signing keys in gradle.properties/local.properties
    - RELEASE_STORE_FILE
    - RELEASE_STORE_PASSWORD
    - RELEASE_KEY_ALIAS_VELOCIRAPTOR
    - RELEASE_KEY_PASSWORD_VELOCIRAPTOR

```
Copyright (C) 2019  Daniel Ciao

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>
```
