---
layout: post
category : posts
tags : [bazingalabs, controlling the household, roger]
---
{% include JB/setup %}

Using the Roger to control household equipment...

Today we added support for a product you may all know quite well the cheap remote socket switch.
This switch can be bought in any household store and costs around 10~15 euro.

<img src="/images/socket.jpeg">

In order to control the remote using the Roger we reverse engineered the wireless protocol of the remote switch.

We did the reverse engineering by hooking up a scope to the sending part of the remote in order to catch the pulsetrain it transmits.

The next step was reproducing this pulse train and sending it with the Roger.

The project sources can be found <a href="https://github.com/erikkallen/House-control">here</a>
