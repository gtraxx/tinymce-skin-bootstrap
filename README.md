tinymce-skin-bootstrap
======================

A template for tinyMCE based on Twitter Bootstrap

Authors
-------

 * Gerits Aurelien (Author-Developer) contact[at]aurelien-gerits[point]be

Official link in french : http://blog.aurelien-gerits.be/2013/01/09/tinymce-skin-twitter-bootstrap/

###Screenshot

![tinyMCE thème bootstrap](http://blog.aurelien-gerits.be/wp-content/uploads/2013/01/skin-tinymce-bootstrap-2013-1-9.png "tinyMCE thème bootstrap")

###Installation
 * Download skin
 * Unzip archive
 * Move folder bootstrap in tinyMCE (tiny_mce/themes/advanced/skin/)


Example
---------------------
<pre>
tinyMCE.init({
        // General options
        mode : "textareas",
        theme : "advanced",
        skin : "bootstrap",
        plugins : "table,inlinepopups",

        // Theme options
        theme_advanced_buttons1 : "bold,italic,underline,strikethrough,|,justifyleft,justifycenter,justifyright,justifyfull,|,styleselect,formatselect,|,table,removeformat,code",
        theme_advanced_buttons2 : "",
        theme_advanced_buttons3 : "",
        theme_advanced_buttons4 : "",
        theme_advanced_toolbar_location : "top",
        theme_advanced_toolbar_align : "left",
        theme_advanced_statusbar_location : "bottom",
        theme_advanced_resizing : true,

        // Example content CSS (should be your site CSS)
        content_css : "/js/tinymce/examples/css/content.css"
});
</pre>

####Demo
Coming soon

Licence
------------

<pre>
TinyMCE skin Bootstrap

Copyright (C) 2013 Gerits Aurelien (Author - Developer) contact[at]aurelien-gerits[point]be

Redistributions of files must retain the above copyright notice.
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

####DISCLAIMER

Do not edit or add to this file if you wish to upgrade tinyMCE skin Bootstrap to newer
versions in the future. If you wish to customize tinyMCE skin Bootstrap for your
needs please refer to aurelien-gerits.be for more information.
</pre>
