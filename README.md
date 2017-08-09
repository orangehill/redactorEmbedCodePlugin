embedCode is a [Redactor](https://imperavi.com/redactor/) plugin that allows users to insert embed codes from e.g. social websites (Instagram, Twitter, Facebook, Pinterest etc.)

Based on the [Redactor Video Plugin](https://imperavi.com/redactor/plugins/video/) code.

Usage

1. Include the file.
2. Add the 'embedCode' to Redactor configuration object under 'plugins'. 

Example:

```
$('#redactor').redactor({
    'plugins': [ 'embedCode' ]
});
```

Note: The plugin is assuming the usage of [Font Awesome](fontawesome.io/) icon set. If you'd like to change the class used, edit the following per your liking:

```<i class="fa fa-code"></i>```
