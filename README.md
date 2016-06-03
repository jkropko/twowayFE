# twowayFE
Files related to "On the Simultaneous Use of Fixed Effects on Cases and Time Points"

## I learned how to make a subtitle
* and an itemized
* list
* of things!

1. some with numbers
2. some with even bigger numbers

Some things require greater *emphasize* and _slanty writing_ or **big ass bold letters** or *__both__* ~~but not other things~~

Here is some Stata code I just wrote:
```*Connection between personal importance and extremity
foreach var of varlist healthinsure govserv defspend govjobs aidblacks enviro {
	gen `var'_ext = abs(`var')
	tab `var'_ext `var'_imp, row chi2
}```

Here is a picture of LeBron James:
![alt text](http://images.solecollector.com/complex/image/upload/qaf58xyfa2cbee9wm1af.jpg "Go Cavs")
