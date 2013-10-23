knockout-jplayer
================

A [KnockoutJS][] binding for the [jQuery][] [jPlayer][] plugin.


example usage
-------------
	<div data-bind="jplayer: {
		media: { mp3: Mp3PathObservable, ogg: OggPathObservable },
		title: TitleObservable }">
	</div>

the jPlayer binding accepts standard [jQuery][] [jPlayer][] options, with the addition of the 
media and title fields. These are the only required fields for the binding. The plugin
will automatically generate the other bindings required by jPlayer (such as *'supplies'*)

	[KnockoutJS]: http://knockoutjs.com/
	[jQuery]: http://jquery.com/
	[jPlayer]: http://jplayer.org/