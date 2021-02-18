---
layout: problem
title:  Blocklist Error
categories: problem
---

A general error occurred in the Blocklist API

{% highlight json %}
{
  "type": "https://problems.roadsync.com/problem/blocklist-error",
  "title": "A Blocklist error occurred. 
            An unexpected exception occurred attempting to retrieve a list of entries.",
  "status": 500,
  "detail": "Exception:: BlocklistError: Blocklist Error: DynamoDB Error: UnrecognizedClientException: 
                The security token included in the request is invalid. in api_helper.blocklist:78"
}{% endhighlight %}
