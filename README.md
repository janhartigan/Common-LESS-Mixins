Common-LESS-Mixins
==================

This is a list of common mixins for LESS CSS. These are common things that potentially make any CSS simpler to write and read. For example, if you want your element to have a 5px border radius, normally you have to write:

<pre>
-moz-border-radius:5px;
border-radius:5px;
-webkit-border-radius:5px;
background-clip:padding-box;
</pre>

But with the common LESS mixins, all you'd have to write is:

<pre>
@borderRadius(5px);
</pre>

Simple as that! I'll eventually get around to writing a more complete reference guide, but for now this is mostly for personal use. You can easily see what all of the mixins do by exploring the very straightforward code.

## Installation

In order to use these mixins, you need to use the "import" command. If common.less is in the same directory as your primary CSS file, all you have to do is:

<pre>
@import "common.less";
</pre>