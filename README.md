# The CaD manifesto

If you ever created a web page but had to abandon your vision or idea because your CMS didn’t have a needed feature, then this manifesto is for you. Or if you had to give up a front-end solution because it would be too complicated to create it with the system you're using, then read on.

CaD, **C**ontent **a**s **D**ata, is a technical architecture pattern that separates the content (data) from the user experience (your vision). It allows you to create a solution with any content management system without letting it dictate your final result.

CaD is about abstracting content. Treat **C**ontent **a**s **D**ata. 

### Why

Most web-solution are normally based on a CMS. We create the web site based on the tools that the content system gives us. If the CMS lets us do something, we do it. If not, we have learned the hard way not to fight too much against it. Work with it, not against it, is usually our mantra.

With the CaD pattern you can keep the CMS happy, develop with it, but break out the front-end solution into something else. Your website is just a consumer of your content and can be developed as you envision it, without compromises.

And CaD is system agnostic. It will work with whatever system you use, as long as its output can be any data format (JSON, XML etc).

## The manifesto

CaD isn’t a rigid technical solution, but instead follows 4 simple ideas:

- Your CMS/Content provider delivers data, not form
- Your frontend code lives outside the CMS/Content provider
- Your frontend consumes the content as data
- You design the interface of your data as something that could be consumed by another solution.

## The TL;DR manifesto

Coming soon
