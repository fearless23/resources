
Are you a founder, CEO, CTO, consultant or other stakeholder who needs to decide how to build a software product? Having trouble deciding on the tech stack for your web application? Should you use Python or Java as a language? Is node.js or Flask / Django the right choice for the web framework? What is the best front-end option: Angular, React or VueJS? What about the database — MySQL, Postgres or MongoDB? Should you self-host with Apache or Nginx on DigitalOcean, or just go with Amazon AWS? Maybe you’d rather work with a PaaS like Heroku?

If you have a million questions and don’t know where to start, this article can help you to make your decision.

---
## 1. Keep it simple. Go agile!

Often, the technology you choose will never wind up mattering, because the product itself fails. Many startups go with a scaling technology and spend time and energy on a robust build, only to find out that there’s no market for their product.

Whenever you want to build a product from scratch, the best option is to go with the easiest solution. A landing page with Wordpress or Unbounce could well be enough. Maybe even a static page faking what you’re try to solve would work. It’s important to gauge interest in your product before you go through the trouble of building it. It’s okay if the technology for the proof of concept winds up being different from the one you use in the end.

As soon as you know that your concept will work, you can move forward with building the product. Stay agile during this phase. You should never spend several months compiling a 100-page system specification (“Pflichten- und Lastenheft” in German) for the developers, especially if it assumes 6 or 12 months for product realization. It will probably result in a product that is either obsolete or delivered too late.

Think: first things first. Get a basic page running, then your first feature, then your second. The advantages of doing things this way are that you can evaluate progress in real-time and change direction as needed. You minimize your risk because your system is already running. You may not yet have all the features you had imagined, but it’s running!

---
##2. Think about your personal requirements

Keep your problem space in mind. The technology you choose should depend on the problem you want to solve. Some things are better done in one language than another — for example, Python is great for computation and statistics.

**Users before technology**

Products should be built for their users. What product do you want to build? How can you create the best user experience? Think about who will be using your system. Will they work on desktops or tablets? Will they access things via a mobile connection (as 60% of all users currently do)? Should there be a desktop-style application? What browsers will be used most often?

**Speed & performance**

Do you have (excluding) criteria? Will the software be running in your intranet? If so, initial loading times could be less than optimal.

A Again, always think agile when possible. Is performance really a problem you need to deal with right now? If you intend to be big, you can always start with Platform-as-a-Service (like Heroku) before improving performance with your own infrastructure. Instead of spending time and money when you’re still very small, you can worry about performance once you’ve crossed the appropriate size threshold.


**Migrations & legacy systems**

Do you have databases and/or data which need to be migrated? Do you have legacy systems which need to be transferred to the new system? These and similar considerations need to be examined and evaluated.

**Security**

Security should never be neglected. Depending on the kind of data you work with, security could even be the most important factor. Determine why you need to secure something before deciding how to secure it. But remember, technology isn’t everything — keep in mind that security depends primarily on the skill set of your developers, the work environment and the policies you implement.

---
## 3. Go for open-source technologies

When building new software, you should seek out open-source solutions. They prevent you from having to build everything from scratch; it will save you a lot of time and is probably more secure (many heads are better than few). You’ll also be able to focus on the business side of things and making your product stand out. Remember to give back to the open-source community!

Once you’ve singled out a prospective technology, you should run through a checklist. What kind of license does it have? Does the language or framework have the features you or your developers need? How many core developers are there? You can check out the contributors or stars in the Github repository and how they have evolved over time. Is the source code easy to understand if you need to go deeper and check the algorithm under the hood? Is the documentation comprehensive, is the tech thoroughly tested, and are there starter boilerplates to get you going quickly?

Another important question: how does the team behind the technology deal with security problems? Is there an email address for reporting security vulnerabilities?

---
## 4. Check the ecosystem

Every technology has an ecosystem composed of people and tools.

How big is the ecosystem behind the language or framework? How many Stackoverflow questions, conferences, and online tutorials (e.g. Udemy) are there? What does Google Trends say? Is interest in the software still growing? How many packages (npm, PyPi, etc.) are there, and do they have licenses you can work with?

Do you know about the awesome awesome lists? They help you dig into the ecosystem of a language or framework. You can check tutorials, articles, and important packages relating to a given technology. There are lists for Django, node.js, React, Angular, and many more.

**Also important**: is the community welcoming new members, and how active is the community? How is the support for users and developers? Is there a mailing list, a chat channel, a Slack room, or a ticketing system? Are people blogging about the technology?

---
## 5. Long-term trends & support

**Market lifecycles**

Every technology has a lifecycle. You want to choose mature technologies because they are reliable. You should check the latest Technology Radar to get an idea of how future-proof technologies are; this can help you decide whether to adopt them or put them on hold. The Technology Radar is free and it separates technologies into the categories of Techniques, Platforms, Tools and Languages & Frameworks. However, you should use the resource with caution, as the information is provides is not set in stone.

Another idea is to check industry-favorite technology stacks with stackshare.io or techstacks.io. Check out what Airbnb is using or what people like about AngularJS and who is using it. If you’re unsure about a technology, you can search for alternatives. Here is a list of alternatives to Angular JS on alternativeto.net.

**Long-term vendor support**

Does the technology vendor look like they’ll be around for a while? Are big companies sponsoring the development of the tech in question? Google is behind Angular, and Facebook is behind React. This means that there should be some progress, until the company eventually decides to drop their support (yes, this can happen). But the bigger the community, the bigger the chance that things will stick around for quite some time.

Some applications have versions with long-term support. Specified versions are then provided with bug-fixes for a given period of time. You should also check the technology’s webpage: how are updates handled? How easy is the update / migration process? Have there been particularly incompatible versions (like Angular 1 & Angular 2)?

---
## 6. Human resources & recruiting

What developers do you have on your side? If you have to decide on a front-end technology and you have three strong Angular developers, you should probably work with those. Moving fast can be important, and it’s quite an advantage to have people who are in their comfort zone instead of learning a new technology. Also, existing knowledge of the ecosystem is an additional benefit.

Regarding recruiting, be sure to check the following: can you find enough quality developers for the desired technology? How much do you need to pay them? Are big companies working with the same technologies and snatching up all the good developers? Are the developers you find mostly established professionals, or is it hard to differentiate between them and the script kiddies? A good Java developer may be easier to find than a good Ruby on Rails or PHP developer. For your research, you can check XING, LinkedIn or job search portals. You can also check for job trends (e.g. comparing Angular with React).

Is the technology easy to learn? An easy language can help you find and train junior developers, and the whole ecosystem could attract more people.

Last but not least: a great resource in HR is the Stackoverflow Developer survey. It provides a great overview of developer types, utilized technologies and salary reports. Have a look!

---
## 7. Will you be flexible enough?

**Service granularity**

Things are changing much more quickly than they were 20 years ago. For a long time, people worked primarily on desktop computers and with Windows. This will probably not be the case in another 10 years. Your chosen technology will probably stay with you for 5 to 10 years: this is a long time, and you can’t be sure how things will evolve. That’s why you need to be prepared to change technologies when the need arises.

Think granular, think in little packages, and think in separation of concerns. You should separate services, back-ends and front-ends into smaller applications and micro-services. You should be able to easily swap out technologies when the existing ones don’t work for you anymore. Check out concepts like service-orientated architecture (SOA) and domain-driven design (DDD).

**Can you bail? Will it scale?**

Do you always have access to the data? Is it always possible to export your data if you need to change technologies? Does the technology have an API to allow flexibility on the other end? Maybe you want to open your application for your clients or customers, or you want to build mobile apps, desktop apps or other systems on top of the chosen technology.

---
##8. How does it feel?

Have your developers look into the technology, or do so yourself. What are your first impressions? Have a little pilot setup, try out existing boilerplates, or (if possible) have a little test project. If you go with granular services, you can build a new little service with a given technology and see how it works.

There are also real-world applications which can give you a better understanding of the differences. TodoMVC is a great project — a simple Todo app is realized with different Javascript frameworks, and you can check out the source code architecture. There are all kinds of examples, and you can compare Angular with React or Vue with Ember.

The awesome RealWorld project goes even further: it’s a Medium-like full-stack-application utilizing either Django or node.js for the back-end and Angular or React for the front-end. You can read an introductory article about it by Eric Simons.

---
##9. Get started

If you are a small startup, getting to market is more important than having the perfect tech. Focus on your business and marketing rather than having all the technology pre-optimization necessary to handle the amount of users Facebook has. You probably won’t have all the required knowledge at an early stage, but you can fine-tune and optimize things or change tech stacks as you grow (and have the requisite budget).

As an enterprise, things can be different. The decision will mostly be political anyway — people in your company need to be okay with your decision. The management (and hopefully the in-house / prospective developers) are probably the most important stakeholders to have on board.

It’s important to keep in mind that quality is a matter of doing things properly. Technology isn’t the only thing that matters: you need the right design, the right requirements, the right testing procedures, and so on. The most important thing is making sure that you don’t limit yourself in terms of scale or migrating to a different technology in the future.