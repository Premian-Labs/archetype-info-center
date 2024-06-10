## What is Price Protection?

Price Protection is an optional feature that allows users to hedge their token swaps from unwanted downside risk. 

When executing a swap with Price Protection, the received token receives cushioning in the event of prices falling. Users can choose from a variety of durations for Price Protection.

Behind the scenes, Price Protection purchases a put option within the same transaction, which provides downside protection on the received token. For those familiar with options strategies, Price Protection is similar to a strategy known as a protective put.

Archetype natively integrates Premia Blue as the options back-end for Price Protection. To learn more about options and Premia Blue, visit the [Premia Academy](https://academy.premia.blue/).
