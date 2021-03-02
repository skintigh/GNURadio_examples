# GNURadio_examples
8DPSK / D8PSK / 8PSK working examples in GNURadio. I couldn't find any working example of 8PSK or 8DPSK nor anyone who could help, and GNURadio documentation was less than helpful. After months of struggling and tinkering I have some solid designs and decided to share them to hopefully save others months of frustration.

I included versions with and without channel models, and a seemingly useless equalizer.

I have also added examples of what I call a 9PSK / 9DPSK. I made it while reverse engineering a mystery protocol that I now think is probably 8DPSK-with-nulls. But where nulls probably are just used for timing and finding frame breaks, my example used them for a 9th symbol for transmitting data. If nothing else that lets you encode nulls along with your data when transmitting 8PSK with nulls.

I also added a simpler example of finding the frequency and power of the strongest signal in background noise. It is based on a collaboration with reddit users. I included a lot of comments to help educate beginners, but it's been over 20 years since I was an undergrad and so I may have some mistakes. I'm open to corrections!
