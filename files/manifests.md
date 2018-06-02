# Manifests

## About
Manifests are used to quickly find and retrieve files that are related /
  required.  They describe the package they build by giving its name, version,
  dependencies, and build options. 

## Structure

**`<manifest>`**

```
<manifest config="{stringName}"
          label="{stringID}"
          versionCode="{integer}"
          versionName="{stringName}"
          installLocation=["auto" | "preset" | "env"]
</manifest>
```

## Usage
