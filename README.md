# Asynchronous Communications Manifesto

Although asynchronous communications become prevalent, many still struggle with them.
To improve individual's communications, the recommendations can be adopted.

## General

- think what value do you bring with every message
- always assume the best intentions of the message author
- don't be sorry about not replying immediately

## No scattered text
Scattering messages make it hard to read. Do not rush, as the reader can wait five additional seconds to enjoy the complete sentence.

Bad
```
Liam 16:12
I was thinking

Liam 16:13
Maybe we should do X

Liam 16:13
instead of Y

Liam 16:13
WDYT?
```

Good
```
Liam 16:13
I was thinking, maybe we should do X instead of Y. WDYT? 
```

## No Hello
[Don't say just hello in chat](https://nohello.net/). Respect the reader — speak right away.

## No tagging without a reason
Do not tag people just because you mention them, do it only if they need to be a part of the conversation.

Bad
```text
Olivia 16:12
I talked to @Emma about X and she told me that we need to do ABC. What are your thoughts on this 

Liam 16:40
I think @Emma is right, we need to take an approach X. We can implement it together with @Noah, let's talk about this next week.
```

Good
```
Olivia 16:12
I talked to Emma about X and she told me that we need to do ABC. What are your thoughts on this 

Liam 16:40
I think Emma is right, we need to take an approach X. We can implement it together with Noah, let's talk about this next week.
```

## No tagging of the whole group without a reason
Often a question can be resolved by a single person. If that's the case, tag only one person or even write in DM.

Bad
```
Liam 16:12
Hi @team-payments! Can you please take a look at my PR?
```

Good
```
Liam 16:12
Hi! Can you please take a look at my PR?
```

## No notifying everyone in channels
With `@here` and `@channel`, anyone can notify every member of the channel. Never use those. It forces others to stop working and take a look at the message. Surely it's not that important as you think.

## Using threads in channels
Using threads allows one to follow the conversation easily and not pollute the chat with many people.

Bad
```
Olivia 16:12
Hi there! Do you know how to do X and Y? I'm trying to make Z.

Liam 16:40
Have you tried doing ABC?
```

Good
```
Olivia 16:12
Hi there! Do you know how to do X and Y? I'm trying to make Z.

--- replies are in the thread ---
```

## Minimum off-topic discussions
Each channel or group is centered around a single topic, keep it that way.
If you want to share a meme, do it in the #memes channel instead of #payments.

## No two-phase commit
Using two-phase commit message styles doesn't bring benefits to the reader.

Bad
```
Liam 16:12
Hi there! I'm going to schedule a meeting about X on Tuesday

Liam 16:30
Scheduled ✅
```

Good
```
(no messages)
```

## Use tools
Use tools that reduce synchronization.
For example, with Google Calendar you can see the availability of every member, and a Github bot notifies you when the PR is reviewed or assigned.

Bad
```
Olivia 16:12
I need one hour of your time on Wednesday, could you tell me please, is everyone free at 13:00?

Liam 16:30
I have another meeting at that time, but I'm available at 14:00

Emma 16:40
I'm not available at 14:00. Maybe at 15:00?

Olivia 16:50
Scheduled for 15:00, thanks, everyone!

Liam 17:30
Sorry, I haven't seen the message. I'm not available at 15:00, can you please reschedule?
```

Good
```
(no messages)
```

## Avoid long messages
If it's possible to shorten the message without losing the meaning, please do it.
Reading is not as fast as talking. Respect the time of others.

## Select the minimum audience
If your question is about payments, try to find a channel for that using search. Don't rush into a global chat with every question.

## Delete unrelated messages
Wrote it a wrong channel? Delete the message, it will save the time of others.

Bad
```
----- #payments channel -----
Liam 16:12
Do you know any good pet stores in the city?

Liam 16:13
Sorry! Wrong chat!

----- #pets channel -----
Liam 16:13
Do you know any good pet stores in the city?
```

Good
```
----- #payments channel -----
Liam 16:12
(deleted message)

----- #pets channel -----
Liam 16:13
Do you know any good pet stores in the city?
```
