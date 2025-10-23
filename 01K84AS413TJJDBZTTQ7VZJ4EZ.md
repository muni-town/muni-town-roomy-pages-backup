**Digital Identity**
====================

**The minimal definition of user agency**
-----------------------------------------

See also:

[https://weird.one/muni.town/identity-tech](https://weird.one/muni.town/identity-tech)

**Minimal definition of user agency**
-------------------------------------

[https://newsletter.squishy.computer/p/the-minimal-definition-of-user-agency](https://newsletter.squishy.computer/p/the-minimal-definition-of-user-agency)

Gordon Brander, jamming on recurring ideas in the web3 space, proposes a [_minimal definition of user agency_](https://newsletter.squishy.computer/p/the-minimal-definition-of-user-agency)_:_

*   Own your ID
    
*   Own your content
    
*   Own your contacts
    

> Why do you need all three?
> 
> If you don’t own your content, you’re stuck. Owning your content is necessary for agency! However, it is not sufficient, because…
> 
> If you own your content, but don’t own your contacts, then you will lose your entire social graph when you switch services. Network effect will keep you locked in.
> 
> If you own your content and contacts, but don’t own your ID, you don’t really own anything. Why? IDs are upstream of access. Specifically, this is about who owns your name, and the cryptographic keys that secure your ID, under the hood. If your name is owned by an authority, you lose it if you leave. If your keys are owned by an authority, they are in control. They can lock you out of your stuff, snoop on your private messages, delete your account, or refuse to let you move it elsewhere. So self-sovereign IDs and keys are crucial for agency.
> 
> When you own your ID, content, and contacts, you have agency, because you have credible exit. You can seamlessly change services and bring everything important with you, like switching carriers for your mobile phone.

**Credible exit**
-----------------

[Vendor lock-in](https://en.wikipedia.org/wiki/Vendor_lock-in), e.g. by way of data lock-in, is by definition an anti-agentic feature. European internet users' _right to exit_ is even codified by law in the [GDPR's Right of Access](https://www.dataprotection.ie/en/individuals/know-your-rights/right-access-information).

From Gordon Brander's [Credible exit](https://newsletter.squishy.computer/p/credible-exit):

> **Dimensions of credible exit**
> 
> I think there may be multiple dimensions along which to think about credible exit. An app might provide some or all of them.
> 
> **I can export my data:** This is pretty bog-standard due to GDPR regulations now. Often what you get is a zip full of JSON files. Pretty lackluster. JSON isn’t something that makes sense outside of an app.
> 
> Export also has the downside of being static. If you continue to use the app, your export becomes invalid. This makes export only really useful for hard exit. Still, it’s better than nothing. I might say “export considered harm reduction”.
> 
> **I can sync my data**, or at least export and re-import it multiple times. This resolves the “dead export” problem. It also makes export useful for other use-cases, like backup and basic interoperability between tools. One way to accomplish this is with immutable data. If the file never changes, it’s easy to sync. iTunes music library is a good example. CRDTs are a promising primitive for data that is frequently updated.
> 
> **My data is in a useful format:** exit happens through a common formats that work in other apps. Plain text, CSV, PNG, PDF, SVG, MP3 are all good examples of useful formats. Camera Roll is a standout example here. You can drag and drop images, in and out of the app freely.
> 
> **My data lives in local files.** iTunes is a standout example. You can always take your MP3 files with you. Files are great because you have the bytes! Files also enable credible exit to emerge retroactively! New apps can come along and implement the file formats of other popular apps, uplifting their file format into a de facto protocol.
> 
> **Multiple apps can share the same data over a permissionless API.** This is where credible exit transcends itself and becomes broad interoperability.
> 
> **The app is open source.** A protocol will never capture the full fidelity of the app experience, but if the protocol and app are both open, you might unlock much deeper credible exit. Mastodon is a great example here.

Continued in [Freedom to exit](https://newsletter.squishy.computer/p/freedom-to-exit):

> > **Freedom to exit:** you can take your data and leave, and no one can tell you no.
> 
> The web does not support the freedom to exit. The server owns the data, so the server can tell you no. The same is true of most mobile apps. Some save files to folders, but most trap data in the app. The app can tell you no. This lock-in is used as a competitive moat for aggregators, and a business model for software-as-a-service.
> 
> So, how do we fix this? As far as I can tell there are just three ways to guarantee freedom to exit: decentralized protocols, local-first data, or legal agreements.
> 
> *   **Decentralized protocols:** no one can tell you no because the data is distributed across multiple peers controlled by different parties. If one peer tells you no, you just ask another.
>     
> *   **Local-first data:** no one can tell you no because you already have your data.
>     
> *   **Legal agreements:** no one can tell you no because you have a contract or license in place that guarantees access to your data.
>     

See also:

[https://docs.pubky.org/Explore/Concepts/Credible-Exit](https://docs.pubky.org/Explore/Concepts/Credible-Exit)

**The Great Untangling \[series\]**
-----------------------------------

Reclaiming (my) digital identity

[https://blog.erlend.sh/reclaiming-my-digital-identity](https://blog.erlend.sh/reclaiming-my-digital-identity)

### **Connective tissue**

> I've grown up in an unprecedented time of connective magic. Unlike my ancestors, I have known not tens, not hundreds, but thousands of people with whom I co-created something of value. Such is the power of the digital age. My deepest connections exist locally, offline. Yet many of those connections were initially mediated through the incredible connective tissue of the internet.
> 
> My life as a somewhat odd person would have been a profoundly lonely one had it not been for the online spaces where I found The Others; fellow weirdos interested in play-crafts like storytelling and game development, coupled with an obsession for openness as a means to digital emancipation. To most of the thousands of people I've come across in my two decades as a netizen, the digital expression of my persona is my entire persona. I hope to live long enough to engage in a physical handshake or even an embrace with many of my online friends, but I recognize that a large number of these connections will forever remain purely digital.
> 
> Therefore it is acutely important to me that my digital identity properly reflects my truest self. I want the people in my life to have seen and known the real me, regardless of whether they came into contact with my physical or digital being.
> 
> ### **Identity prison**
> 
> And therein lies my predicament: Ever since I first logged on to the internet, I've never had legitimate ownership of my own digital identity. My digital expression has always been mediated through some higher power. Sadly not of the paternal kind that intends to lift my spirit up until I can stand on my own.