What is a cloud [shim](https://en.wikipedia.org/wiki/Shim_(computing))?

You have developed a really great cloud-based product and you offer it to your customers as SaaS, out of your data centre or private cloud.

Unfortunately, while your customers love the benefit of using your product, and they love the benefits of using SaaS, they want to extend those SaaS benefits to all sorts of aspects of their business that your product does not cater for, so they buy other people's great SaaS products too.

Then they want them all to work together, and to work with their on-premise systems to create an integrated solution that works seamlessly for their employees and customers.

Those other systems though have somewhere between slightly different and completely different data models and business rules, so, while you do offer good file-based and web-service-based interfaces, there is still work to be done to convert between data models and technical standards.

So, what's the problem? Isn't this for the customer to solve if they want to enjoy the benefits of your fab software?

But firstly customers don't like to be left on their own to solve this kind of problem, and its a competitive world - other companies that help them more gain a competitive advantage over you.

Secondly it doesn't always make sense for this to fall within the customer's domain - there are situations where it makes sense for data to flow directly between your systems and third party's without direct customer technology involvement.

What you don't want to happen is you having to support loads of customer-specific automation and transformation logic on your data centre platform, ruining your cost effective operational model and creating a long term maintenance nightmare.

Again, what's the problem? This is a common integration challenge, and there are lots of powerful enterprise application integration, EAI, products available help you solve it, and some of them available in the cloud.

But they are expensive. They are designed to be capable of solving far more complex scenarios than you are faced with in 90% of cases, often asking for a subscription of at least $1000 a month, scaling up costs with usage and number of data flows.

So, that is what a cloud shim is, it's that little bit of software, that fills in the software cracks in a solution; conforms to one of a number of standard patterns; costs little to nothing to create, run or maintain; and does not add to the complexity or operational cost of your data centre platform.

Yet, it forms part of a business critical integrated solution, and so must satisfy the same requirements for security, scale, performance, monitoring, system management, high availability, disaster resistance and recoverability as any other component of that solution.

Is that possible for this little piece of software to achieve such low costs but simultaneously form part of a critical piece of technology infrastructure that your customers' businesses rely on?

Yes, as it happens. Standard public cloud offerings from the likes of AWS or Azure, if used carefully, can provide exactly these characteristics at minimal cost.

The Cloud Shim project aims to develop and provide the design patterns and utilities that make up a cloud shim, and tools to make it easy to deploy and use it in production, without attempting to redevelop, replicate or compete with full-featured EAI products.

This project focuses on Azure as the base platform - because it provides some very nifty features and tools to address this type of problem all nicely integrated around the .net framework, or Core dotnet, and because, well, you have to make a choice.

We will focus on two type of shim:

1. file
1. web-service

starting with file shims, since this is surprisingly common, and onerous, but easy to shim, and that is what is being worked on now.
