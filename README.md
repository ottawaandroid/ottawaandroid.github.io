ottawaandroid.github.io
=======================
The Ottawa Android website and blog.

Creating Content
================
If you are only interested in creating content, then this is the only section you
really need to read. You can ignore the ``archived_posts`` folder from the old
blog.

Posts
-----
Posts are inside the ``_posts`` folder. To create a new post, simply
create a new file in that folder following the same naming convention as the other
posts. Make sure to include the proper metadata at the top of the file.

To keep things organized, we group all posts for a given year in the same sub folder.
The internal structure of the ``_posts`` directory does not determine the final url.
The final url (and publishing date) is based on the filename for the post.

Pages
-----
Non underscore folders are browsable by the web. This means that for the ``contact``
page, the associated page file will be inside the ``contact`` folder in a file called
``index.md``.

Development
===========
To run a local copy of the site while developing, execute ``jekyll server --watch`` 
in the project root directory.

You can have sass watch for file changes when working on the CSS by executing
``sass --watch css/style.scss:css/style.css --style compressed`` in another terminal.
It will automatically recomple/minify the CSS as you make changes and save the files.
