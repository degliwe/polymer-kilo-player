polymer-kilo-player
===================

web component to use kilo player on your web apps.

Usage
=====

1.Add the component

Simply paste the following code to your html page

```
<script src="http://kilo-app.com/polymer/bower_components/platform/platform.js"></script>
<link rel="import" href="http://kilo-app.com/polymer/kilo-player/elements/kilo-player.html">

<kilo-player src="{{SRC}}" width="{{WIDTH}}" height="{{HEIGHT}}"></kilo-player>
```

2.Adjust the component

Go to http://public.kilo-app.com and select the clip you want to use.
On the player page you can click on the _embed_ to get the iframe based embed code.

replace {{SRC}} by the latest segment of the url ex.90cf4bf0977af95dfa7362a4162de7c0 this is the id of the clip you want to embed.
replace {{WIDTH}} by the _max-width_ value in pixels ex.480px
replace {{HEIGHT}} by the _padding-bottom_ ex.133.33333333333331%

This following line

```
<kilo-player src="{{SRC}}" width="{{WIDTH}}" height="{{HEIGHT}}"></kilo-player>
```
should now look like this

```
<kilo-player src="90cf4bf0977af95dfa7362a4162de7c0" width="480px" height="133.33333333333331%"></kilo-player>
```
