Eclipse Minify Plugin
===================

An incremental builder for minifying CSS and JavaScript.

Installation
-----------

You can install the plugin through its update site
[https://raw.githubusercontent.com/mnlipp/EclipseMinifyBuilder/gh-pages/update-site/](https://raw.githubusercontent.com/mnlipp/EclipseMinifyBuilder/gh-pages/update-site/).

Usage
-----

1. Enable the builder for your project in Project: `Configure` → `Enable Minify builder`.
2. Then, for each file that you want to be minified, configure a minifier in the file's properties dialog.
3. When you will `Build Project`, the plugin will build new minified files with the same names + the `.min` suffix.

Version 0.9.2 supports both YUICompressor and Google Closure Compiler.

Version 0.9.5 supports generation of source maps with the Google Closure Compiler.
