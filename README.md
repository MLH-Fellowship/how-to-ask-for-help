# How to get help during the MLH Fellowship

Congratulations! Getting support means you're about to learn something new, and that's exactly what the MLH Fellowsip is about. We created this document to help you learn how to fix your problems quickly.

# Who do I ask for help?

1. 🦆 [Ask your Rubber Duck](https://github.com/MLH-Fellowship/how-to-get-help/blob/master/README.md#rubber-duck-debugging) 
1. 🔍 [Ask Google](https://github.com/MLH-Fellowship/how-to-get-help/blob/master/README.md#tips-for-googling)
1. 👪 [Ask a human](https://github.com/MLH-Fellowship/how-to-get-help/blob/master/README.md#asking-others-for-help)
    1. ✉️ DM a BFF on your team in a direct message (ex @username)
    2. 📦 Ask for help in your your project channel (ex #babel)
    5. 🏗️ Ask in the project discord (ex: babel/help)
    3. 🧍  Ask a mentor (ex @username)
    4. 🗺️ Ask in general chat (ex: #javascript)
    5. 🙋 File an issue on the project repository

# Rubber Duck Debugging

A popular method for developers is known as ‘rubber duck debugging’. This is where you explain the problem to a rubber duck on your desk. 9 times out of 10 you realise the solution to your problem halfway through explaining it!

> Many programmers have had the experience of explaining a problem to someone else, possibly even to someone who knows nothing about programming, and then hitting upon the solution in the process of explaining the problem. In describing what the code is supposed to do and observing what it actually does, any incongruity between these two becomes apparent.[2] More generally, teaching a subject forces its evaluation from different perspectives and can provide a deeper understanding.[3] By using an inanimate object, the programmer can try to accomplish this without having to interrupt anyone else.

[See Wikipedia article](https://en.wikipedia.org/wiki/Rubber_duck_debugging)

The great thing about Rubber Duck Debugging is that even if you don't solve your issue, you'll have summarized and phrased the question for your next steps.

# Tips for Googling

- **Keywords** - First off, if you’re debugging an error message, pull out any individual information, such as file paths. This allows you to search a wider range of results.
- **Source** - Where is your error coming from? Is it a library? If so, look up the library’s GitHub page (if it has one), and check out the issues page. It’s likely someone has come to this error already and has had a response with a solution. If it hasn’t already been raised and the solution isn’t clear, raise an issue yourself, giving the developers as much information as possible. Also try and get a second opinion on your error, check on another codebase or computer, just in case it’s an issue with your set up.
- **StackOverflow** - Ah, the trusty StackOverflow, what would we do without it? I often find searching directly into StackOverflow brings up results otherwise hidden by Google.
- **Describe the issue** - If the problem is due to certain circumstances, try and pick out the keywords from this setup in your search term, as in step 1.

# Asking others for help

It's hard to provide support if all we know about your problem is "My printer doesn't work." or "My mail server doesn't work." This document has some easy tips that will help your helper help you! 

It's based off a dated document called [IRC Etiquette](https://github.com/fizerkhan/irc-etiquette), regarding support channels in IRC. I also highly reccomend checking out [how to ask smart questions](http://www.catb.org/~esr/faqs/smart-questions.html).

### Be precise

- What did you try to accomplish? (I'm trying to run `npm install`)
- What has happened (wrongly) instead? (I get `ENOENT`)
- What environment are you using? (I am on Mac Catalina with Node v12)
- What did you try to find the cause? (I already tried deleting the `node_modules` folder and reinstalling.)
- Are there error message or log files? (Here is a copy of my logs from when I run `npm install`)
- Has it ever worked? What did you change? (I just pulled the latest changes. It worked before that.)

If all this information is included then you will have a high chance of getting a useful reply.

### Tell what you are doing

Others only know what you tell them. If you change things silently then nobody will know about it. Don't say "I changed something. Now I have another problem," use the guide above to communicate your new problem.

### Don't ask to ask

It's a bad manner if someone enters a support channel and asks "May I ask a question?" or "Can anyone help me?". Although that may be polite in normal human interaction, if you're already in a support channel we know you need help! You can ask your question right away.

### Unintended rudeness

Sometimes you may feel that others are rude. You may get a response like "Reinstall the package. Restart the service. Read the `/usr/share/doc/mysoftware/README`." Although this is a very brief reply it is likely not meant to be rude. 

Sometimes text chat is like human interaction without all the friendly bits. Other people have probably answered your question a dozen of times today and they want to help you solve the problem quickly.

### Read the documentation

If people tell you to read the documentation then you should do so. You can expect to be told where to find the documentation. If you get an URL then get it and read it. 

If the documentation is too technical or you don't understand certain sections then say: "I have now read chapter 3.1 of the URL you gave me and I understand how virtual domains work in general. But how would I use both virtual and non-virtual domains together?"

### Tell others about the solution

It doesn't help anyone if you just say "Nevermind, found it." and quit the channel. Please tell the others what the solution to your problem was so everybody can learn from it. You will not look stupid - trust me.

### Use a pastebin

Sometimes you need to show others more than one line. Perhaps parts of your configuration files or a log file. Never just copy and paste larger amounts of text right into the channel. Always use a pastebin. 

Pastebins are public services (web sites) where you can paste your text and everybody can access them as a URL. Just paste your contents there and send the URL into the channel. That should allow everybody who's interested to take a look. Just don't paste it without any comment. Rather say: "Emails seem to get lost since I installed program foobar. Please take a look at my logs: http://..." See the [list of pastebin services](http://en.wikipedia.org/wiki/Pastebin) on the internet.
