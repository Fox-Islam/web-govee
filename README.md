# web-govee
A webpage containing just enough javascript to turn my Govee lightstrip on and off

The Govee app is unusually slow at connecting to my lightstrip to then switch them on and off, and the toggle widget Govee provides is similarly slow but has the additional issue of not knowing when the lightstrip is on or off - it defaults to assuming it's off and tries to turn them on first, requiring two attempts to switch the lightstrip off. 

Created this basic page using information gleaned from [RGB-PC](https://github.com/ib0b/RGB-PC) to make controlling my lights just a little bit quicker. 

To use this with your own lightstrip you'll likely have to change the name in the bluetooth device request `filters` property.
