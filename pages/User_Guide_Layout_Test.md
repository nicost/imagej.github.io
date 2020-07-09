---
autogenerated: true
title: User Guide Layout Test
breadcrumb: User Guide Layout Test
layout: page
author: test author
categories: 
description: test description
---

This page should be used internally to discuss the new IJ user guide
layout. Once polished, it should serve to orient on when converting old
user guide sections or preparing new sections to end up with a uniform
layout.

The syntax is always shown in the gray boxes and the actual look you
will see directly below each syntax specification.

If you want to add other templates, here you can find the ones existing
on imagej.net: [Template
pages](https://imagej.net/index.php?title=Special%3AAllPages&from=&to=&namespace=10)

## Different headline levels

    == 1 Main Menu Items ==     
    === 1.1 Submenus/Direct commands ===
    ==== 1.1.1 Sub-submenu ==== 
    ===== 1.1.1.1 Sub-submenu =====

## 1 Main Menu Items

### 1.1 Submenus/Direct commands

#### 1.1.1 Sub-submenu

##### 1.1.1.1 Sub-sub-submenu (if needed)

  

## Plugin parameters

Plugin parameters such as number fields, text fields, checkboxes, or
radio buttons will be shown **bold**

dropdown choices will be indeícated ***bold/italic***

## Keyboard keys

    {% include key content='Ctrl' %} + {% include key content='C' %}   or    {% include key content='Ctrl' %} + {% include key content='Shift' %} + {% include key content='F' %}

{% include key content='Ctrl' %} + {% include key content='C' %}     /
    {% include key content='Ctrl' %} + {% include key content='Shift'
%} + {% include key content='F' %}

## Menu structure

    {% include bc content='Image | Color | Split Channels'%}

{% include bc content='Image | Color | Split Channels'%}

## Boxes

``` 

{% capture includecontent %}
width=30% | As a standard box for additional info.
{% endcapture %}

{% include sidebox-right content=includecontent %}
```

{% capture includecontent %} width=30% | As a standard box for
additional info. {% endcapture %}

{% include sidebox-right content=includecontent %}

  

``` 

{% capture includecontent %}
Modifies Box with a title!
 As a standard box for additional info.

{% endcapture %}

{% include sidebox-right content=includecontent %}
```

{% capture includecontent %} Modifies Sidebox with title\!

`As a standard box for additional info.`

{% endcapture %}

{% include sidebox-right content=includecontent %}

  
  
  
  
  
  

``` 

{% capture includecontent %}
tip = Press the {% include key content='L' %} key to access ImageJ's most useful feature: the [[Command Finder]].

{% endcapture %}

{% include tip content=includecontent %}
```

{% capture includecontent %} tip = Press the {% include key content='L'
%} key to access ImageJ's most useful feature: the [Command
Finder](Command_Finder "wikilink").

{% endcapture %}

{% include tip content=includecontent %}

``` 

{% capture includecontent %}
This should display a notice box used for tipps.
{% endcapture %}

{% include info-box content=includecontent %}
```

{% capture includecontent %} This should display a notice box used for
tipps. {% endcapture %}

{% include info-box content=includecontent %}

``` 

{% capture includecontent %}
Something critical like do not put Fiji in the Programm Files folder!
{% endcapture %}

{% include warning-box content=includecontent %}
```

{% capture includecontent %} Something critical like do not put Fiji in
the Programm Files folder\! {% endcapture %}

{% include warning-box content=includecontent %}

``` 

{% capture includecontent %}
if necessary can be used for technical details.
{% endcapture %}

{% include tech content=includecontent %}
```

{% capture includecontent %} if necessary can be used for technical
details. {% endcapture %}

{% include tech content=includecontent %}

``` 

{% capture includecontent %}
To mention Fiji specific hints!
{% endcapture %}

{% include fiji content=includecontent %}
```

{% capture includecontent %} To mention Fiji specific hints\! {%
endcapture %}

{% include fiji content=includecontent %}

  
  
  
  
  
  

    %Replace% Yes %Replace% 

%Replace% Yes %Replace%

## Specific Icons

    %Replace% No %Replace% 

%Replace% No %Replace%

## Operating systems

``` 

{% capture includecontent %}
Everyone agrees: Linux is the ''best'' operating system!
{% endcapture %}

{% include linux content=includecontent %}
```

{% capture includecontent %} Everyone agrees: Linux is the *best*
operating system\! {% endcapture %}

{% include linux content=includecontent %}

  
  
  
  
  
  

``` 

{% capture includecontent %}
Everyone agrees: Windows is the ''best'' operating system!
{% endcapture %}

{% include windows content=includecontent %}
```

{% capture includecontent %} Everyone agrees: Windows is the *best*
operating system\! {% endcapture %}

{% include windows content=includecontent %}

  
  
  
  
  
  

``` 

{% capture includecontent %}
Everyone agrees: macOS is the ''best'' operating system!
{% endcapture %}

{% include macos content=includecontent %}
```

{% capture includecontent %} Everyone agrees: macOS is the *best*
operating system\! {% endcapture %}

{% include macos content=includecontent %}

  
  
  
  
  
  
\== TODO / Task list == The guidetask enables to make a tasklist with up
to 10 entries. This could either be appended to the bottom of each
article, or to article's discussion page. We could use the Todo

``` 

{% capture includecontent %}
add link to wiki page|add info on shortcut {% include key content='Shift' %} + {% include key content='F' %}|mention alternative plugins
{% endcapture %}

{% include guidetask content=includecontent %}
```

{% capture includecontent %} add link to wiki page|add info on usage of
{% include key content='Shift' %} + {% include key content='F'
%}|mention alternative plugins {% endcapture %}

{% include guidetask content=includecontent %}