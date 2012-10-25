/!\ ATTENTION : This fork must be used as it is. If you want to improve it or fix issues, I highly recommend you to look at this other fork https://github.com/eternicode/bootstrap-datepicker that has fixed lot of bugs and add several features. /!\

# Datepicker for Bootstrap

All the credits must be sent to Stefan who wrote this script (http://www.eyecon.ro/bootstrap-datepicker/).
However I found it doesn't work with Bootstrap v2.0.2+ and also it doesn't work with IE8 (at least), so I decided to patch the file... except that Stefan doesn't have a github account for this script, so I've create one.

FYI If you want more features or if you have some new requests, please look at this other fork https://github.com/eternicode/bootstrap-datepicker that will be more suitable.

# Example

See http://aymkdn.github.com/Datepicker-for-Bootstrap/ for examples.

# New option

You can also call datepicker() with "destroy" to remove the Datepicker from an element
```javascript
$('#id-element').datepicker("destroy"); // --> no more calendar when clicking on the element
```