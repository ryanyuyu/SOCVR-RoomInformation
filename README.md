#What is the SO Close Vote Reviewers Chat Room?

The [SO Close Vote Review Chat Room](http://chat.stackoverflow.com/rooms/41570/so-close-vote-reviewers) is a group of like-minded people who want to make a difference in the CVQ, reviewing and clean-up efforts. 

The moderation efforts of the room broaden, still aiming to reduce the close vote queue. However the room now acts pro-actively by issuing [cv-pls] requests, reopen voting, tag cleanup, burnination efforts, editing, coaching/commenting, delete voting, and feeding the [roomba][1].

## What sort of behaviour is expected?

We love this community. Our goal is to get rid of the "crap" so the good content can be easier found. As Room Owners we are sensitive for the needs of the community on Stack Overflow and encourage our members to help us create a guidance toolkit that enables all of us to fulfil those needs.

**No matter what is asked from us, we moderate the post and educate the user, the [be nice policy][2] is our bible.** 

Make sure you are ok with exerting your power, but understand when it is necessary to do so to keep the peace.

We are open for any critic, feedback and guidance received from the community as we are a part of it.

Room Owners step in the moment we notice site users are targeted by any room member. This goes without warning.


##What are the chat room rules?

To be an effective member of this room you'll need access to the review queues and you _better_ have some experience on Stack Overflow. Ideally 3k reputation, but 1k will do. That assumes you know the core of the site and assumes you have enough experience in (self)moderation.  

To stop us from turning into a chaotic voting ring, we have set up rules and guidelines for members to follow. 

###General expectations for Members:
* [cv-pls] should not be a habit for users. Don't make it an instinct to fast-track a particular post to the front of the closure system. Exceptions are made if the post is _really_ bad or the users in that tag can't close the post in time.
* [cv-pls] mean "close vote _please_", not "close vote or I'll stab you". There should be no expectation for other members to close vote any post you bring up, and do not pressure anyone into doing so.
* Extended discussion about a [cv-pls] is useless; we don't have to agree/consensus about a close request. We're not a democracy. However, users that are posting [cv-pls] that are blatantly wrong will be told so. The final verdict is on the RO team.
* All members are accountable for their actions when and if such accountability is requested on meta.
* Tag burniation requests and tag cleanup requests _must_ be backed by an MSO post with significant community support.
* A post is only actively edited/commented/handled by one member of the room. We don't need 4 members all leaving witty statements in the comments or in chat.
* The one-boxing of pictures is kept to a minumum and at best only (partial) screenshots to support the discussion are encouraged. (post yout meme's in the SO Tavern)
* All discussions are public. The RO team has an offline/private lounge for sensitive subjects if necessary.
* In absence of all Room Owners, the members lead-by-example.

###General behaviour for Room Owners:
* Is a role model for the kind of participaton expected. 
* Makes the final call in any dispute, unless the RO team decide otherwise. 
* Clears messages that are starred with a tag from the starboard
* Keeps the number of pinned items in the starboard to a minimum. It's ok to update and replace an existing if the information is still relevant.
* Keep the tags that the room is working on in the description of the chat room. This way we don't need to use pinned messages.
* Start the meeting.
* Schedule the events.

## Who are the room owners?
The room owners are

* [rene](http://stackoverflow.com/users/578411/rene)
* [gunr2171](http://stackoverflow.com/users/1043380/gunr2171)
* [durron](http://stackoverflow.com/users/1768232/durron597)

[Andrew Cheong](http://stackoverflow.com/users/925913/andrew-cheong) is the original room owner and creator of the room. [Dukeling](http://stackoverflow.com/users/1711796/dukeling) is also a room owner. Both stop by every once and awhile.

## Why do we need room owners?

We really shouldn't need room owners, but because we do we need to establish some guidelines.

The RO basically are there to slow down the enthusiastic crowd and to make sure we focus on posts and their quality and not on users.

The CV chat room has quite a bit of power. In the extreme cases we can insta-close any question, and this gives us moderator-like powers with very little external oversight.

We lead by example to prevent the room to become the mob.


##How does the room work? 

There are no obligations. We can't force you to do anything, and we don't want to either. The first purpose of the chat room is to have company as you go through the queue. Having a group beside you as you take on the queue really helps morale. We are also here to help with questions about what to do. Not sure what to do with a review item? Post a link and we will take a look at it!

We are also using a tactic for the queue's filtering. By having all members concentrate on a single tag at a time we have a higher chance of completing the review tasks that we process. Whoever is leading the event of the day (usually Rene) will give the tag suggestion based off a SEDE query.

We don't want to become a close vote posse. Every user should handle the review based on their own opinion/knowledge, choosing leave open, close, edit or skip when appropriate. Concentrating attention on a question in the context of whether or not to close a question, severely biases attention toward closing the question.<sup>1</sup>

##How can I join in?

First, check out the [chat room's schedule of events](http://chat.stackoverflow.com/rooms/info/41570/so-close-vote-reviewers). It's updated by the room owners and shows the weekly meet-ups. There are two time periods to choose from (you can choose both if you are able to) so that people in all time zones can join.

If you can't wait until a weekly event, or want to help out more often, we do a smaller review session each day. Hop into chat between 17:00 and 22:00 UTC and help us fight the queue (times change by day and member availability).

##What if you make a mistake?

We are all humans and have different backgrounds but solid reputation in a wide-range of tags. If you feel we mis-judged a gem, closed for the wrong reason or blindly followed advice from our peers feel free to ask for a reopen. Based on your feedback we'll learn, improve your question and help in getting it re-opened by casting re-open votes. This will improve our actions, so please provide feedback.

##Any resources to help?

Members of chat have made some user scripts to help make your life easier (or just more enjoyable).

* [Shortcut keys](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/CloseVoteShortcuts.user.js) - A script that allows a user to use the number keys to click review buttons, speeding up review time.
* [Confetti chat messages](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/ChatRoomConfetti.user.js) - Makes confetti appear on the screen when a type of message is said in chat (alpha status)
* [Bot Commands Auto-complete](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/BotCommands.user.js) - Auto completes commands for the chat bot.

We have a chat bot that you can play around with and help keep track of our activities. You can find the code base [here](https://github.com/SO-Close-Vote-Reviewers/SOCVR-Chatbot). The bot's name is `Closey`; hop in the room and type `@Closey help`.

The following is the Stack Exchange Data Exporter query we use for demeriting which tags to focus on: [Tags that can be cleared of votes](http://data.stackexchange.com/stackoverflow/query/236526/tags-that-can-be-cleared-of-votes)

You can see the day-to-day progress of the size of the close vote [from this neat online graph](http://hichris.erwaysoftware.com/closegraph.php). An explanation for the drops each day can be found on [this MSO post](http://meta.stackoverflow.com/questions/252584/enough-fuzzying-lets-let-everything-into-the-close-queue-and-age-out-questions).



##History

Let's face it. The Close Vote Queue on Stack Overflow is huge. It's a dauntingly large number. At one point, it was over 100k. It's a much tamer amount now, but it can feel like your contributions don't amount to anything. Hence the start of the 
initiative to [start a Close Vote room back in 2013](http://meta.stackoverflow.com/a/251956).

The room originated as a meeting place once a week to handle your 40 allotted review tasks. The feeling to make a dent with a couple of fellow users worked as an incentive. The motivation to make a difference is still there. 

We feel your pain. We want to help. Together, we can make a dent.


----

1: Paragraph adapted from [Rene's original chat room FAQ](http://meta.stackoverflow.com/revisions/251956/9). Mentioned here for attribution purposes.


 [1]: http://meta.stackexchange.com/questions/173513/turbocharging-the-roomba-solutions-for-premature-deletion 
