---
layout: page
title: ""
---

I am a Cyber Security Engineer
I love visiting / exploring new places with friends.
Process the flexibility to accomplish projects independently or within a diversified team of other IT Professionals.

###
AWS
Cyber Security
---
title:  "Comptia A+"
mathjax: true
layout: post
categories: media
---

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

{% gist 5555251 %}

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `medium` can be used to increase the width of an image or iframe.

![Flower](https://media.licdn.com/dms/image/v2/D4D35AQHY8vooKW2gGQ/profile-framedphoto-shrink_200_200/B4DZYR_Z5uG4AY-/0/1744058556404?e=1745326800&v=beta&t=r2WfJhy4yue7eikQoAhj6ZhP1wanEU2-nIBDdgGx5xU)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.



{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
