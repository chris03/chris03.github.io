---
layout: post
title: "A first post"
tags: test stuff
---

This is a first *post* with some `markdown`.

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}