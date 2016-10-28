# email-newsletter

Here are the steps required to go from HTML/CSS files to ready-to-deploy email:

1. Copy all the CSS into the HTML file between the <style></style> tags
2. Copy and paste the new HTML file (with CSS included) into the CSS inliner tool at <a href="http://inliner.cm">inliner.cm</a>
3. Copy and paste the inlined HTML into etouches on the text screen - you should be able to see a decent preview of the email.
4. Test test test!  Keep in mind most people will be on some version of Outlook, even various versions of Outlook work differently across different operating systems.

A few tips:

* If you are making major changes to this email and have not done much work with HTML emails before, it is really worthwhile working through <a href="https://webdesign.tutsplus.com/tutorials/creating-a-future-proof-responsive-email-without-media-queries--cms-23919">this tutorial</a> first to understand a few of the methods and pitfalls with HTML email design

* The most common cause of issue in Outlook is matching closing tags for your HTML - if an email is rendering fine in other mail clients but acting weirdly in Outlook this is a very likely candidate.

* If you are adding new images, keep in mind the images need to be hosted somewhere - before uploading your email, upload the image to etouches, and add the image URL to the appropriate <code>src</code> tag so that you don't have to edit the email using the etouches in-browser editor.

