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

```
*Connection between personal importance and extremity
foreach var of varlist healthinsure govserv defspend govjobs aidblacks enviro {
	gen `var'_ext = abs(`var')
	tab `var'_ext `var'_imp, row chi2
}
```

Remember, Don't Panic!
>For instance, on the planet Earth, man had always assumed that he was more intelligent than dolphins because he had achieved so much—the wheel, New York, wars and so on—whilst all the dolphins had ever done was muck about in the water having a good time. But conversely, the dolphins had always believed that they were far more intelligent than man—for precisely the same reasons.

Because it goes all the way across the sky:
<a href="http://www.youtube.com/watch?feature=player_embedded&v=OQSNhk5ICTI
" target="_blank"><img src="http://img.youtube.com/vi/OQSNhk5ICTI/0.jpg" 
alt="Double Rainbow!" width="240" height="180" border="10" /></a>

Here is a picture of LeBron James:
![alt text](http://images.solecollector.com/complex/image/upload/qaf58xyfa2cbee9wm1af.jpg "Go Cavs")
