---
layout: page
title:  "Highlighting Test"
teaser: "If you need them, <em>Feeling Responsive</em> offers you a breadcrumb navigation. You can easily turn it on/off via frontmatter."
breadcrumb: true
categories:
    - design
tags:
    - blog
    - content
    - post
---
<div class="alert-box alert radius">WARNING: If you use breadcrumbs be aware, that if you use categories, you need pages for those categories. If not, the link in the breadcrumb won't work.</div>

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

## Front Matter Code
~~~
breadcrumb: true
~~~

