# D.I.V.E. ENGINE
Dynamic Individual Vulkan Engine or DIVE for short, is a new custom game engine with performance in mind. It started as a joke amongst a few friends when I couldn't stop complaining about the annoyances of Unity and the steep learning curve of Unreal.

My proposed solution was to create my own engine, which would be simple to use and very powerful. And sure this got some laughs and some taunts but, I was determined to make something great of my own.

I started by looking at what code Unity used to program their app. Apparently C++ was the way to go if I wanted to have low-level performance but still maintain some abstraction, because I really didn't feel like coding it in C or Assembly.

Alongside C++ I thought that using OpenGL would have been a good idea. At first, it seemed like the perfect fit. It was easy to use, easy to understand and easy to iterate upon. The only problem was that seeing as it had been around for so long, most tutorials/books were either deprecated or just old. A couple of websites aspired to teach modern OpenGL but when I tried I was most of the time unsuccessful and or unsatisfied with the results I obtained.

So for a week or so, I was quite happily using the older, less modern graphics API, up until I had to deal with shaders. I was unable to load shaders from another file for some strange reason so after trying for literal days, I decided to switch platforms and see if I could do something with macOS. To my surprise, apparently Apple had deprecated OpenGL in favour of their new graphics API Metal.

This made my heart sink as I knew I wanted my application to be cross-platform. I thought of a lot of solutions and remembered having a conversation with a fellow programming friend about graphics APIs and recalled that we had discussed the advantages of Vulkan and it's superior abstraction on modern GPUs.

So I went with Vulkan and this was the result.
