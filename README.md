Bootstrap Scroll Modal
=====================

Twitter Bootstrap's current modal has a fixed height and scrolls long content inside of it. This version of the plugin, along with some minimal CSS allows you to have a modal that acts more like Facebook and Trello modals, where the content can be any height and the whole page scrolls, rather than internal scrollbars in the modal.

You can try a demo here: http://ericanderson.ca/bootstrap_scroll_modal_demo/

How to Use
----------

Simply use this version of the Modal Plugin rather than Twitter Bootstraps. It works exactly the same way the original plugin does. There are only minor differences which relate to how the HTML markup is inserted, which allows for the full page scroll.

Then include the Stylesheet. Ensure to include it AFTER bootstrap.css, as it overrides some of the modal classes found in it. You can also just add the minmal CSS to one of your project's CSS files, as long as it comes after Bootstrap.css.

Cross-Browser Tested
--------------------

I've tested the modal on IE7+, Safari, Firefox 4+ and Chrome. Let me know if you find any compatibility issues.