---
layout: post
title:  "This is a test"
date:   2016-05-28 20:43:33 +0800
categories: personal
---

ruby code

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
