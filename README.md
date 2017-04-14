## Keyboard-layouts for Judeo-Tat in Cyrillic, Latin, and Hebrew

For all three keyboard layouts, I made an effort to keep commonly used non-letter characters still easily accessible. In all three alphabets, Judeo-Tat uses a large subset of the commonly used letters. I then replaced the letters not used in Judeo-Tat with the uncommon letters found in Judeo-tat.  

To add this keyboard layout in Linux, add the following code to your `/usr/share/X11/xkb/rules/evdev.xml` file. 

```
     <layout>
      <configItem>
        <name>jdt-lat</name>
        <shortDescription>jdt-lat</shortDescription>
        <description>Judeo-Tat (Latin)</description>
        <languageList><iso639Id>jdt</iso639Id><iso639Id>jdt-lat</iso639Id></languageList>
      </configItem>
    </layout>
     <layout>
      <configItem>
        <name>jdt-cyr</name>
        <shortDescription>jdt-cyr</shortDescription>
        <description>Judeo-Tat (Cyrillic)</description>
        <languageList><iso639Id>jdt</iso639Id><iso639Id>jdt-cyr</iso639Id></languageList>
      </configItem>
    </layout>
     <layout>
      <configItem>
        <name>jdt-heb</name>
        <shortDescription>jdt-heb</shortDescription>
        <description>Judeo-Tat (Hebrew)</description>
        <languageList><iso639Id>jdt</iso639Id><iso639Id>jdt-heb</iso639Id></languageList>
      </configItem>
    </layout>
```
