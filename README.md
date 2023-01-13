
# <center>Chapter 1</center>
## <center>Theory</center>
---
### **What is emmet ?**
1. It allows you to type shortcuts that are then expanded into full pieces of code.
For Example : 
    1. boilerplate HTML code
    2. building hierarchical structures
    3. adding custom characteristics and class/ids

[*_help_*](https://docs.emmet.io/cheat-sheet/)

---
### **Difference between a Library and Framework?**
1.Libraries provide the user a lot of control and have a low barrier to entry. They may be effortlessly merged into existing applications to provide new functionality, and they normally need little expertise and boilerplate code to get started.

2.Frameworks are more powerful, but they dictate how users structure their code. They are more likely to be utilised when starting a new project rather than being absorbed into an existing codebase, and the developer will need to learn about the framework's key principles before they can begin using it successfully. However, this inversion of control also aids developers in avoiding typical mistakes, inefficiencies, and bikeshedding.
Overall, Frameworks are more opinionated, whereas libraries are more adaptable. Both abstraction patterns have a place in the world of programming, and while none is necessarily superior, it's important to determine which is best for the scenario at hand.

**_Analogy_** : -

A library is like going to Amazon Furniture. You already have a home, but you need a bit of help with furniture. You don’t feel like making your own table from scratch.  Amazon Furniture allows you to pick and choose different things to go in your home. You are in control.

A framework, on the other hand, is similar to constructing a model home. You have a set of blueprints and just a few restricted options for architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.

**jQuery, React** => Libraries 
**Angular, Vue** => Framework

---
### **What is CDN? Why do we use it?**
a content delivery network (CDN) : It is a global server network that caches and sends information through the nearest edge server rather than the origin server, thereby lowering page load time.

So whatever type of content you’re consuming online, a CDN has probably been used to ensure it loads quickly for you. Many websites and online services rely on CDNs as a cost-effective way to improve uptime and perform.

Why is a CDN important :
CDN’s basically store a replicated, or cached, version of website content in multiple points of presence (PoPs) all around the world, so that users can access it from the PoP that is located within the closest proximity to them. So if you’re trying to access content in Cyprus, let’s say, you won’t have to wait for it to travel from a server based in Los Angeles.

#### Benefits : 
1. Performance: High performance and speed
2. Security: provides extra peace of mind
3. SEO: making your website more visible and higher ranking 
4. Availability: your content to be readily available all time by using the cached content. 

A properly configured CDN may also help protect websites against some common malicious attacks, such as _Distributed Denial of Service (DDOS) attacks_.

[*CDN Links*](https://reactjs.org/docs/cdn-links.html#gatsby-focus-wrapper)

By including CDN Links for REACT and REACT_DOM, we get access to REACT GLOBAL VARIABLE

REACT-DOM : specific for web
