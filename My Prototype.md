# My Prototype

Prototype cube (storage crate from ikea). basically just a frame to ziptie all the pieces to.

![image](https://i.imgur.com/VBK3HnA.png)

![image](https://i.imgur.com/M9Vh0Dq.png)

that's a full PC power supply which I just happened to have kicking around and it already worked for the plugs that the PC-based pump used, so that was an easy way to get up and running - the pump actually only uses ~5-10 watts and so having a 550W power supply is clearly overkill. By coincidence, this power supply has a eco mode where the fan doesn't spin so it's perfectly quiet which is conveniently great.

eventually I think I'd solder some sort of barrel connector to a cheap amazon 12V power supply brick, since that's more appropriate in power and size.

clearly there's lots of room here to make things more dense for more permanent install, I think I might drill a hole in my bed frame such that I can mount everything directly into / under the bed itself.

pump (more information in [the parts list](https://github.com/LTKMN/Bed-Cooling-is-Best/blob/master/Parts%20List.md)):

![image](https://i.imgur.com/ch6JmSG.png)

I used a sponge to hold up the acrylic pump hat because the bracket on the 'bottom' of the pump wasn't strong enough to cantilever both the pump AND a weighty block (and pipes, fittings, water weight) plus I figure it isolates vibrations and thus noise, if there's any (the pump runs very smooth and quietly)

![image](https://i.imgur.com/mNPwoYP.png)

The screen has tons of diagnostic info, and is a self contained operating system so you can adjust the thermostat settings, speeds, etc. - basically the whole reason I bought this particular pump is that I wanted the screen and fan controller.

cut the existing pad's piping:
![image](https://i.imgur.com/WcKhTvF.png)

the printed converters:

![image](https://i.imgur.com/ySp6ns9.png)

![image](https://i.imgur.com/LBmmqcn.png)

these have worked great, no leaks that I can tell. cheap resin 3D printer used was the Elegoo Mars.

## Thoughts

Overall I'd call this a huge success.

I used it all summer and it's october as I write this update, so it's the end of needing the machine.

If anything it's too powerful - the triple radiator can run nearly passively (no fans) with the thermostat set to 26-27 degrees, which seems to be a nice zone for my sleeping comfort if slightly too cold (waking up at 3am or rolling in my sleep off the mat).

The pump I run at 60%. seems like a good compromise between power and quiet. I think if I had some sort of other fan controller I would switch to a common vario pump instead of the fancy expensive one - there's just no real reason for the pump speed to change once you've dialed in that initial speed preference.

The fans are basically inaudible - the whole system is silent honestly, especially with them off - so much so that sometimes I forgot to turn it off in the morning. There might be something to be said about running a double or single radiator with more constant fan to dial in better temperature control: if the passive power is too much you can't really turn it down from zero (running the pump slower works sort of, but it also interupts the feedback loop of the pump getting temp readings out of the pad since the water has to come back).

The height of the unit should be equal or higher than the pad, I think. if you turn off the pump all the water from the pad flows down into the reservoir and since this system happens to hold way more water than even my large computer res. was designed to hold, it might back up past the fill point (which should be the top of the system). You can screw in the cap, and I do, but then you're also adding air pressure / vacuum into the whole thing when the pump is on / off, and depending on how you filled it. The answer is either a bigger fluid storage or a better elevation in the elements.

The pad is still mediocre. I fixed the noise and some complaints with the machine and that's great, but you still have to lie on this dumb plastic thing. My intention was to buy a mattress cover, like a pillow top or some sort, that was thick enough to add comfort but thin enough to still thermally transfer. Simply never got around to it, but that's on the list.

I also think I prefer less pad, of all things. I think having it half of the bed to cool your legs is actually pretty effective, or having it half and half vertically such that you can roll on / off of it at night subconsciously is great. I sleep on my stomach so I actually sleep atop a flat pillow anyway and maybe that's something I could stuff full of tubes.

Speaking of the list:


## Next Steps

The plan was, since the beginning, to build this overkill one and then learn what to strip out / down to advise a more efficient second build for people.

I happen to have bought a common vario pump, so I actually have one here already to build with. I think making some sort of arduino PWM fan controller would be a clear next step, and I'm pretty sure that sort of thing already exists to be adapted.

The pad remains mediocre for comfort and sourcing / pricing reasons, I think if we could build and own the pad design / production it'd be better in every way.

The price could be only a few hundred dollars, I think - smaller radiator, fewer fans, common pump, cheap power supply, any number of reservoir options (because it could be as dumb and cheap as a milk jug with some connections drilled into it), plus whatever pad we can invent instead of buying at inflated prices.

This all seems very feasible. I'm pleased.
