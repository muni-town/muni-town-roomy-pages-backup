**ATProto Isn't What You Think**
================================

This post is about [ATProto](https://atproto.com/), [Bluesky](https://bsky.social/), and to a certain extent [All The](https://docs.bsky.app/showcase) [Other](https://blueskydirectory.com/) [ATProto  
Apps](https://cred.blue/resources). I want to take the opportunity to look at things from a different angle and share how my view of ATProto has changed over time.

> **Charlie:** Wait!! First I want to address the elephant in the room: your title for this post is really click bait-y. How do you know what I think ATProto is?

Um... Hello, uh... Charlie. Obviously I don't _really_ know what you think. It's just that the title "ATProto might not be what you think" didn't roll of the tongue the same way, so I shortened it for marketing's sake.

> **Charlie:** OK, fine, continue.

Anyway... If you want some very long, optional background reading you could also read [How decentralized is Bluesky really?](https://dustycloud.org/blog/how-decentralized-is-bluesky/), [Reply on Bluesky and Decentralization](https://whtwnd.com/bnewbold.net/3lbvbtqrg5t2t), and [Re: Re: Bluesky and Decentralization](https://dustycloud.org/blog/re-re-bluesky-decentralization/), too. This post isn't really in reply to those posts, and I haven't fully read them all either, but they contribute to the overall mood and idea of what this post is about.

**Is It Decentralized?**
------------------------

I'm not really going to try to definitively answer this question, but I want to talk about the question itself.

Some people, correctly in my opinion, say that this question is nuanced. Other people say things like "it's pretty obvious that Bluesky isn't decentralized". I think part of the trouble is that there are a lot of questions that we're actually trying to answer when we ask "Is Bluesky decentralized?".

Some possible "questions within the question" people might actually want answered might include:

*   Is Bluesky decentralized?
    
*   Is ATProto decentralized?
    
*   Can I "own" my data? ( whatever that means )
    
*   Can good posts be censored against our will?
    
*   Will Bluesky be any better than Twitter in the long run?
    
*   Can I keep my followers and identity if I need to switch to an alternative for some reason?
    
*   What happens of the company behind Bluesky goes rogue?
    
*   What about if Elon Musk buys it?
    
*   Will I be happier on Bluesky than on Twitter?
    
*   Is "decentralized" Bluesky just an overcomplicated solution to problems I don't have just like blockchains?
    

This question of "decentralized-ness" is really just a front to a bunch of other vague questions we might be asking. And that's OK. It's a lot harder to talk about all the specifics of this "threat model" that we have half-formed in our head than it is to say, "is it decentralized?".

We just have to realize the limits of the question and realize it means different things to different people.

Again, in this post I'm not going to directly ask or answer that question, but I'm going to look at if from some different angles.

**Centralized Views Over Decentralized Data**
---------------------------------------------

I've seen a lot of different kinds of apps popping up around ATProto lately and I think one thing that isn't immediately obvious is that most of them are, in a large way, just typical, centralized web applications.

> **Charlie:** No they're not! They're on ATProto so they're... decentralized or something!

Oh, you're still here? Well, don't take everything so seriously, hear me out.

In order use the app, you have to access a centralized webserver run by the developers. Whenever that app shows you some data, it is querying from its own, centralized database. If that central infrastructure goes down, you can't access the app or do anything useful with it.

> **Charlie:** So all of the decentralization is useless!? Noooooo!!

Not necessarily. While the _app_ is centralized, the _data_ isn't completely centralized. In ATProto your data is written to your own PDS ( Personal Data Server ), and that PDS can be hosted by anyone. So if the app goes down, you can still have your data on your PDS.

This is really good compared to sites like Twitter or Discord, where your data is locked up in the platform and if it weren't for laws in certain countries giving you a right to that data, you might never be able to get your data out again.

> **Charlie:** Yeah, and even still they can make it pretty difficult.

Exactly. They want your data locked up. With ATProto there's a lot more going for you when it comes to having your data always accessible to you, including providing a standardized API to get that data.

Even if Bluesky runs most of the PDSes today, it doesn't have to be that way, and time may change that.

So the PDS gives us decentralized data, and the apps give us central views over that data.

**The Importance of the PDS**
-----------------------------

This is something I want to put a bit more focus on: how important the PDS is.

Giving people their own PDS is **soooo** crucial to having a free ( as in freedom ) internet. This needs to be something that I can:

*   Self host or have somebody else host for me
    
*   Download **all** of my data from, whenever I want to, and
    
*   Grant other apps read and write access to
    

That last piece is crucial to the existence of all of these different ATProto apps. We are giving people their own data store and then letting them connect that to all kinds of different tools and experiences.

The potential here is enormous! We **need** personal data stores.

Because of them, instead of us having just _one_ app with a way for us to "own" our data, _all_ of these apps now let us own our data. And making this basic ability, this right to control our own data, mainstream, is crucial to getting people's internet freedoms back.

**The Importance of Bluesky**
-----------------------------

I think that the importance of being "mainstream" needs a little bit of attention, too. Bluesky is becoming a much more "normal" thing than most other "decentralized" apps ever end up.

Bluesky set out to make an uncompromising Twitter-like experience, but with important freedoms built-in to its protocol. That lack of compromise on user experience has been crucial to its securing 30 million+ users.

> **Charlie:** But didn't they kind of lie about it being "decentralized"?

I think they did pretty good at explaining what they were doing the best they could. Again, lanugage is kind of failing to be as expressive as we want it to be here.

Even if Bluesky _had_ blatantly lied about its being decentralized, and I'm not saying they did, I think that getting so many normal people using an app with fundamentally way more open and freedom preserving tech, is really important.

I firmly believe that we can make decentralized apps that have great experiences and are really useful to normal people. I think it's a huge shame that almost nothing like that exists yet. Bluesky, whether it's 100% decentralized or not, has started to spread the narrative that not only are good decentralized apps possible, but that they are important.

The network that they are accumulating is also triggering an avalanche of development looking to capitalize on its potential. And these development efforts are inheriting the all-important personal data store.

**But the Centralization!**
---------------------------

> **Charlie:** OK, so we have decentralized PDSes, fine, but you said the apps are centralized. What does it matter if I have my data on my PDS if I can't do anything with it because the app is gone?

Let's take an example: the [Omnivore](https://github.com/omnivore-app/omnivore) app.

Omnivore is an open source read-it-later app. They had a free cloud service running for a while, they've got 14.4k stars on GitHub, and a lot of people loved and used that app.

But eventually the team behind it got acquired and users were given short notice that the service was going down for good. The project would remain Open Source on GitHub but all of the normal people who aren't going to self-host the app won't be able to use it anymore.

Users were given the opportunity to request a zip archive of all of their saved posts in a JSON format, but as it stands there isn't necessarily anything good to do with it yet.

> **Charlie:** That really sucks! But how would ATProto have prevented that? If the company goes away, the app goes away.

Well, if Omnivore was an ATProto app, and they shut down their server, all of the users would still have their data on their PDS in a standardized format. At that point, any other developers can come in and run another app, or even the same app if it was Open Source like omnivore, and access **all of the existing data already on your PDS** when you login.

> **Charlie:** Ohhhh, and unlike Omnivore, because all the data is still on the PDSes, all the users would have to do to get setup again is login to the new app. They wouldn't even have to make a new account or anything!

Exactly! That makes it **so** much easier for somebody to come in and "rescue" the app, so-to-speak.

Even if nobody stepped up to run the full-blown service that would run your RSS subscriptions etc., it would be possible to make a free website that would let you login to your ATProto account and _view_ all of your Omnivore data, so that at least you'd have a way to use the data left-over.

That's all made possible by the standardized personal data store.

**Identity**
------------

And that brings us to another one of the **super important** things that ATProto has done: they've decentralized the login provider.

> **Charlie:** Wait a second! ATProto isn't the first one to do that.

No, they aren't, but again, I go back to the "mainstream" factor. While there are other things like [Solid OIDC](https://solid.github.io/solid-oidc/) and [Web Sign-in](https://microformats.org/wiki/web-sign-in) that let you use your own domain to login, ATProto has made it so much more "normal".

When somebody lets you "Login with ATProto", unlike the "Login with Google" button, it actually lets you login with your _very own_ PDS.

Using your domain as a handle is _also_ super important. It means that just by putting in our handle we are informing the service, transparently though DNS, who is in charge of logging us in.

The "Login with Google" button has been so _useful_ and yet so horrible for the freedom of the web. Why does google get to be the gatekeeper to all of our web logins?

We need an alternative, but it also needs to be easy, and by making handles domains, and making it so that normal people can use and understand it, they have made it possible for an actually decentralized social login button.

Linking **Identity** to your **Personal Data Store** and using **Domains as Handles** is a _crucial_ combination that is really starting to unlock web freedom.

**More PDS Providers**
----------------------

> **Charlie:** But Bluesky hosts almost everybody's PDS. That's why it's so easy. How do we know that there will ever be anybody else that hosts PDSes for people? Decentralized login doesn't help if everybody only uses one provider.

That's a good point, and we _do_ need more people hosting PDSes. But I have good reason to believe that there will be more services hosting PDSes very soon.

The reason is for onboarding.

When most people make an ATProto app today, they usually just let you login with Bluesky. Bluesky is already providing the PDS and most people who are interested in your app is probably interested because they're already on Bluesky.

But that's not true for everybody. Us at Muni Town, as well as a couple other ATProto project developers I've talked to, are thinking about hosting PDSes so that users don't **need** a Bluesky account to join.

We want people to be able to register directly for _our_ app. They shouldn't _need_ to login with Bluesky, but if they want to, that's fine.

If we host PDSes, then we can let users sign up directly for our app.

Our app will give them a domain handle, just like Bluesky does, and the cool part about it is that they can use their handle from our app to login to any ATProto app, including Bluesky!

> **Charlie:** Whoah! That's neat!

Isn't it! What's great about this is that desire for independent registration provides a natural incentive for more apps to start running PDS services.

The more serious apps that start getting built on ATProto, that don't want to require a Bluesky account, the more services that will likely start offering PDS hosting.

And all of these apps will let you bring your own PDS to any of the other apps!

**No Relay Necessary!**
-----------------------

> **Charlie:** OK, that's pretty cool, but what about the relay? I hear a lot of people talk about how the relay is too centralized and that it's too expensive for anybody to ever really run their own.

There's a lot of debate around the Bluesky relay and whether or not it's posible to "scale down" ATProto.

Luckily, with all the attention that Bluesky and ATProto have gotten lately, there's a lot of interest in running alternative relays just in case things go bad, and I think it may be possible that funding for a public good relay might materialize to protect from the potential failure or compromise of the Bluesky relay.

But I also want to draw attention to another non-obvious thing about ATProto: the relay is not required.

Let's do a thought experiment. Let's say we were making our own read-it-later app called Herbivore.

Remember what I said about ATProto apps basically being normal web apps? Well, technically it's possible to make Herbivore so that you login with ATProto and then after that is 100% typical and centralized.

All the data is stored on the Herbivore server and basically completely ignores ATProto after you're logged in. This would take advantage of the identity side of things, but not the PDS.

Now lets add one more feature: all of our data is "backed up" in realtime to our PDS.

At that point we have a basically "normal" web application, where we can login with ATProto and all of our data is stored on our PDS, but there's no need for the relay.

> **Charlie:** Interesting... What's the catch?

The catch is how it interacts with other apps. For example, say there is another app called Carnivore. Its job is to help us delete old Herbivore data that we don't want anymore.

If we login to Carnivore and use it to delete a record off of our PDS, without the relay, Herbivore won't know immediately that our PDS was modified. So if we log back into Herbivore we'll still see the data that we deleted using Carnivore.

> **Charlie:** Well that's a problem.

Maybe sometimes, but not all the time.

For example, maybe Herbivore could just check to see if our PDS is in sync whenever we login to it. Or maybe there could be a periodic refresh.

Herbivore could expose an API endpoint that other apps could use to ask it to refresh it's data.

Or even better, maybe it could use the relay when it's available, but still fallback to another refresh mechansim if the relay is not available.

> **Charlie:** Could Herbivore run it's own relay that only subscribes to Herbivore users?

I'm not sure! I think that there's room for exploration here.

They already have the [Jetstream](https://github.com/bluesky-social/jetstream), which is like a filtered relay, but it still depends on Bluesky's relay service.

Maybe we need some protocol or PDS changes to make it feasible to do lighter-weight subscriptions to individual users on their PDS, or maybe there are things we could try already that we haven't thought of.

This is something I'd love to see more investigation into.

**Local First + ATProto**
-------------------------

And that brings me to the solution that Muni Town has started down with [roomy.chat](https://bsky.app/profile/roomy.chat): combining local-first tech with ATProto.

We're making a toolkit for building apps that can work offline and efficiently sync their data to other peers or services, including their ATProto PDS.

We'll still have a central service that will help users sync chat messages and other data with each-other in realtime, but it's also a service that communities can run for themselves and they can easily move their data from one provider to another.

The user data is stored it our own kind of "personal data store" that, unlike the ATProto PDS, is designed to be efficiently synced peer-to-peer.

The great part, is that we can still leverage the advantages ATProto regarding identity and the PDS as a place where all of you data is backed up and always accessible to you.

**Not a One Trick Pony**
------------------------

A lot of what I'm trying to get at with this post is that there is more than one way to leverage ATProto, and that there are some pretty major things it has started to do right that we really need right now.

We're used to the idea that there's more than one way to make a web app, and the same is true even if you are building it on ATProto. It hasn't set a lot in stone, it's just given us some bricks that we can all share.

The ["AppView"](https://atproto.com/guides/glossary#app-view) is a component of the ATProto architecture that you are given nearly free reign on. It can be any kind of thing you want, and I think there's all kinds of unexplored possibilities there.

You might even be able to make an AppView with a meaningful [ActivityPub](https://activitypub.rocks/) integration, or possibly borrow ideas about inboxes and outboxes as an alternative to relays.

> **Charlie:** So maybe ATProto lets you make centralized **and** decentralized apps.

Yep. I've had my eye on ATProto for over a year, and when I found it I definitely wasn't sold on it in any respect. I'm definitely still not betting everything on it.

Gradually, though, I am seeing some of the principles that I really believe are important actually holding up better than I thought they would in ATProto. ATProto wasn't what I thought it was.

It's still not perfect. Our whole Local First + ATProto idea doesn't even use it in a way that is commonly accepted as a good idea. We're still not sure how our plans might change, and we are actively preserving our ability to deploy completely independent of ATProto if we need to.

But there's a lot of good here that can sometime be hard to see.

When you're reading though all of the technical details of the protocol and seeing all of the specific designs of existing apps on it, it's hard to see what other possibilities there are and what still remains to be tried.

**The Final Hesitation**
------------------------

> **Charlie:** Uh oh, here it comes, I knew there would be another issue.

Heh, yeah, the last, big concern I see built into ATProto that I'm not comfortable with is the [plc.directory](https://web.plc.directory/).

PLC directory is the centralized database of user identities that is used by almost all ATProto users.

It's what gives you a permanent identifier that never changes, even if your ATProto handle changes.

It's what lets you tell the network when you change your handle, PDS provider, and other identity critical changes like your rotation keys. It's something most people don't need to think about, but that is critical to ATProto working.

It is almost completely fine and secure except for the fact that whoever controls the PLC directory can technically reject your updates to things like your PDS or handle.

This doesn't mean they can forge updates to your account, so for instance, they can't convince the world that you changed your handle when you didn't.

But they are able to deny your ability to share with the network that you changed your handle, if you wanted to.

For example, if you wanted to change your PDS to a non-Bluesky-hosted one, you could use some tools to create a signed record saying that you want to switch your PDS.

Technically, though, it is within Bluesky's power to completely ignore your updated record and not share it with anybody else. Effecively they've locked changes to your identity.

We need some fallback to prevent this. People have talked about turning power over the PLC directory to a group like the IETF, and that would help, but it's still not enough in my opinion. I feel like we need an option to use an alternative directory or something like that. We need a way to keep our identies even if somebody takes over the directory.

Someone has made a [proposal](https://github.com/edmundedgar/did-plc-p2p-guard-rails) to help provide an escape hatch for the directory, and I feel like there are other possibilities here too that are worth exploring.

Because, fundamentally, these records are a list of signed operations on our identity. Even if the directory denies my update, it is still signed and valid, and I could go and share that signed record somewhere else. I could even go post it to bluesky!

Once people find out about my signed update, then they would know that the directory is not up-to-date and my records could now be looked up from somewhere else maybe?

> **Charlie:** It doesn't sound like you've got any solid ideas.

No, I don't. I haven't had the time to do the necessary research to actually have a proposal in mind, but I do think it's important, and it's the biggest piece of ATProto that I feel I'm not comfortable with.

The rest of it, like relays, are largely optional, at least in the respect that I'm free to try something else, but that's not quite true with the PLC directory.

> **Charlie:** What about [did:web](https://w3c-ccg.github.io/did-method-web/), doesn't ATProto support that?

It does, but using `did:web` for your identity basically means you have to maintain ownership over that domain forever, which isn't always realistic. It just moves the problem.

The other promising possible solution is `did:webvh`, but I also haven't had time to look properly into that so I'm not sure if it's a suitable solution yet.

**Closing Thoughts**
--------------------

> **Charlie:** Well, are you done yet? I doubt anybody actually stuck around long enough to read this far.

Yeah, that's pretty much it, and, I mean, you stuck around so you never know.

> **Charlie:** That's fair.

I'm tentatively excited about ATProto and very glad to get to try and build on top of it. I'm hopefull that some real good will come out of it one way or another.

Until next time, bye! 👋

> **Charlie:** See ya! 👋