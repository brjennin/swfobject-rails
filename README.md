Rails 3.x Integration for swfobject
==

This gem integrates [swfobject](http://code.google.com/p/swfobject/) with the Rails 3.x asset pipeline. It has been tested with Rails 3.1 and 3.2.


Install
--

Just add it got your Gemfile:

    gem 'swfobject-rails'


Quick Start
--

Add to your application.js:

    //= require swfobject

Place your SWFs you want to incude somewhere in the rails assets directories (ex. app/assets/swfs/...).

In your view you can now do:

    <%= swf_tag "video" %>


Updating
--
When new versions swfobject are released, simply update the gem to the latest version.

