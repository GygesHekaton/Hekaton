# Hekaton - An Alternative to Commander 

*Disclaimer: This is in concept phase. I am gauging interest and baiting feedback and criticism before committing.*

EDH/Commander has been the most beloved way to play kitchen-table magic for many years. Until now, it was managed by a group of individuals who were not under the direct purview of Hasbro, and that gave it a tenuous (if sometimes tumultuous) sense of objectivity and fun outside of the pure esports mindset that formats with more competitive metas have ultimately been reduced to under their guidance.

With the announcement of the dissolution of the Commander Rules Committee and the surrendering of EDH to Hasbro, many of us feel as though the spirit of both kitchen-table jank and unsanctioned cEDH tournaments now finally have the looming visage of enpoopification raising its arms and ululating in ecstasy at its newfound rule over us.

We don't have to accept this. We can fork it.

With modern tools such as Git, cloud collaboration software, and online databases, managing projects at this scale become much easier than when EDH was initially conceptualized among a small group of friends.

I propose: **Hekaton.**

Hekaton starts with the current rules of EDH, but with one massive change.

## Point System
We are moving to a point-buy system for card selection.
### Rating Cards
This will be the most tedious aspect of creating the project, so it is important to establish the logic by which all future adjustments will be made.

Cards will be rated on 2 criteria:
- Their power
- The misery they cause during the game

In your deck, all basic lands are free of cost, but everything else will cost at least one point

This inital rating will be based on the most-used and saltiest cards in the format. We will begin with a baseline criteria of the maximum power that qualifies as a 1, then move any card up by 1 point that is clearly better than the pack.

This will be made easier by establishing which [Signpost Cards](signposts.md) are the maximum power that can be considered a 1 for this initial ranking.

### Adjusting Cards
Format stability is the most important aspect for continued emotional and intellectual investment. Card rankings will have to be updated frequently in the beginning and then slow down as the relative balance reveals itself.

Once the initial pool of most-played cards is rated, their ratings will be voted on via a website. Users will be allowed to rate specific *and* random cards against cards in their same rating and categories, and players will be able to vote whether they should be rated higher, lower, or stay the same. After a period of 90 days, the votes will be counted, and rating shifts will be announced. No card will shift more than 1 point in rating unless there has been a monumental and previously unknown discovery about its function.

Also being proposed is that every new card introduced to the format gets a probationary period of one month with a valuation of 1 until it receives its first rating by the Hekaton administrators, who will base their rating against the current meta, using our Signposts as the floor. The reason that the valuation will be delayed is that we have had too many reactionary moments of misvaluation before a card has seen play. Also, people should get a chance to play their new cards before they are rated so that they will have a better idea of how it fits within their deck, and whether or not the cost makes it worth keeping.

[Mana Crypt's](https://scryfall.com/card/2xm/270/mana-crypt) power has been self-evident since the birth of EDH. If they had used our rating system at that time, it would have received a high valuation and stayed there, only possibly reducing incrementally as the format's power level rose via newer, more ridiculous cards.

Inversely, [Dockside Extortionist](https://scryfall.com/card/2x2/107/dockside-extortionist) famously started off as an undervalued card until its power revealed itself. Then as Wizards printed an unholy amount of treasure and sacrifice support at higher and higher power levels, Dockside's relative power increased instead of leveling out. It would initially have received a medium valuation, and then climbed and climbed proportionately to its effect on the format, eventually causing players to have to consider its place in their decks, rather than its final status as an auto-include in anything with red.

[Lutri, the Spellchaser](https://scryfall.com/card/iko/227/lutri-the-spellchaser) was banned due to it being an auto-include in every deck with blue and red because it cost nothing to do so. With the rating system, this would no longer be the case. It would cost a minimum of 1, but it will probably climb higher than that over time. Is it still an auto-include if you have to sacrifice a basic land for it? Maybe, but what if it rises to 3? 

There are no more auto-includes.

This completely removes the grandfathering of cards that Hasbro and the rules committee have told us are beyond reproach, such as [Sol Ring](https://scryfall.com/card/dsc/94/sol-ring). It is an incredible card, and everyone has one, but its rating should reflect its actual power and not its availability, legacy, or price. Every card added to your deck should convey a sense of choice.

### Deckbuilding

Pods or events may decide their own criteria for entry. Players looking for a medium/casual experience could set their point limit at, say, 150, where other pods could set it at 300.

Additionally, they may care more about the power of specific cards, such as "cards 4 and below welcome"

This is not a conversation about absolute deck power level, and it does not aim to be. Competitive and casual decks will coexist at every possible level. Cutthroat Competitive or Casual decks could both be built with a point restriction of 50 or only with cards no higher than rank 2. 

For those familiar with Warhammer tabletop games, think of the challenge of building a 2000 point army. Are all of these armies meant to address the most competitive meta? No. You still need to be upfront about the kind of experience you are looking for.

The rating of these game pieces simply arms everyone with a better (if still incomplete) picture of what people are bringing to the table while creating new opportunities for creative deckbuilding restrictions.

### The Return of Jank
Building low power decks is fun, but previous methods have been based on the printed rarity on the card, such as Pauper EDH, or its price, such as Gumball Commander.

Hekaton introduces better tools to create leagues of lower deck ratings, returning the massive pool of forgotten and underpowered cards to the format as deck builders find more and more ways to engage in creative deckbuilding.

### Bans and Unbans
Strict banning will not be the mechanism used to balance the system going forward.

[Primeval Titan](https://scryfall.com/card/ima/183/primeval-titan) is a powerful and easily exploitable card, but should it be excluded from the format entirely? I think not. Its point cost should reflect the impact he has on the game, but those willing to make huge sacrifices with their decks to play it in lower value pods or in high-power competitive Hekaton should have the opportunity to do so without being accused of harming people who they don't even play with.

People want to play with the cards they have. If you want to run [Black Lotus](https://scryfall.com/card/vma/4/black-lotus), it will be one of the most restrictive cards to include, but there should be a home for you. 

## Concerns
### Player Onboarding
**Q:** *Isn't an online rating system and individual card valuation a high barrier of entry for new players?*

**A:** Yes. However, the barrier to EDH is already unreasonably high, and all of the current methods and the recently revealed ones by Hasbro are even more convoluted. New players accidentally play with banned cards or cards wildly higher or lower than their playgroup's meta because they don't know either how they work in other decks or how they have been abused by others in the past. This tool, if implemented simply, gives them a resource to review their new cards within a more coherent context without having to spend hours on youtube or reading articles to have the most basic understanding.

**Q:** *Isn't price the main barrier to entry to most people? Shouldn't we rate expensive cards higher so that new players don't feel like they're missing out?*

**A:** To prevent corruption, price must remain irrelevant to this format. We have no position on what cards *should* cost, and we are entirely neutral on the subject of proxies. That being said, once the cards are being voted on, people will inevitably use some of their own subjective criteria. We won't prevent people from rating [Bayou](https://scryfall.com/card/vma/293/bayou) a 7 just because of its price if that's what the community wants, but our language should discourage the use of price as relevant criteria.

### Safety
**Q:** *What measures will be taken to prevent the pitchfork army from attacking?*

**A:** This will be disincentivized in several ways:
- Differing levels of anonymity: Who I am isn't important, and I don't need to know you either. Anyone invited to collaborate on the project, if they so wish, will be allowed to hide their identity from the public and from the other collaborators, with the current exception of myself. If desired, I may be able to find a way to authenticate each of them with a random name every time we communicate so that, while I broadly know who is involved, I may not know whose opinion is being shared.
- Open Standards and Transparent Processes: Development will be done in the open using tools that are accessible to anyone. You will be able to review and comment on every aspect of it, from the ratio of votes needed to trigger a rating shift, to the criteria by which cards are rated.
- No centralized community management: Your opinions matter, but if you want to share them outside of a dedicated suggestion channel or web form, feel free to create a community of your own. Once the project is started, public communication from me will be purely informational. Gyges, the avatar of Hekaton leadership, will not engage with you directly. If you are great at managing communities, the administration will be among you as someone else. 
- Go in Peace: I'll give you every possible tool to keep the parts of it you love. If you don't like a change, clone the repository and revert it to a previous state. I'm not your boss. Do whatever you want with it. 
- Law Enforcement: Don't harass people. It's stupid and illegal, and it will be used against you. Cops would much rather spend their afternoon arresting some MTG nerd than scratching their heads looking for leads. It will just confirm everything they already think about you.

## Conclusion
I have other, smaller changes to the ruleset that I want to propose that may improve some aspects of the game even further, but I will reserve those until after the initial feedback and criticism period, as they are not core to the concept and should also be voted upon by the community at large.

Thank you in advance for your interest and constructive criticism.
