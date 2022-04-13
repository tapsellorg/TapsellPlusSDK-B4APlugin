# Changelog

## v2.1.7
- Update targetSDK to 31
- Update `tapsell` ad network to `4.7.4`
- Update `adcolony` ad network to `4.6.5`
- Update `applovin` ad network to `10.3.4`
- Update `unity-ads` ad network to `3.7.5`
- Update `admob` ad network to `20.6.0`
- Add support for `mintegral` ad network `15.7.41`
- Support `app-set-id` due to removal of `GoogleAdvertisingId` (Adds `playService:appset`:16.0.2)
- Add `AD_ID` permission to essential
- Fix network issue on old devices (Adds `playService:auth`)
- Fix an error in admob native banner
- Update tapsell plus native to `2.1.7`
- New: Give more verbose error if `tapsellplus.SetDebugMode` was called (with any argument, preferably `3`)


## v2.1.4
- Fix multiple ad request by adding `zoneId` as the first params

```
// before
TapsellPlus_OnResponse (responseId As String)

// New
TapsellPlus_OnResponse (zoneId As String, responseId As String)
```

- Fix onRewarded callback not called on some situations

## v2.1.3
- Initialize release
- Basic implementation of native tapsell-plus SDK

## v2.0.0
- Blank release
