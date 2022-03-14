# Changelog

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
