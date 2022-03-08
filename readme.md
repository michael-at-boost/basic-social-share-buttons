# Basic Social Share Buttons

Contributors: basicbydesign  
Tags: social shares, social buttons, share buttons, social share buttons  
Requires at least: 5  
Tested up to: 5.9.1  
Stable tag: 1.0.1  
Requires PHP: 7.0  
License: MIT  
License URI: https://opensource.org/licenses/MIT

Basic Social Share Buttons. Easily stylable. Fast loading. No Javascript. No tracking.

## Description

Basic Social Share Buttons allows your users to share posts to social networks without loading any javascript.

## Configuration

Admin options are in the Wordpress admin under Reading.

You can choose between three button sizes:

- Small - Icon only
- Medium - Icon + site name
- Large - Icon + "Share on " + site name

You can choose to include the css (via wp_enqueue) or you can disable the enqueue and the css rules will be shown in admin for you to insert in your main stylesheet (for one less http request).

## Usage

Use the short `[basic-share-buttons]` in your post content.

or in a php template its `<?php echo do_shortcode('[basic-share-buttons]'); ?>`

The title and URL are taken from Wordpress's `the_title()` and `the_permalink()` functions.

You can override both as parameters to the shortcode.
`[basic-share-buttons title='Your custom page title' url='http://customurl.com/page']`

## Screenshots

![Admin settings (Large buttons)](.wordpress-org/screenshot-1.png)
![Admin settings (Medium buttons)](.wordpress-org/screenshot-2.png)
![Admin settings (Small buttons)](.wordpress-org/screenshot-3.png)
![Admin settings (CSS dumped to be included in your main stylesheet)](.wordpress-org/screenshot-4.png)
![Buttons on page ](.wordpress-org/screenshot-5.png)

## Changelog

### 1.0.1

- Shortcode added to admin page

### 1.0

- Initial launch

## Copyright

This plugin includes code from:

- SortableJS [https://github.com/SortableJS/Sortable](https://github.com/SortableJS/Sortable) - [MIT License](https://github.com/SortableJS/Sortable/blob/master/LICENSE)
- Sharing Buttons io [https://github.com/mxstbr/sharingbuttons.io](https://github.com/mxstbr/sharingbuttons.io) - [MIT License](https://github.com/mxstbr/sharingbuttons.io/blob/master/LICENSE.md)
