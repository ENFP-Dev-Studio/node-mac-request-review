# node-mac-request-review

A Native module to show App Store review requesting UI. It tells StoreKit to ask the user to rate or review the app.  

<p align="center">
  <img center width="532" alt="image" src="https://user-images.githubusercontent.com/57121116/209694268-af2d01c0-d6ef-4141-9e94-dd3b2453d0b2.png">
</p>

### Note
This API is wrapping [Storekit:requestReview](https://developer.apple.com/documentation/storekit/skstorereviewcontroller/2851536-requestreview).  
I create this library for [Capture Note](https://capture-note.enfpdev.com).

### How To Install

```bash
$ yarn add node-mac-request-review
```

### How to Use

```typescript
import { requestReview } from "node-mac-request-review";

// Ask Review
requestReview();
```


