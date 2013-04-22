# Toggle Mute Alfred 2 Workflow

The `mute` keyword will toggle the mute setting for your Mac's audio.  In other words, if the sound is not muted, invoking the keyword will mute it, and if the sound is muted, the keyword will unmute it.  

An optional argument is allowed for the `mute` keyword, that represents the number of seconds to mute for; the sound will automatically unmute after the elapsed time.   This can be useful for muting ads on streaming radio, for example.

There is also an explicit `unmute` keyword provided, in case it is easier for some to process that way (vs a toggle).

Tested on OS X 10.8.3.

### Usage

* `mute <seconds>` - Toggle the system's mute setting.  The argument is optional, and if provided, the audio will only be muted for that amount of time (in seconds), then unmute itself.  Adding the argument while the sound is already muted (which will result in an unmute) has no effect.  A non-integer argument is ignored.
* `unmute` - Unmute the system's audio.  No effect if audio is not muted.

### Download

[Download the latest version](https://github.com/brianbillman/alfred-2-toggle-mute-workflow/raw/master/ToggleMute.alfredworkflow) of the workflow.

### Release Notes / Change Log

##### 2013-04-21
* Initial version