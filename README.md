# c8y-remoteaccess

:warning: Usage of this extension is discouraged as it will be incorporated natively in go-c8y-cli soon. In addition the integration will also support a new c8ylp replacement to natively create a local proxy connection to the device (e.g. with ssh etc.). You can track the progress here: https://github.com/reubenmiller/go-c8y-cli/pull/368

go-c8y-cli extension to managed Cumulocity IoT Cloud Remote Access Connection definitions

## What is included?

**Note**

Use ✅ or 🔲 indicates if the extension includes the given functionality or not.


|Type|Included|Notes|
|----|:-:|-----|
|Aliases|🔲|Some useful default command like `lookup <serialNumber>`|
|Commands|✅|Commands to manage the custom inventory managed object entities used in our IoT solution|
|Templates|✅|Some random data templates and common operations|
|Views|✅|Custom device and event views|

## Install

The extension can be installed using the following command.

```sh
c8y extension install reubenmiller/c8y-remoteaccess
```
