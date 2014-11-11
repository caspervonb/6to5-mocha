# 6to5-mocha

**package.json**

```json
{
  "scripts": {
    "test": "mocha"
  },
  "dependencies": {
    "6to5": "*",
    "mocha": "*"
  }
}
```

**test/mocha.opts**

```
--require 6to5/register
```
