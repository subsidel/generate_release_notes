# Generate Release Notes

This generates two files
```notes.html``` a view of your change logs and readme
```changelogs.json``` the github dump

## Usage

Install using

```npm i -g generate-release-notes```

You need the following param

* ```--repo=:owner/:repo```

The following params are optional

* ```--save-to=folder_location``` saves notes.html and changelog.json to this folder, defaults to ```./```
* ```--token=xxx``` the github oatuh token
* ```--from-tag-name=x.x.x.x.x.x...``` assumption it is 
a versioned number
* ```--last-releases=X``` gets the last X releases
* ```--readme-location=file_location``` this will be in the top of notes.html, will not be present when not given
* ```--style-sheet-location``` adds style sheet for notes.html, will still look like readme
* ```--usage``` or ```--help``` exits and displays this message