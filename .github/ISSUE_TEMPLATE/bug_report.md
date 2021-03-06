---
name: Bug report
about: Create a report to help us improve
---

### What version of Hls.js are you using?

### What browser and OS (including versions) are you using?

### Test stream:

<!-- If possible, please provide a test stream or page -->
<!-- You can paste your stream into the demo and provide the permalink here -->

### Configuration:

<!-- Describe the hls.js configuration and any additional player setup steps -->

```
{
  "debug": false,
  "backBufferLength": 60
}
```

### Checklist

<!-- Replace [ ] with [x] to check off the list -->

- [ ] The issue observed is not already reported by searching on Github under https://github.com/video-dev/hls.js/issues
- [ ] The issue occurs in the stable client on https://hls-js.netlify.com/demo and not just on my page
<!-- The stable client is built from the latest release -->
- [ ] The issue occurs in the latest client on https://hls-js-dev.netlify.com/demo and not just on my page
<!-- The latest client is built from the head of the master branch -->
- [ ] The stream has correct Access-Control-Allow-Origin headers (CORS)
- [ ] There are no network errors such as 404s in the browser console when trying to play the stream

### Steps to reproduce

1. Please provide clear steps to reproduce your problem
2. If the bug is intermittent, give a rough frequency

### Expected behavior

_What you expected to happen_

### Actual behavior

_What actually happened_

### Console output

```
Paste the contents of the browser console here (with `debug` enabled in your config).
```

```
For media errors reported on Chrome browser, please also paste the output of chrome://media-internals
```
