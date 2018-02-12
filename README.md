# README

This test shows the changes made to `many.rb`.

To test, bundle install, start development server and open a browser to: http://localhost:3000/posts/

Create a test post and attach several files. You can then edit the post and delete only the files that you want to.

You can also test the purge all behavior by removing the argument from `if @post.images.purge(@attachment_id)` in the posts controller and it will delete all attachments.