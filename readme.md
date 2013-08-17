# MyImages for PyroCMS

MyImages is a PyroCMS module (plugin) to display images in layout files. It can display image data, image tag and image tag inside a anchor tag. Also can display all these taken from the folder.

- version - 1.0.0
- Author  - Tanel Tammik - keevitaja@gmail.com

## Install

Just copy module to your modules folder and install it. Backend in admin section is not available.

## Plugin

All methods in library Myimages.php can be called from plugin.

### `{{ myimages:url_thumb }}`

Returns url of the thumb image.

	{{ myimages:url_thumb id="45e7c41ad7dd006" width="200" height="150" mode="fit" }}

##### params

- `id` - image id (required)
- `width` - image width (defaults to auto)
- `height` - image height (defaults to auto)
- `mode` - image resizing mode (defaults to fit), please refer to [pyrocms docs](http://docs.pyrocms.com/2.2/manual/plugins/files)

### `{{ myimages:url_large }}`

Returns url of the large image.

##### params

- `id` - image id (required)
