# nomic
Github-based game of [Nomic](https://en.wikipedia.org/wiki/Nomic), a game where the only move is to change the rules of the game.

## what is nomic

> Nomic is a game in which changing the rules is a move. In that respect it differs from almost every other game. The primary activity of Nomic is proposing changes in the rules, debating the wisdom of changing them in that way, voting on the changes, deciding what can and cannot be done afterwards, and doing it. Even this core of the game, of course, can be changed.

_— Peter Suber, The Paradox of Self-Amendment_

## how to play
The goal of nomic is to win. But how you win can change with each move. Each action in this game changes the very rules of the game. In order to win you must be cunning, crafty, and diplomatic. 

To participate all you need is a [github account](https://github.com/join) and a basic understanding of [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Rules will always be recorded in the [rules.md](./rules.md) and all information about players and resources will be recorded in the [players.md](./players.md).

### propose a rule amendment
1. Click `rules.md`
1. Click the pencil icon to edit the file.
1. Write your proposed change in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Give a short title to your change and then a more in-depth reasoning behind it. Then click "Propose file change".
1. Click "Propose file change" then "Create Pull Request".
1. This will create a "Pull request". PLayers now will vote and comment on it, and hopefully a mod will merge it, if it passes.

**protip:** If you need some inspiration for a rule name, [check out this](https://en.wikipedia.org/wiki/List_of_Latin_legal_terms)

### comment and vote on amendments
1. Click the 'Pull requests' along the top.
1. Click on the amendment (read: pull request) you wish to vote or comment on.
1. Write your comment or vote. For voting, use the reactions on the top comment to vote. :+1: to vote for it and :-1: to vote against.
1. Only mods can merge in approved pull requests. Once a pull request is approved following the current rules, add a message to the pull request using `@modname` to notify the mod it's ready to be merged. They will then double check it and merge it.

### join the game
1. Propose a change to the `players.md` where you are added to the list of current players with the starting resources outlined by the current state of the rules.
2. This pull request does not need to be voted on. A mod will double check the accuracy of the change and then merge it
3. Congrats! You're now playing.


### conflicting pull requests
Sometimes two pull requests may both be modifying the same part of the rules. If one is merged in before the other, the outstanding pull request may become _conflicted_. Github will display a grey message on the pull request indicating this. The proposer will have to close the conflicted pull request, create a new one that is not conflicting, and begin the voting process again.

## implicit rules
There are some aspects of the game that will not be listed as a changable rule, but still will take effect. Most of these will be obvious, but we'll list them here for reference.

1. Players will obey the rules at all times
1. Players are considered playing the game unless explicitly stated
1. No rule-change may take effect earlier than the moment of the completion of the vote that adopted it, even if its wording explicitly states otherwise. No rule-change may have retroactive application.
1. If ever there is a disagreement over the intepretation of the rules that can not be resolved by the players, the arbiter may be called upon to cast judgment on the intepretation.
1. Amendments are to be merged in chronoloigcal order of when they are accepted.
1. Resources may not be changed, gained, lost, or transferred except as explicitly stated in the rules.

### transfers
To initiate a resource transfer of any kind between two players, first the nature of the transfer must be allowed within the current revision of the rules. If it is, than one of the participating players submits a pull request modifying [players.md](players.md) outlining the change in resources. The other participant must approve the proposed exchange in the comments. Once approved, a mod will merge the change in. Please mark any transfer pull request by starting the pull request name with 'TRANSFER'.

### moderators
Each moderator will be set as a `collaborator` on the github repo, all other players will be `contributors`. Their job is to merge in approved pull requests and update resources. There should be a minimum of two moderators.

### the arbiter
The arbiter is an impartial non-player who, if need be, can be used for the game. eg. Determining ambigous rules, producing random numbers/results.

## start your own game
If you'd like to start your own version of this game, you'll need to duplicate this repo into a new one. Click the "plus arrow" in the navbar on the right and select "Import Repository". Use the url of this repo and call your new repo whatever you like, I suggest using the month-year or a unique name, incase you want to play mutliple times, eg. `nomic-aug2016` or `nomic-emeraldfury`. 

After you've created your duplicate, feel free to modify the starting rules (or anything else for that matter). Your new repo is completely separate from this one.
