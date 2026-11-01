PitchLog online update
1. In Firebase: add the Android app (package com.pitchlog.scorer, SHA-1 from the chat), download google-services.json.
2. In GitHub upload/replace: www/index.html, package.json, capacitor.config.json, debug.keystore, google-services.json, and edit .github/workflows/build-apk.yml.
3. Paste firestore.rules into Firebase > Firestore > Rules > Publish.
