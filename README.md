knockout-jplayer
================

A [KnockoutJS](http://knockoutjs.com/) binding for the [jQuery](http://jquery.com/) [jPlayer](http://jplayer.org/) plugin.


example usage
-------------
	<div data-bind="jplayer: {
		media: { mp3: Mp3PathObservable, ogg: OggPathObservable },
		title: TitleObservable }">
	</div>

The [jPlayer](http://jplayer.org/) binding accepts standard [jPlayer](http://jplayer.org/) options, with the addition of the 
media and title fields. These are the only required fields for the binding. The plugin
will automatically generate the other bindings required by [jPlayer](http://jplayer.org/) (such as *'supplies'*).
