# Bloodhound-CustomQueries
Custom Queries - Brought Up to BH4.1 syntax.

A combination of custom cypher queries from various sources for [Bloodhound](https://github.com/BloodHoundAD/BloodHound), added categories to match newest version of BH. Some queries are straight from sources below however others are curated from all over. If you have others to add, just open a pull request and add the thanks to the list.

## How To
Copy the customqueries.json into the respective paths on your OS:

**Windows:**
```
%APPDATA%\bloodhound\customqueries.json
```

This translates to `C:\Users\<USERNAME>\AppData\Roaming\bloodhound\customqueries.json`.

**PowerShell:**
```powershell
$env:APPDATA\bloodhound\customqueries.json
```

**Command to copy the file to the correct location:**
```cmd
copy customqueries.json %APPDATA%\bloodhound\customqueries.json
```

**PowerShell command:**
```powershell
Copy-Item -Path .\customqueries.json -Destination "$env:APPDATA\bloodhound\customqueries.json"
```

**Linux/macOS:**
```bash
~/.config/bloodhound/customqueries.json
```

The BloodHound application will automatically look for custom queries in this location when it starts up, so placing your JSON file there will make the queries available in the BloodHound interface.

## Thanks
- [Azure Queries](https://github.com/hausec/Bloodhound-Custom-Queries)
     - [Ryan Hausknecht](https://twitter.com/Haus3c)
     - Additional Azure Queries - [Matt Powell](https://github.com/mpowelltech)
- [Certipy](https://github.com/ly4k/Certipy) Certificate Queries - [Oliver Lyak](https://twitter.com/ly4k_)
- [OS Version Queries + LAPS](https://github.com/myexploit/bloodhound-custom-queries)
     - [MyExploit2600](https://twitter.com/myexploit2600), Updated queries also merged in (https://twitter.com/myexploit2600/status/1529547082494881792)
