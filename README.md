Run ```npx playwright test --project=chromium -c playwright.service.config.ts --workers=10 -g testDownload.test.ts```

Ensure that the first execution fails with error waiting for event "download"
============================================================

Failed worker ran 1 test:, try again if it doesnt

Observe that if run locally it does not fail

