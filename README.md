# Timed Content

Adds a shortcode and function allowing you to force the contents of a post or page to appear or expire after a specific date, day and/or time. There are no premium features and no adverts - this is 100% complete and free! 

After installation use the shortcode `[timed]` around any post or page contents that you wish to appear or expire on a specific date and/or time.

Six parameters can be used - `ondate`, `offdate`, `ontime`, `offtime`, `onday` and `offday`.

**ondate** : Date after which you wish the content to appear, in format YYYYMMDD.

**offdate** : Date after which you wish the content to expire, in format YYYYMMDD.

**ontime** : Time after which you wish the content to appear, in format HHMM.

**offtime** : Time after which you wish the content to expire, in format HHMM.

**onday** : Day on which you wish the content to appear - 1 (for Monday) through 7 (for Sunday)

**offday** : Day on which you wish the content to expire - 1 (for Monday) through 7 (for Sunday)

If any of these aren't specified then a logical alternative is found - e.g. not specifying `ondate` or `ontime` means the text will appear immediately (until the conditions of any expiry date/time is met).

Here's some examples of use..

`[timed offdate="20122412"]It's nearly Christmas![/timed]`

This will cause the message to disappear after the 24th December 2012.

`[timed ondate="20120101" offdate="20121231"]It's 2012[/timed]`

This will cause the message to only appear during the year 2012.

`[timed ondate="20120101" offdate="20121231" ontime="0800" offtime="1200"]It's between 8am and midday[/timed]`

This will cause the message to appear between 8am and midday during the year 2012.

`[timed onday="1" offday="3"]It's Monday to Wednesday[/timed]`

This will cause the message to only appear Monday, Tuesday and Wednesday.
