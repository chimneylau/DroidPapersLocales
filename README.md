DroidPapersLocales
==================

All language files for DroidPapers.

<h3>DroidPapers</h3>

DroidPapers gives an overview of wallpapers and ringtones for official stock and famous ROMs of Android. Download the wallpaper or ringtone you like and set it from within the app. App is and stays ad-free.

Read more about it here: http://droidpapers.teusink.org/about.php

<h3>Folder structure</h3>
- json (all language files used in the web part of the app)
- market (all translations used for the app-stores)
- data (all language files used in the native part of the app)

<h3>If you want to help</h3>
- Translate all language files to your desired language.
- Make sure that the language is listed here as an ISO 639-1 code: http://www.loc.gov/standards/iso639-2/php/code_list.php
- You can put your name and website (or profile to some social media) for credits in the bottom of the JSON file. It will be viewable in the app.
- Submit your changes through GitHub or send me the files directly.
- Your work is entirely voluntary. Your help is very much appreciated though!

<h3>What you must not translate</h3>
All words below should and must not be translated.

- DroidPapers
- AutoChanger
- ShakeChanger
- DroidPapersLocales
- Joram
- Teusink
- Teusink.org
- HTML5
- CSS3
- JavaScript
- jQuery Mobile
- PhoneGap
- GitHub
- ```<a [id / href]></a>```
- ```<br />```
- \n
- INTERNET
- ACCESS_NETWORK_STATE
- WRITE_EXTERNAL_STORAGE
- SET_WALLPAPER
- READ_PHONE_STATE
- READ_EXTERNAL_STORAGE
- WRITE_SETTINGS
- RECEIVE_BOOT_COMPLETED
- VIBRATE
- /sdcard/Pictures/DroidPapers
- /sdcard/Ringtones/DroidPapers
- /sdcard/Notifications/DroidPapers
- /sdcard/Alarms/DroidPapers
- /sdcard/DroidPapers

<h3>What you should translate in JSON</h3>
In the example below you only need to translate the x. The identifiers a, b, and c should not be translated. All {, }, " and : should be left in place.

```
{
	"a": {
		"a" : "x",
		"b" : "x",
		"c" : {
			"a" : "x"
		}
	},
	"b" : "x",
	"c" : "x"
}
```

<h3>What you should translate in DATA (XML)</h3>
In the example below you only need to translate the x. The identifiers a, b, and c should not be translated. All <, >, ", ? and the xml and resource tags should be left in place.
```
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="a">x</string>
	<string name="b">x</string>
	<string name="c">x</string>
</resources>
```

<h2>Languages</h2>

<table>
<tr>
	<th>Language</th>
	<th>JSON</th>
	<th>XML</th>
	<th>Contributor</th>
	<th>Link</th>
<tr>
<tr>
	<td>Chinese 中文</td>
	<td>zh-hk</td>
	<td>values-zh-hk</td>
	<td>Ron Tam</td>
	<td></td>
</tr>
<tr>
	<td>Dutch</td>
	<td>nl</td>
	<td>values-nl</td>
	<td>Joram Teusink</td>
	<td><a href="https://plus.google.com/+JoramTeusink/">Google+ Profile</a></td>
</tr>
<tr>
	<td>English</td>
	<td>en</td>
	<td>values</td>
	<td>Joram Teusink</td>
	<td><a href="https://plus.google.com/+JoramTeusink/">Google+ Profile</a></td>
</tr>
<tr>
	<td>Italian</td>
	<td>it</td>
	<td>values-it</td>
	<td>Giampaolo Frello</td>
	<td><a href="https://plus.google.com/u/0/+GiampaoloFrello/">Playboard Profile</a></td>
</tr>
</table>

<h2>License</h2>

All work in this repo is released under the GNU LesserGeneral Public License.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU LesserGeneral Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details. To read more about the GNU Lesser General Public License that belongs to this program, see http://www.gnu.org/licenses/