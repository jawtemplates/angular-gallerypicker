angular-gallerypicker 
=================
created by J&W Templates

<br>
Angular directive for <b>Wordpress</b> native gallerypicker.

* Compatible with wordpress 3.5+

Using
-----
Add to your form this directive:

```echo '<div gallerypicker name="NAME" ng-model="gallery"  ng-init="gallery = JSON.parse(\'' . addslashes(str_replace('"', '\'', $meta)) . '\');" ></div>';```

You must have linked also mce-view.js (wordpress library).  
```wp_enqueue_script('mce-view');```
In post (custom post) editor is linked automatically by WP.