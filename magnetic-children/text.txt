## Introductions

In this panel, the question we've been looking at is what code and the reading thereof should play for videogame studies. Hopefully, some of the merits of this approach may now be apparent. Some of the risks may have occurred to you as well. In my contribution, I want to reflect on the role of code in video games by considering it as a "critical paratext". That is, not only does code merit criticism (as highlighted in Mark Marino's term, Critical Code Studies), but I think we need to view code itself as something that critiques the object it creates.

So to frame code and code studies as simply as possible, since most videogames now are software, they exist or existed at some point in history as something like a long list of words or at least alphanumeric graphemes. So, should we be paying attention to those words and word-like things, and if so, what can we learn from them? Code studies says yes.

(As we know,) Mark Marino has used the phrase "extra-functional significance" to identify what critical code studies studies: the textual, discursive or expressive elements of computer code. But in this expression, "extra-" is to me an unusual prefix with a particular connotation. Marino doesn't give us, for instance, "non-", or "a-", functional, and also (surprisingly) he declines "para-functional". Instead, we get "extra-" which connotes signification alongside or over and above a level of already-significant function. Now, I suspect "para-" may have been rejected because even though the literal sense of "para-" suggests being next to or alongside the thing, for most of us, "para-" recalls Genette's threshold of interpretation, which (to me) has always suggested a perpendicular orientation o the text -- a reader's otherwise direct approach to the transcendentally signified text as text is necessarily mediated or undercut by her first having to cross its thresholds, and two vectors that cross cannot be parallel. Marino's use of "extra" and my now-qualified use of "para" embrace this sense of confrontation.


## The Free Culture Game and Gravitation
So for this paper, I want simply to indicate that "para-" performs nicely as a vehicle for connoting what code does to the two example games I wish to analyze: two art games [artgames?]: 1) The Free Culture Game by Molleindustria and 2) Gravitation by Jason Rohrer. The title for my paper, "forward slash forward slash create magnetic children," is in fact a quote from the source code of one of these games, but not the one you might expect. [Since this is a code comment, it has no presence in or bearing on the compiled, playable version of the game.]

Gravitation is a meditation on love, parenthood, inspiration, creativity, and (maybe) capitalism. It's basically a sequel to Rohrer's popular and widely analyzed "Passage." Like Passage, the gameplay in Gravitation is simple and evocative, the music is elegiac, and the images offer a nostalgic, lo res bitmap charm characteristic of many artgames. [cf Chaz Evans] Overall, playing Gravitation tends to evoke sadness.[some students do report crying.] An affective response underscored when reading its code reveals it to have an autobiographical and confessional quality as well.

The Free Culture Game, on the other hand, is a "playable theory," with smooth vector graphics emulating the polished corporate culture it seems to critique. Gameplay is abstract and frustrating: the player controls a copyleft symbol which can be used to motivate citizen "prosumers" to consume ideas. This allows them to produce new ideas and thus remain active within the commons. Meanwhile, the opposing force -- a "Vectorialist", signified by a copy<strong>right</strong> symbol -- consumes and sells those ideas. The player's object is to convert all consumers into prosumers. The Vectorialist's objective is less clear (and thus we may well question it's status as an agent), since allowing it to convert all of the people back into consumers simply lets the game to continue indefinitely.

## Why these games?
At first glance, (and second and third), these games seem quite dissimilar, and indeed they are. Gravitation is overtly artistic, Free Culture is overtly political, Gravitation is programmed in C++, Free Culture is Flash. Gravitation offers some sense of narrative or at the very least a sense of characters and a situation, while free culture involves abstract agent entities conscripted or coerced into performing symbolic actions among and against other abstract agent entities.

I think my analysis will show that these games have a similar tension between their expression in code and their expression in runtime, but Above and beyond everything else, it's worth noting first that what these games share is simply that their source code is accessible. Jason Rohrer makes most of his artgames available this way, and he supports himself and his family by seeking out donations from those who enjoy his games. As a game maker practicing his craft at the self-identified avant garde of video games, this open source orientation of most of his gamework is consistent with his philosophies and manifestos about art and life in general.

The Free Culture game, on the other hand, is the only game featured on Molleindustria.org to be offered with source code available for download. Along with standalone players for different platforms, the website also includes a Flash .fla file for graphics and animation and a Code.as actionscript file for everything else. We can speculate that the programmer made this available for a couple of reasons. The game is, after all, about free culture, so in a way, it's openness demonstrates the principle it purports to argue through it's processes. In this cotext, it would be strange NOT to create an open source game. Less cynically, we might speculate that this game is unique among Molleindustria's titles for its emphasis on subtlety and process.[other titles not so subtle] To some extent, interpreting and responding to the game requires an understanding of how the game entities relate to and influence one another. So the code invites us to consider the math behind the processes or maybe even to manipulate those calculations and produce our own version of the game, perhaps one with its own, different, argument.

In any case, the fact that <em>these two games</em> are available for reading calls to attention an issue that I think has so far not received adequate attention within the nascent CCS conversation: the source code for the majority of games is simply not available in the same ways, and even when that code IS made available, it is there for a particular, rhetorical reason. There is an agenda or an intent underlying its presence in a way that perhaps should make us cautious of its textual authority. For instance, the fact that artists like Jason Rohrer choose to open their games makes it that much more likely, therefore, that his games are the ones we talk about when we do code studies.

## Significant Functions
To begin an actual analysis, I'd like to consider each of these games in turn first of all as though there were no code. In other words, at the level of functionally significant play, what gestures or signifiers are present and what to do the say? A brief and probably incomplete catalog of potential signifiers in Gravitation should probably include

- the score
- the time countdown
- the graphics
- the scope of visible game world around the player character
- the implied space of the invisible world

- the music

- the jumping height of the player character

- the season (winter -&gt; spring)

- the volume and complexity of the music

- mania / not mania (super saiyan mode)

- presence / absence of the child in scope

- presence / absence of the child in game world



- the relationship between playing ball and all of the above

- the relationship between acquiring/converting stars and any of the above

- the difficulty in pursuing multiple goals at once

From these, and maybe others, we can draw some specific conclusions as we play the game.

1 - Increasing the scope of vision, the volume of music and the season are all good things, and these may be increased by spending time with the child. Therefore it is good to spend time with the child.

2 - Acquiring and converting stars also increases these elements, as well as the score, so this must be a good thing also.

3 - Spending time with the child makes it easier to acquire more stars because playing ball more induces a mania state more quickly in the player character.

4 - When the child disappears, it is our fault for not spending enough time with him.

5 - Therefore, playing ball symbolizes a healthy relationship, stars are a metaphor for capital (since the score increases as stars are "cashed in" in the fireplace), vertical motion equals creative inspiration, which is something we can nourish by spending time with our children. The morals of this story are

A: Acquire capital at your own risk, since harvesting too many stars at once makes it too difficult to maintain healthy relationships.

B: The score lasts as long as the game, but is otherwise meaningless. Acquiring capital is meaningless if it leads us to lose the ones we love. Kids aren't kids forever.

C: If you have kids, go find them right now and give them a hug.

Now, there might be other conclusions, but these are, I think, fairly reasonable (literary) interpretations of what's going on in the game and what we are supposed to get from it -- and it's clear, by the way, that we <em>are</em> supposed to get something from this game because, remember, it's an "artgame." We can arrive at these interpretations and conclusions through iterative play -- that is, simply running the game over and over again -- and we can stretch or even subvert these through non-standard play. For example, leaving the game running and choosing not to interact at all actually yields some relevant information about it's processes. As it turns out, the scope, music and mania signifiers ebb and flow on a natural rhythm, without regard to playing ball or acquiring points. Also, choosing to remain continually with the child sprite doesn't yield a specific reward, other than the game ending with the child still present on the screen. The timer just reaches 0 and the title reappears. The affect of sadness is still present, however. [The isolation and futility of the final moments remind me of the final moments in my first play of the apocalyptic One Chance, where my player character and his daughter wait to die together on a park bench.]

So turning to The Free Culture Game, it's relatively straightforward to perform a similar analysis for significant functions. These seem to be the relevant signifiers:

- the number of people (prosumers) in the commons

- the satisfaction of those prosumers

- the number of people in the market

- the satisfaction of those consumers

- the number of ideas in circulation

- the influence of the cursor on ideas

- the influence of the vectorialist on ideas

- the difficulty in keeping prosumers satisfied

- the difficulty in keeping consumers unsatisfied

- copyleft pushes away ideas

- prosumers produce and consume ideas, consumers simply consume

The lessons of the game derive from this functions in a way that is likewise straightforward, if also a little convoluted. Strategy becomes a significant function for interpretation also, when players determine (at least, as I did) that success depends more on starving consumers than on feeding prosumers. I found it more productive to herd the ideas into the middle of the commons in order to keep them from the vectorialist. 

In this manner, with ideas in circulation like a currency, I seemed to enact with my strategy the cynical manipulation of intellectual property that the game should be critiquing. The critique, though, is further complicated by my playing as a solitary copyleft icon -- making monolithic a diverse and contentious range of philosophies and licenses in and around free culture and against traditional copyright. There's a whole host of intellectual properties issues that aren't addressed at all by this game, and those that are addressed are ambiguous or possibly counter to what I assume is the intended political message. Perhaps these limitations are a constraint of the game's playability as a theory. Perhaps not. To put it simply, it seems to me that the core problem facing intellectual property law in the digital era is that some want to treat an idea as property to be hoarded, and that's what the game encourages me to do.

## Significant Code
Now, finally, let me turn to reading the source code of these games to see how the functional significance bears out. Even though both games are the work of single programmers, and the platforms each uses are relatively common, it's too much, I think, to ask the potential code reader to apprehend the game top to bottom. In other words, I don't think one needs to master ActionScript in order to derive some insights from how the Free Culture Game is programmed. Instead, the significant functions we've already identified provide a starting point for what to look for in the source code.

In Gravitation, each of the significant functions I identified is indeed programmed and works pretty much as one might expect. [acknowledge Dylan here.] Several details become apparent, however, that disrupt or perhaps undermine the interpretation I laid out earlier. My function-based analysis depended in part on the relationship among properties like the apparent season (winter/spring), the complexity and volume of the music, and the effect my actions had on either of those. As it turns out, all of these things are managed and attenuated by a global variable, "playerEmotion." For example [dylan], here that variable is imported into the file musicPlayer.cpp, and Rohrer's comments clarify what is happening here:
<pre><code> // smoothly fade in particular tracks based on player emotion // low emotion plays only first track... high emotion plays all tracks extern double playerEmotion; ... // factor in player emotion // level from 0..(numTimbres-1) double trackFadeInLevel = playerEmotion * (numTimbres-1); </code></pre>

Some other interesting things:

<pre><code> // change in player emotion per frame //double defaultDeltaPlayerEmotion = -0.0005; double defaultDeltaPlayerEmotion = -0.0010; double deltaPlayerEmotion = defaultDeltaPlayerEmotion; // used during natural depression recovery double upswingDeltaPlayerEmotion = 0; // upswing 2 times faster that base downswing rate // ** Actually, since downswing rate increased, these rates are now equal // thus, if you're stuck away from catch-with-Mez, you don't spend // the rest of the game waiting for the natural upswing to complete //double defaultUpswingAmount = 0.0010; double defaultUpswingAmount = 0.0010; </code></pre>


There are several interesting observations to be made here related to revision and authority, but I just want to point out how striking it is that Rohrer uses the variable name "playeremotion"

Two other aspects of Gravitation's code strike me as significant and potentially transformative: the child's disappearance near the end of the game is something I felt guilty for, and this gave meaningful shape to my emotional involvement. However, what the code tells us is that this event had more to do with the child than with my actions.

[mez goes away]

Further, this child is still "there" in an ontological sense -- the hideMez simply references a method that advances his sprite animation to a frame that doesn't exist, thus rendering him invisible.

Notice, by the way, that I have shifted my pronoun in referencing the child. This is significant. While I played the game, I had been assuming, because of that extra pixel of hair-length, that the child sprite was a little girl. That assumption carries some affective weight for me because my 3.5 year old daughter Wendy has long blond hair. I'm not saying that I played the game as a representation of our relationship, but it does seem significant that that possibility is now to some extent foreclosed by the way Rohrer codes it. Throughout the source, that child is named Mez -- Rohrer's son is named Mez and also has long blond hair. This is a very specific interpretation on the author's part that's completely hidden from us as we play the game.

In the Free Culture Game, no such personalization exists to suggest an autobiographical intent. In my function-based interpretation, I did find the game's meaning somewhat incoherent. In the file Code.as, however, the structure of the meaning is more clear. Generally speaking, the Vectorialist's behavior in code comes across as much more malevolent than its actual behavior in the game. For example, there's an entire set of behaviors -- thankfully commented out -- that define "energy" as a property of the vectorialists' consumption. If I'm reading it correctly, it would basically get hungrier the more it eats

[energy code]

Note the use of first person in the comment, along with the invocation of the vectorialist by the pronoun, "this." ActionScript is an object-oriented language, where it is idiomatic to focalize discursive text to recall the present context of any code statements.

Like in Gravitation, the naming of things in the Free Culture Game seems to be important, and true to the names give in the game instructions, the enemy is indeed the Vectorialist and there is code for creating ideas. In addition, people are "person" objects with the property "consumer" that can be either TRUE or FALSE -- the term "prosumer" (which I've already been using) only appears in comments left by the programmer.

There is one curious exception to this otherwise consistent nomenclature: the cursor the player controls, and the attendant set of behaviors (mainly, repulsion of ideas) is referred to as "magic." This name leads to the oddly poetic line I borrow for my title. Here it is in context (where "this" is "magic"):

<pre><code>
//did the mouse move?

if((this._x !=_xmouse || this._y!=_ymouse) )

{

//create magnetic children

//they add persistence to the magic field (arguably useless)

d=field.getNextHighestDepth();

child=field.attachMovie("empty", "child_"+d, d, {_x:_xmouse,_y:_ymouse});
</code></pre>

Again, ActionScript is object-oriented, which means that objects share parent-child relationships. What's happening in these lines is that as the cursor moves, it creates an invisible shadow copy of itself that inherits the same ability to repel ideas. This is likely a way of tweaking the difficulty of the game, though the comment indicates that the programmer is skeptical of this behavior.

I see two interesting interpretive shifts that this makes available. First, whereas I previously questioned the validity of deploying "copyleft" as a single agent, the coding of this as an object reminds us that the behavior we perceive is really an aggregate of several properties, each of which bears the potential for nuance, especially the children's behavior. Magic is, thus, characterized as a field and not a vector.

The second shift has to do with the ideas that this magic pushes away. The ideas are programmed as objects already, so where earlier I criticized the game's strategic concrescion of ideas into commodities, the code reveals that this is always already the case, at least for this game -- and that may be it's best argument as well: to effect change within the cultural field, we must play the game by the rules that already exist -- rules like DMCA. I'm not a copyright expert, but most copyleft licenses that I'm familiar with (creative commons, MIT) work as extensions of existing copyright law, not as replacements for it.

Finally, though, these magical invisible children remind us that influence is fleeting. Like Mez, they are born with an automatic self-destruct timer:
<pre><code>
child.onEnterFrame = function() { 
			this.range-=1;
			if(this.range<10)
				removeMovieClip(this);
			}
		}
</code></pre>

## Conclusion: What is Code Studies Studying?

I suspect that I've gone on long enough, so let me conclude simply by listing some observations, drawn from these examples, that might give shape to what it is I think we study when we study code.

- commentary
- rough draft
- paratext
- hermeneutics

When we read code, we read a story that's constrained by the necessity of also functioning as software

I hope some of the benefits of this methodology are or have become apparent, but I also want to acknowledge and again list some inherent risks.

- code essentialism, demystification

- intentional fallacy: we have to trust the programmer.

I'll close by returning to the juxtaposition of these two games and what they do: The situation of playing Gravitation is intriguing because of the relationship between the player's emotion and the child sprite. Magnetism in Gravitation exists as an affect of strategy because the actual rules governing the consequent events are misleading. In the Free Culture game, magnetism exists in spite of strategy, and children are already a function of magic. Strategy exploits a tacit rule of inheritance, just as the vectorialist exploits ideas for profit, thus, ultimatley re-stating its critique of culture as capital.
