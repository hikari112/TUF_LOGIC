# TUF_LOGIC
Three Value Logic for Pine Script v6

This is a fun library I made in pine script. Back in version 5 bool's had an na state. This got me thinking about three valued logic which lead me to the wikipedia page for it.

https://en.wikipedia.org/wiki/Three-valued_logic

I really enjoyed going through the formal definitions and implementing them in the language. Thats what inspired me to make the UNANIMOUS() operation. Its kind of like a super & where when both values are different it returns Uncertain, otherwise it returns the value that both values share. 

I left two ways of using this library: plain int's, or an enum. I prefer the enum system my self, but some times just plain int's are the best way to go. Either way, I hope you get something out of this!

https://www.tradingview.com/script/lZBTgs2H-TUF-LOGIC/
