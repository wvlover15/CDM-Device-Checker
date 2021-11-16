# CDM-Device-Checker

Easily parse the cdm device info from: https://tools.axinom.com/decoders/LicenseRequest
By passing the license base64 in the argument.

## USAGE:

```
py check_device.py test  
or  
py check_device.py "license_base64"
```

# RESULT

```json
{
    "status": "Active",
    "systemId": "4464",
    "securityLevel": "3",
    "manufacturer": "Generic Field Provisioning",
    "model": "Android KLP x86",
    "modelYear": "2013",
    "modelName": "Android SDK built for x86",
    "systemOnChip": "android generic",
    "type": "software",
    "AdditionalInfo": {
        "applicationName": null,
        "architectureName": "x86",
        "buildInfo": "google/sdk_google_phone_x86/generic_x86:7.1.1/NYC/5464897:userdebug/test-keys",
        "companyName": "Google",
        "deviceId": "zdfDCPHaHrBQakqKhEcFqXiLwbblJwg",
        "deviceName": "generic_x86",
        "productName": "sdk_google_phone_x86",
        "widevineCdmVersion": "v4.1.0-android"
    }
}
```
