---
layout: post
title:  "From json resume to json cv"
date:   2018-06-01 20:55:50 -0700
categories: json resume cv
---
Looking at ways to extend json resume to cover more of the common elements in an academic cv.

### multiple positions at the same institution

#### json resume



{% highlight json %}
"work": [
		{
			"company": "CurrentInstitution",
			"position": [
				{
					"title": "YourTitle",
					"startDate": "2017-01-01",
					"endDate": "Present"
				},
				{
					"title": "YourPreviousTitle",
					"startDate": "2016-01-01",
					"endDate": "2016-12-31"
				}
			],
			"website": "http://the-university-url.edu",
			"startDate": "2016-12-31",
			"endDate": "Present",
			"summary": "A short description of your primary role.",
			"highlights": [
				"First hightlight",
				"Second hightlight",
				"Third hightlight"
			]
		},
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
