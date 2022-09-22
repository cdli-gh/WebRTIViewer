This is a fork of [WebRTIViewer](http://vcg.isti.cnr.it/rti/webviewer.php), "a HTML5-WebGL viewer for high resolution RTI images (PTM and HSH) and standard images (JPEG, PNG and TIF)."

The original version of the code was originally distributed under the [GNU General Public Licence version 3](LICENSE). A number of changes were made:

  - Only the CSS, JS, GLSL, and icon files were kept.
  - Some unused files (minified versions of CSS & JS files, unused jQuery UI icons) were removed.
  - The remaining CSS file was modified to allow for the viewer to be embedded in a larger page, by scoping the rules to the HTML id of a container element.
  - The code used to get the shader files was modified to work for the CDLI framework.

These changes are shown in detail on [this page](https://github.com/cdli-gh/WebRTIViewer/commit/32e6a1c).
