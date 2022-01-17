# Hello, is Oz.

I have only changed image paths in the template, for structure, also didn't use any css libraries as you probably aren't after whether or not I can type class names or not, I could implement bootstrap, I have agency experience over 2 years or so :)

## To install, npm i && npm run start

Yes yes, answer to your questions:

- What kind of front end projects do you enjoy working on? Why?

  - Project I'd like will care about software as much as I do, as in bunch of performance improvements, challenges, slick UIs, animations and ideally have potential to reach millions :p.

- Which are your favorite features of HTML5? How have you used them before
  - To list few:
    1. I what I like about html5 is having bunch of new div namings, it used to be all div's now we have main, nav, header, footer, sections etc. And yeah! I use'em actively.
    2. I like accessibility attributes too, currently I am trying to improve myself on it.
    3. Personal favorite? Audio API. I've used it while peer-programming with a course :p
    4. Every improvement on inputs, helped me greatly while creating an input for the component library I've developed.
- Explain the difference between creating a DOM element setting innerHTML and using createElement.
  - Imo, most important one is innerHTML isn't secure, other more obvious difference is, in one: you're putting in a script, and other one you'll need to append, I've created website wrapping advertisement model library, I've used createElement plenty. This should suffice?
- Compare two-way data binding vs one-way data flow.
  - Two way data binding allows us to update the data which is being held in the variable too, one way flow will just send data in either way we see fit, it's what the reactivity concept is.
- Why is asynchronous programming important in JavaScript?
  - In short, when Javascript initialized it creates a global execution content, which hoists everything then puts executables into memory-heap and from this call-stack it keeps executing the JS that is coded, which all happens in a single-thread, but some functionalities takes some time to respond from server or they're just heavier operations, which will block this single thread, so we're just sending those kind of operations to Workers that is working in parallel with this call-stack and when a respond comes (it works with messages, like webSockets) javascript recieves it and acts accordingly, in advanced situations you can instantiate a web worker and connect it to your interpreter/JIT compiler, which I didn't need to but yeah good to know it's possible.
