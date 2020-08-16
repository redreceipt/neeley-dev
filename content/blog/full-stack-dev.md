Title: Full Stack Developer, 18 Months In
Date: 2020-05-12

I'm relatively new to web development. I learned Javascript at the end of 2018 and have enjoyed every second of it. But the modern stack seems to be growing increasingly more complex without a lot of payoff. I tend to agree with Tom [here](https://macwright.org/2020/05/10/spa-fatigue.html).

In a previous life I was Linux engineer and worked primarily in Python. To say it's my favorite is an understatement. This is why I have felt such a strong magnetic pull towards Flask. I understand that choosing to work with a server-rendered framework in 2020 is the equivalent of heading over to Cingular Wireless and picking out a new Blackberry, but I can't help it. You’ve got a fully extensible back and front end with five lines of boilerplate. Every SaaS in the world has a fully functioning Python API and for fancy front-end stuff, we've got HTML, CSS, and plain ol' Javascript.

Don't get me wrong, I love React. The interactivity you get out of the box is incredible. It's obvious why it's caught on. But when something has gone wrong, I have to debug React and every other tool down to the roots. For simple projects, I may as well just learn JS better and cut out the middleman.

So back to Flask. It's got Python. It's got the back end libraries to do anything I need. And on the front-end, it doesn't try to re-invent the wheel.

Ok so I've got a fully functioning website on my computer, but where do I put it?

![It's in the computer](https://media.giphy.com/media/4cjRNnP4dpMis/giphy.gif)

I learned about [Vercel](vercel.com) (formerly Zeit) somewhere along the way and fell in love. They have all the hard questions answered and make it so easy to buy a domain and deploy a static site or a simple serverless function, complete with a global CDN, first-class developer tools and practically no configuration.

Then they moved to 2.0 and the honeymoon was over.

I still think they are the gold standard for the modern JAMStack site mentioned above. But they will be the first to tell you that support for server-rendered sites and advanced application servers on their platform is essentially deprecated. So what do I do with search indexing? Persistent cache? Custom data schemas? The [answer is somewhat open-ended](https://twitter.com/rauchg/status/1247965620668231680) primarily because the serverless landscape is just getting started. Even trying to use Mongo was a dead end. Tools like [Hasura](https://hasura.io/) and [Fauna](https://fauna.com/) look amazing but are just the tip of the iceberg.

So on personal pet project number two, I'm moving my Flask site to Heroku to see if I have better luck. Our GraphQL server at work is hosted there so I was already familiar. I'm a day in, so far so good. The developer experience can't touch Vercel but there seems to be an answer for everything. Native Redis and Postgres integrations are already answering my unanswered serverless questions. I'll need to set up custom domains and preview deployments, steps that are stupid simple with Vercel but I imagine it won't be much work.

Overall, I love how much there is to learn. It satisfies my never ending curiosity. Fresh perspectives are valuable but that’s all I have to offer. These thoughts are from someone with very little experience so please be patient with my naivety. One thing however is certain, code makes anything possible. I’m having a blast.
