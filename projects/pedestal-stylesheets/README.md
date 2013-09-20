# Pedestal Stylesheet Service

## Factsheet

Life Cycle Phase: early conceptual draft
Namespaces Contained: pedestal-stylesheets.service, pedestal-stylesheets.server
API Stability: experimental
Authority: informal, uncoordinated


## History

This was born out of some earlier experimentation in Pedestal samples which, is less suitable for this endavour once the experimentation hits a volume or certain level of complexity where it gets in the way of the purpose of a sample application, a demonstration of capabilities of new and unfamiliar users/testers. For a while, I had been testing the features of the CSS Domain Specific Language (DSL) named [garden][garden], which is made in Clojure for Clojure. After some interaction with the author and while becoming more and more familiar with Pedestal, I went to update some samples as contribution to the project, one of which was the `template-server` sample application. I then quickly added some style rules to the hosted site content because well, they didn't have any, and the rest is history.

Recently I did some more exploration on server-side CSS (since it really boils down to that what I was doing in the sample service) and this will probably be an extension of this notion.

## Concept



## Disclaimer

Keep in mind, I have no preference or bias for the most parts on technology, I know what works for me and what doesn't but I won't just asume or take anyone on their word: I like to experience it first and then make up my mind. This goes for server-side CSS as well, I'm sure many people have something against it, I don't care. It's not like I'm preaching any religious beliefs here anyway, and I'm well aware of any downsides to certain methods or schools of thought.

Have some serious thought, consideration or any contribution you would like to make (at some point when/if this becomes more formal)? Great, let me know.

## Links
* [Other examples](https://github.com/pedestal/samples)


[garden]: <https://github.com/noprompt/garden>
