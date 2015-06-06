#What is the SO Close Vote Reviewers Chat Room?

Let's face it. The Close Vote Queue on Stack Overflow is huge. It's a dauntingly large number. At one point, it was over 100k. It's a much tamer amount now, but it can feel like your contributions don't amount to anything. Hence the start of the initiative to [start a Close Vote room back in 2013](http://meta.stackoverflow.com/a/251956).

We feel your pain. We want to help. Together, we can make a dent.

The [SO Close Vote Review Chat Room](http://chat.stackoverflow.com/rooms/41570/so-close-vote-reviewers) is a group of like-minded people who want to make a difference in the CVQ. We concentrate our efforts on a single tag at a time, and it works. We ensure that more reviews _matter_, and more reviews get completed.

##How does it work? 

There are no obligations. We can't force you to do anything, and we don't want to either. The first purpose of the chat room is to have company as you go through the queue. Having a group beside you as you take on the queue really helps morale. We are also here to help with questions about what to do. Not sure what to do with a review item? Post a link and we will take a look at it!

We are also trying out a new tactic for the queue's filtering. By having all members concentrate on a single tag at a time we have a higher chance of completing the review tasks that we process. Whoever is leading the event of the day (usually Rene) will give the tag suggestion based off a SEDE query.

We don't want to become a close vote posse. Every user should handle the review based on their own opinion/knowledge, choosing leave open, close, edit or skip when appropiate. Concentrating attention on a question in the context of whether or not to close a question, severely biases attention toward closing the question.<sup>1</sup>

##How can I join in?

First, check out the [chat room's schedule of events](http://chat.stackoverflow.com/rooms/info/41570/so-close-vote-reviewers). It's updated by the room owners and shows the weekly meetups. There are two time periods to choose from (you can choose both if you are able to) so that people in all timezones can join.

If you can't wait until a weekly event, or want to help out more often, we do a smaller review session each day. Hop into chat between 17:00 and 22:00 UTC and help us fight the queue (times change by day and member availability).

##What if you make a mistake?

We are all humans and have different backgrounds but solid reputation in a wide-range of tags. If you feel we mis-judged a gem, closed for the wrong reason or blindly followed advice from our peers feel free to ask for a reopen. Based on your feedback we'll learn, improve your question and help in getting it re-opened by casting re-open votes. This will improve our actions, so please provide feedback.

##Any resources to help?

Members of chat have made some user scripts to help make your life easier (or just more enjoyable).

* [Shortcut keys](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/CloseVoteShortcuts.user.js) - A script that allows a user to use the number keys to click review buttons, speeding up review time.
* [Confetti chat messages](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/ChatRoomConfetti.user.js) - Makes confetti appear on the screen when a type of message is said in chat (alpha status)
* [Bot Commands Auto-complete](https://github.com/SO-Close-Vote-Reviewers/UserScripts/blob/master/BotCommands.user.js) - Auto completes commands for the chat bot.

We have a chat bot that you can play around with and help keep track of our activites. You can find the code base [here](https://github.com/SO-Close-Vote-Reviewers/SOCVR-Chatbot). The bot's name is `Closey`; hop in the room and type `@Closey help`.

The following is the Stack Exchange Data Exporter query we use for deteriming which tags to focus on: [Tags that can be cleared of votes](http://data.stackexchange.com/stackoverflow/query/236526/tags-that-can-be-cleared-of-votes)

You can see the day-to-day progress of the size of the close vote [from this neat online graph](http://hichris.erwaysoftware.com/closegraph.php). An explination for the drops each day can be found on [this MSO post](http://meta.stackoverflow.com/questions/252584/enough-fuzzying-lets-let-everything-into-the-close-queue-and-age-out-questions).

----

1: Paragraph adapted from [Rene's original chat room FAQ](http://meta.stackoverflow.com/revisions/251956/9). Mentioned here for attributation purposes.
