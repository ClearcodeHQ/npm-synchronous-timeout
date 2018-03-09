# Synchronous timeout

A simple utility that allows you to set a synchronous timeout in your application.

## Installation

Add to your dependencies:

```
"dependencies": {
    "synchronous-timeout": "https://github.com/ClearcodeHQ/npm-synchronous-timeout.git"
}
```

# Usage

```
const timeout = require("sychronous-timeout");
await timeout(5000); //set in miliseconds
```