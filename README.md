# How to use in your project

###add to your dev dependencies:

```json
"eslint": "^7.29.0",
"eslint-config-propergate": "git+https://github.com/propergate/eslint-config-propergate#TAG",
```

(replace TAG to current version)

### add configuration to package.json

```json
"eslintConfig": {
    "extends": "propergate"
},
```

# How to deploy new version

1. update version in package.json
2. create git tag with name = new version
3. update version in your project
