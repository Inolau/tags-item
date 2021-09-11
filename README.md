## tags-item
An Oracle APEX plugin for a tags item, based on jQuery plugin [itemTags.js](http://betaweb.github.io/inputTags-jQuery-plugin/).
The main difference is that a tag is not editable, but a tag can optionally have a link to another page.

### Preview

![Preview](https://github.com/Inolau/tags-item/blob/main/tagsitem.gif)

### Demo

[TagsItem demo](https://apex.oracle.com/pls/apex/ino/r/share/products)

### Custom Attributes

**Maximum number of tags** Maximum number of tags you can enter in a tag item.\
**Tag link** Optional link to another page when clicking on a tag. Use !TAG! to pass the value of tag.\
**Tags LOV query** Optionally, a one column query that retuns a list of tags to choose from.\
**Allow other values** In case of a Tags LOV query, can you enter a value that is not in the LOV?

### Versions

The plugin was built in APEX 20.2, but the code can be used in lower versions to create a plugin for older APEX applications.

### Installation

Download item_type_plugin_com_ilaurensse_tagsitem.sql from the sourrce directoy.

Import this plugin into your APEX applications.
