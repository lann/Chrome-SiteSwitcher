Chrome extension clone of Firefox "Domain Switch" extension

To use:

1. Clone somewhere
1. Open Chrome's Extensions dialog (under preferences)
3. Tick the "Developer mode" box
4. Click "Load unpacked extension..."
5. Pick the repo directory
6. Click the Options link that appears
7. Fill in site name/domain pairs, e.g.:

```
Production  | www.example.com
Development | dev.example.com
Local       | localhost:8080
```

Visit one of the above domains. An icon should appear in the URL bar letting you switch domains.

