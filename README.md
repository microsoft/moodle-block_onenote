# Moodle Plugins for Microsoft Services
*including* **Office 365** *and other Microsoft services*

## Microsoft OneNote Block

This plugin provides a container for the Microsoft Account signin button and also Microsoft OneNote related action buttons.


Design details
--------------

There are several parts that make up the Microsoft OneNote Online API Local plugin.

### Configuration
None. This plugin depends upon the Microsoft Account local plugin to be configured for accessing the appropriate Microsoft Live application.
It is recommended that this block should be configured to appear on all pages throughout the entire site.

### get_content method
This is the standard block get_content method that returns either the Microsoft Account signin widget if the user hasn't signed in yet or the appropriate OneNote action button if so.

### Plugin dependencies
block_onenote => local_onenote => local_msaccount


This is part of the suite of Microsoft Services plugins for Moodle.

This repository is updated with stable releases. To follow active development, see: https://github.com/MSOpenTech/o365-moodle

# Contributing

Before we can accept your pull request, you'll need to electronically complete Microsoft Open Tech's [Contributor License Agreement](https://cla.msopentech.com/). If you've done this for other Microsoft Open Tech projects, then you're already covered.

[Why a CLA?](https://www.gnu.org/licenses/why-assign.html) (from the FSF)

# Copyright

&copy; Microsoft Open Technologies, Inc.  Code for this plugin is licensed under the GPLv3 license.

Any Microsoft trademarks and logos included in these plugins are property of Microsoft and should not be reused, redistributed, modified, repurposed, or otherwise altered or used outside of this plugin.