

NOTES ON MY SLEEP / THE BUILD

- I seem to prefer the mattress temp to be about 25-26°C. Unintuitively, this actually means that my unit tries to _heat_ my bed before I get into it, because the native room temperature is about 20-23°. But then I get in and I'm 36° so then it has to cool down to 26°. It would be more efficient if it was smart enough to let me warm it up to 26° and not add heat of its own.
- On that note, you might notice that my design has no heating unit. This could be added, but personally isn't my goal. I have no interest in warming my bed really ever. Maybe this is an oversight, we'll see if people keep asking for it. In my mind heating by any other means is incredibly easy, and cooling is relatively hard, so the invention is to solve the hard one.
- My ideal room temperature is about 17°. I love winter.
- Since moving to a place with central A/C it seems like I can sleep up to about 21° but 20° (real room thermometer, not thermostat number) is roughly the threshold where I start waking up and feeling hot and antsy. I also keep an overhead fan on medium, the breeze helps a lot.
- I do slowly acclimatize - the numbers in august are slightly different than june, with more tolerance having gotten used to summer. Then, by the time I'm happy in september, it's already starting to get cold again.
- Solar gain still is the biggest bane of room heating, both physically and perceptually. The other summer in my other place I was shocked to notice that my bedroom was 26° and I was rather comfortable as long as the blackout blinds kept the whole place as dim as possible. Bright and hot feels warmer than dark and hot?


AFTER A FEW MONTHS WITH MY PROTOTYPE

- I do wake up cold if I'm laying on the mat with my whole body. The mat is exactly half of the width of my bed and so I've found that I either wake up having moved over to the non-cooled side, or I've started sleeping at an angle such that half of my body is cool / not cooled.
- contrary to my above thoughts, I think actually this is where a heater makes sense: you can't always rely on the body to add all the energy when the loop is actually _too efficient_ at cooling you. The fans almost never come on, which implies that the triple-rad passively run is over spec. 
- I think I can program both the pump and the fans (right now it's just the fans, set to come on at 27, the pump is permanently 60% power) where if it gets too cold the pump slows down and moves less overall through the radiator. The main problem with this is that the thermometer is in the pump, so if you stop running it also stops knowing what the bed temp is like (you could overheat in the bed and it would just never know to kick on higher)


SOME SORT OF INTELLIGENCE

- what if there was some sort of control panel where if you woke up in the night you could just hit a button that said "I'm too cold" and it'll move up a few degrees (or too hot = down, etc) and it starts logging that over time, every night, such that eventually it gets to know what the nightly graph looks like and can merely start to anticipate and be perfect.
- other sensors: room ambient temperature could play a part in it (maybe I'm too cold if the water is X, but just right if the water is X and the room is Y)
- at some level, I wonder if temperature as a number is actually so unintuitive with a machine like this that they don't matter: as an interface, setting a thermostat to 24 might mean any degree of felt-temperature depending on other factors (room temp, blankets, sleeping partner, sun, humidity, etc etc etc) and so abstracting preferences might actually be a nicer, smoother thing to deal with.
