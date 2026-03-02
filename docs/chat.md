## Chat Accessibility

> This piece dives further into the purpose and capability of multi-identity chat / plural chat accessibility tools - and how to evaluate their effectiveness.
> It expects you to have read [affordances](/affordances) or be otherwise familiar with [PluralKit](http://pluralkit.me).

there's a lack of depth in discussions of plural accessibility and multi-ID features in new and existing chat software. to me, the problem is clear: most participants don't know what pluralkit actually is.

"they're making pluralkit for [chat platform]" are they, though? do they understand what that is? do they understand why tupperbox isn't pluralkit? do they understand why matrix account switchers aren't pluralkit? do they understand why IRC /nick isn't pluralkit?

here's the deal: **multi-identity chat is not a technical capability problem, it's a social integration problem**. The question is not "can you send messages from different profiles with this software", it's "how does this software avoid implicitly ostracizing plural systems?" - and the answer matters.

what pluralkit teaches us is that when multi-ID messaging is naturalised in the software itself, it stops being exceptional to the user. what matters is not the featureset available to systems, it's that **pk/webhook messages look like messages, which means users treat them like messages**. the shared design language makes plural expression approachable, comprehensible, even intuitive to people who would otherwise struggle, hell, plural systems who otherwise struggle - we've met so many systems who've known themselves to be plural for a long time, but it took seeing other systems openly using pluralkit to show them that there is a way to integrate their plural identity socially, that there is a space in the world they can make for themselves - and that have subsequently become comfortable and open with themselves in other parts of their lives. that's the kind of impact these accessibility tools have - this is what pluralkit is.

the catch is obvious - every piece of technical/social friction in a multi-ID feature **others users and fosters alienation** (e.g. copping "wHy iS tHe bOT tAlKinG" due to the discord BOT label) instead of trivialising their acceptance - these are effectively flashing neon signs that say "THIS ISN'T NORMAL" that you could just _never install_.

"they're making pluralkit for [chat platform]" do they understand the problem they need to solve? or are they copying the list of features beat-for-beat? the more you speak to plural systems on discord, the more you see how much the the medium both enables and limits us, the more "let's set the bar where it already is" is obviously an absurd fucking take.

the tools we use and their friction shape both what's possible in terms of our expression and actualisation, and what's trivial in terms of our ostracisation. that is what pluralkit is.

making individual improvements over pluralkit's frictions is good, but without understanding that the critical problem is social, developers easily backslide on progress and leave obvious gaps: stoat's _masquerade_ feature (for example) has technical improvements over PK by existing at an API level, but chose a name that sows distrust in openly presenting plural systems.

you need to be able to think critically and identify pitfalls like this yourself, but here's _my_ list of flashing neon signs to avoid installing:

  - **Impermanence**: treating using different IDs as a "change" [irc /nick notifications]
  - **Scoping**: removing user agency [tupper perms, bot invites, matrix per-id bans]
  - **Armbanding**: displaying multi-id messages unnaturally [BOT/APP labels, different formatting to other messages]
  - **Opaqueness**: missing flows that make multi-ID messaging seem edge case or "unsupported" [pk unviewable profiles, usage being confined to a bot or mod]
  - **Complexity**: time spent on any action scaling with ID count [matrix room joins getting you IP banned, anything without proxy tag parsing]
  - **Serversidedness**: not giving the chat client control over the ID to send a message with [pk deletion jitter, no avatar preview (leading to misproxies)] 

multi-ID isn't something you can just "tack on" - remember, in an ideal chat software, ALL messages/accounts would be multi-ID (i.e truly natural messages) - with most users just never setting up a second ID.

so, use the accessibility tools you design - and talk to the people who've used them more than you. and remember: stagnation is not good enough - we deserve better.

-Jynn
