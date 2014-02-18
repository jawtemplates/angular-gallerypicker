angular-gallerypicker 
=================
created by J&W Templates

<br>
Angular directive for <b>Wordpress</b> native gallerypicker.

* Compatible with wordpress 3.5+

Using
-----
Add to your form this directive:
```echo '<div gallerypicker ng-model="gallery"  ng-init="gallery = JSON.parse(\'' . addslashes(str_replace('"', '\'', $meta)) . '\');" ></div>';```