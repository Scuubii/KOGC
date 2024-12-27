# HARDWARE / PRE-SETUP

## This will run through everything hardware oriented, every category will be specificed.

:D




# CPUs 


As of writing this, the newest Intel CPUs (Core ultra series) are considerably worse then their older counterparts, if you're looking to buy an Intel CPU and newer alternatives haven't been released or proved to be better, look for a a 14700ks / 14900ks (New microcode updates fix the voltage frying the CPU)

If you're looking for AMD I could only really recommend the 9800x3d.

Keep in mind that a STOCK Intel CPU will perform worse on average then a STOCK AMD CPU, on the other hand if both are pushed to the limit, Intel tends to come on top (at the cost of twice the power consumption). At the end of the day it comes down to when you're reading this and what you're looking for in your specific use case, ask yourself, Is this system PURELY for gaming? Am I going to utilize what I'm buying? Do I have the knowledge to completely utilize the hardware I'm buying?

Intel vs AMD debates have mostly died down due to both parties making exceptional CPUs. The only benefit that Intel still has over AMD is a monolithic* CPU DIE design while AMD is utilizing a chiplet* design

monolithic - this refers to the Intel DIE being one singular piece of actual hardware as opposed to AMD's equivalent, without being over-detailed this is technically "faster" latency wise but has limitations in terms of core count and expansion.

chiplet- This is AMD's choice of CPU DIE, it's multiple chiplets tied together by a high speed "transmitter" that relays information between the chiplets, the argument for this being slower is that a part of your real-time program could happen on one chiplet while a whole different chiplet is processing another part of the same program, adding a transmitter means the relaying of this data isn't instant, therefor adding a delay, this delay is VERY slight and most likely a non factor unlesss you're pushing both chips to their limits (while the other conditions are near-perfect)


Fun Fact: After Intel called AMD's chiplet technology "bascially glue" they then used the exact same technology on their new server CPUs, resulting in worse performance and power consumption than AMD for a more expensive price.

Moving on from basics, I want to talk about the specifics of each chip, to put it simply, AMD is a LOT easier to mess around with, this is not a rule but especially on ASUS motherboards, and on newer Ryzen processors, the BIOS is simplified and generally has good descriptions for each setting, this cannot be said for Intel, this could either be an advantage or a disadvantage depending on what you're looking for, as a rule of thumb, take everything AMD as simpler and Intel as more complicated, not to say AMD can't get complex or that Intel is "too hard".

!! A major difference between AMD and Intel CPUs is the MASSIVE L3 cache on AMD processors, I can't go over the entierty of L3 cache in a single guide as it would take forever, you're free to read more on this, I'll mostly skip over this, just know bigger number = better, AMD has more cache while Intel pushes the core clocks further.

I'll be talking more about CPUs in the following section as in a way or another everything connects back to the CPU :D




# RAM


RAM is one of THE most overlooked component out of all, people think they can cheap out on RAM and still get a good experience, this is FALSE, RAM latency is INCREDIBLY important for a system, I really can't stress this enough.

RAM differs vastly on AMD and Intel so I'll be splitting this category into 2 subcategories, feel free to skip to the one corresponding to your processosr.

Regardless of CPU, I would recommend looking and investing into a GOOD motherboard that can run high speed DDR5 RAM, the best motherboards for this are called "2 DIMMERs" that essentially means that they only have 2 DIMMs (2 RAM slots) instead of the 4 you're used to, these can run faster RAM more consistently usually, there usually aren't many high tier 2 DIMM boards on the market, for Intel I can only recommend the Z790-I Lightning and the Z790 Encore.

## Intel

In this case I would recommend pushing RAM speeed as far as it goes on your motherboard (each one will be different depending on many factors) there's plenty of DDR5 overclocking guides on youtube so I won't go into the specifics as this is more of an overview of EVERYTHING, as a rule of thumb, push the speed until it's unstable, dial it back and tune the timings, the timings can be complex on Intel, but a well tuned RAM kit will feel considerably better than just having XMP on.

Keep in mind RAM latency scaling slows down at around 7600 MT/s, but I've seen as high as 8200 MT/s beign used. (this HEAVILY depends on CPU bin* and your specific motherboard)

bin - we use this to define how "lucky" you got when buying your processor, yes! every single CPU is slighlty differnet, some are better, some are worse, there's no way to know this before-hand, this is commonly referred to as the "silicon lottery"

## AMD

AMD is different when it comes to RAM, it prefers slower speeds (6000 Mt/s is commonly referred to as the golden number for AMD, this could also be as high as 6600 Mt/s very rarely)

AMD uses Infinity Fabric (FCLK) to communicate between the CPU and the RAM, take a note of all the abbreviations I'm using, this will be important later

Memory clock (MCLK) = this is the speed the RAM is actually running at, keep in mind this is going to be half of what your RAM is advertized at, if you bought a 6000 Mt/s kit, it will say 3000 mhz as DDR stands for Double Data Rate, if you couldn't tell already, it doubles the actual frequency that it's running at, so whenever you see RAM kits being advertized as 6000 "mhz" just know they ACTUALLY mean 6000 mt/s and 3000 mhz, this could get confusing.

Unified Memory Controller Clock (UCLK) = this should idealy be 1:1 with the MCLK, both figures should be the same, I'll go more in depth with this when I talk about gear modes in the OVERCLOCKING section, this is just to understand the actual hardware.



# Motherboards


## Don't cheap out

Really, that's all I have to say, there's a myth that motherboards don't affect performance. Yeah. Yeah they do, quite heavily, the amount of RAM tuning you can do massivly depends on the quality of motherboard, as said above, the best motherboards have only 2 DIMMs (RAM slots) instead of 4, if you can get your hands on a good 2 DIMM board, good job, you're going to have a more enjoyable RAM overclocking experience and get better results.

That's the most important thing about motherboards but you could also factor in the actual features, how many USBs, what speed those USBs are, what specific NIC (Network Internet Controller) it has, Intel is usually the best, you could also factor in the powre quality that is delivered to the VRMs and other components, though this is minimal.

TLDR: buy a good 2 DIMMer



# GPUs

This is the most simple category

NVIDIA, please don't buy an AMD GPU unless your goal is to daily drive Linux operating systems, AMD is just worse in this field. 

If you want me to tell you the best GPU to buy, it's the most expensive one (wow! really?), you can also get away with cheaper GPUs if you're doing 1080p on non demanding games, I'll go more in depth into this in the Operating System category when I describe latency and how it influences certain factors.

# Storage

Not much to say about this either, buy a fast SSD that has enough storage for your use case, make sure this is not SATA or NVMe, it should be M.2|



# COOLING

Cooling is important if you want to get ANY overclocking results from your CPU, the cooling solution you go to heavily depends on what you want to do.

I feel like any modern CPU should be cooled by AT LEAST a 240mm AIO, please don't get an air cooler, it's just not worth it...

On more demanding CPUs (14900k, 9800x3d) you'd go for a 360mm / 420mm good AIO.

In a PERFECT world you would do what's commonly called "de-lidding" or "direct die cooling" this is an advanced techinique where people take off the "lid" of the CPU, this is the exterior that we all know and love, that's what keeps the interior components of your CPU safe, this is taken off to expose the CPU die itself, the actual thing generating heat, then people apply a cooler directly to this die, bypassing the lid and getting better thermal results. This should only be done if you know what you're doing and are really pushing chips to their limits.

You also need some good case fans, I can recommend Noctua as a company or Arctic, depends on your budget, you should fill up every fan spot in your case.



# Monitor


In this day and age of competitive gaming I don't think anyone should be under 240hz, it's a huge disadvantage, although I understand monitors can get expensive so I'll go over budget ranges here


Super budget: find the cheapest 240hz 1ms monitor that you can and buy that. Simple.

Moderate budget: Try to find a quality 240hz monitor, somthing 0.5ms and by BENQ

Decent budget: this is where you start looking for 360hz monitors, I can recommend BENQ again as a manufacturer or ASUS.

High Budget: You can start looking for OLED monitors (no they don't burn-in, yes they are better in every way, no it's not just visuals) this again shouldn't be under 240hz, try to avoid Alienware.

Unlimited budget: The only step up is whatever the fastest OLED is, 360hz OLEDs have hit the market and they're amazing, very recently we've also seen 480hz OLED but it's in the primitive stages, also no computer on earth can hold 480hz in most games (exclude Valorant, Overwatch 2, Cs2, etc)


# Mouse

I don't need to explain how important buying a good mouse is, I'll also go over mouse skates in the same category because why not.

I'm a huge fan of WIRED mice (yes! wired in 2024, insanity), I can only make the comparison of WI-FI versus Ethernet to prove my point, although anyone should understand that wires are automatically faster then wireless signals, this does not mean I recommend any cheap wired mouse, I only really have a singular wired mouse that I love and personally use, that would be the Endgame Gear OP1 8k.

On the other hand I won't blame you if you're going wireless, buy whatever new flagship comes out while you're reading this, currently we have the Viper V3 Pro from Razer and the Superlight V2 from Logitech.

When talking about moue polling rate you have to factor in A LOT of differnt things, as a rule of thumb, 1000hz is fine, 8000hz is mostly a buzz-word and doesn't yet have any real world use cases, I wouldn't recommend using 8000 polling rate on any mouse (ESPECIALLY if it's WIRELESS), if you really want to use a higher polling rate, use 2000hz.

As for mouse skates, just go for high quality aftermarket PTFE skates (not valid if you're using a GLASS mousepad, only on cloth), I don't have enough experience to give recommendations, go look into Boardzy's youtube channel, he makes the best mouse / mousepad / mouse skates content on Earth



# Keyboard

At the time of me writing this there are really only 2 keyboards worth buying, the Apex Pro Mini and the better Wooting 60HE / 80He.

The Wooting is undeniably better then the Apex, better software, better integration and better latency, all this being said I wouldn't mind using either keyboard, they're both amazing, just please don't buy some boot-leg Wooting that you heard about on Tiktok, no they aren't the same.

Not much to say about keyboards, turn the actuation point to the lowest on all keys and enable rapid trigger on all keys, if your game supports SOCD or a form of it, enable that too. 

As a plus you can set all RGB to static or OFF (this goes for everything BTW, RGB sucks, try to buy products without it or disable it)

