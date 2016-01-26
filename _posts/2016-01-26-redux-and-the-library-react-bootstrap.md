---
layout: post
title:  "Redux and the library react-bootstrap"
date:   2016-01-26 11:36:00 +0100
categories: React Redux Project App
---

I found the library react-bootstrap and it seemed like a good idea to use. When trying to add an event to the react-bootstrap component I didn't find a prop that could be used. So, I had to refactor the code and write my own components using the usual bootstrap instead. My feeling is that the react-bootstrap isn't the choice when using Redux. But I might have missunderstood something.

#### Redux struggle
Right now I have this kind of Redux struggle thing going on. I have the theorethical feeling for the parts, but I'm not clear on how to use it for implement it in my app...

My struggle goes on and I'm hoping for the penny to drop soon.

#### Redux and deeply nested objects
In the problem definition in the <a href="https://github.com/gaearon/normalizr">normalizr library</a> it says that's hard for Stores (or Reducers) to consume data from deeply nested objects. That's also on my mind right now.