#Social Media Sharing
Inject Social Media FontAwesome Icons and makes button shareable.

#Configure

To inject the icons into your web page, add this file in the footer/header of your page and change the following:
Set where the icons will be inserted!

If you are using the jquery version (social-media.js) then follow the below setup:

Change the below variable with the CLASS/ID of your HTML tag where you want the icons to be inserted.

var attachedParent = '.socialMedia';

If you are using the JavaScript setup (social-media-js.js) then make sure that attachedParent refers to an ID.
Email configuration

The below variables needs to be modify if you would like to share the content over email

var subject = encodeURI('Lorem Ipsum');

var message = encodeURI('dolor sit amet, consectetur adipiscing elit. Integer tempor vehicula tristique');