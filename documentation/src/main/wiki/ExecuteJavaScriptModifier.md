#### Execute Java Script Modifier

Execute Java Script Modifier is responsible for execute command as in webbrowser console.

Module name: **executejavascript**

##### Parameters

| Parameter | Value | Description | Mandatory |
| --------- | ----- | ----------- | --------- |
| `cmd` | command | webbrowser command | yes |

##### Example Usage

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<suite name="test-suite" company="cognifide" project="project">
    <test name="hide-test">
        <collect>
            <open />
            ...
            <executejavascript cmd="document.getElementById('toRemove').style.display='none'" />
            ...
            <resolution width="1200" height="760" />
            <screen />
            ...
        </collect>
        <compare>
            ...
        </compare>
        <urls>
        ...
        </urls>
    </test>
    ...
    <reports>
        ...
    </reports>
</suite>
```
