# JSON-Resume-Paperalt

This is an alternative version of the paper theme for [JSON Resume](http://jsonresume.org/).
Visit the original theme's repo [here](https://github.com/TimDaub/jsonresume-theme-paper).

It can be installed via npm with:

```
npm install jsonresume-theme-paperalt
```

## Alterations

* Added an **About** section
* Slightly increased the font size of section texts
* Changed the variable name checked in the template from `website` to `url` to conform with the [default schema naming convention](https://raw.githubusercontent.com/jsonresume/resume-schema/v1.0.0/schema.json)
* Postal code label is now separated from city
* Added support to the projects section, with an optional link following each project's name and an optional project source code link at the bottom of the summary. Project source link can be used by defining a `sourceUrl` string inside a project object in `resume.json` 