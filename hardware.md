HARDWARE / PRE-SETUP
Overview
This section covers hardware essentials, with categories clearly specified.

# CPUs


## Intel


As of now, Intel’s latest Core Ultra series CPUs are underwhelming compared to their predecessors. If you’re in the market for an Intel CPU and no newer, better alternatives are available, the 14700KS or 14900KS are your best options. Recent microcode updates have resolved the voltage issue that caused CPUs to fry.

Intel has been the leader in processors for decades, peaking around 2013. However, recent issues like microcode problems with 13th and 14th-gen CPUs, leading to physical damage, and the disappointing Ultra Core series release have caused a decline in market share and consumer confidence.

## AMD


For AMD CPUs, the 7800X3D and the newer 9800X3D are standout choices, especially for gaming. AMD has seen significant growth since the early 2010s, capturing a major share of the gaming market.

AMD’s platform is robust and gaming-focused. While they offer CPUs tailored for workloads, dual-CCD processors can introduce latency. However, AMD’s server processors are undisputedly superior to Intel’s in performance and efficiency.

## Design Differences

The Intel vs. AMD debate has largely faded, as both brands now produce exceptional CPUs. Intel’s monolithic CPU die design provides slightly lower latency, whereas AMD’s chiplet-based design allows for higher core counts and scalability.

Monolithic (Intel): The CPU die is a single piece, which minimizes latency but limits scalability.
Chiplet (AMD): Multiple chiplets are connected via a high-speed interconnect. While this introduces slight latency, it allows for greater scalability and cost efficiency.

Fun fact: Intel criticized AMD’s chiplet design, calling it “glue.” Ironically, Intel later adopted the same technology for its server CPUs, which delivered worse performance and efficiency compared to AMD's counterparts.



# RAM


## General Notes
RAM is one of the most overlooked components in a PC build, yet latency is crucial to overall system performance. Investing in high-quality RAM and a capable motherboard is essential.

For the best results, use motherboards with only two DIMM slots ("2 DIMM boards"), as they allow for higher RAM speeds and better overclocking consistency. Recommended models include:

Intel: Z790-I Lightning, Z790 Encore
AMD: X870E Crosshair Hero, X870E-E

## Intel

Push RAM speeds as high as your motherboard and CPU can handle. Most Intel systems see diminishing returns beyond 7600 MT/s, although speeds up to 8200 MT/s are possible with high-end setups. RAM tuning on Intel is highly rewarding, but achieving optimal results may require meticulous manual adjustments.

## AMD

AMD prefers lower RAM speeds compared to Intel. The "golden standard" for AMD systems is 6000 MT/s, though rare setups can handle up to 6600 MT/s. AMD's Infinity Fabric (FCLK) ties CPU and RAM performance closely together, so ensuring a 1:1 ratio between memory clock (MCLK) and Unified Memory Controller Clock (UCLK) is critical for stability.

## Motherboards


Key Advice

Do not skimp on your motherboard. The quality of your motherboard significantly impacts RAM tuning, overclocking capabilities, and overall system performance.

Recommendations
Intel:

Z790 Encore (Best overall)
Z790-I Lightning (Solid choice)


AMD:

X870E Crosshair Hero (Best overall)
X870E-E (Budget-friendly alternative)


# GPUs

This category is straightforward:

Buy NVIDIA.
Avoid AMD GPUs unless you plan to use a Linux-based operating system.
For gaming at 1080p or non-demanding titles, mid-range GPUs are sufficient. For cutting-edge gaming and workloads, invest in the most expensive NVIDIA GPU you can afford.


# Storage


Opt for a fast M.2 NVMe SSD.
Avoid SATA SSDs unless cost is a major factor.
For bulk storage or NAS setups, refurbished 8TB+ hard drives are a cost-effective option.


# Cooling


General Tips

Effective cooling is crucial for overclocking and CPU longevity. For modern CPUs, at least a 240mm AIO is recommended. Air coolers are less efficient and not worth considering for high-performance builds.

For high-end CPUs (e.g., 14900K, 9800X3D), use a 360mm or 420mm AIO.

## Advanced Techniques: Direct Die Cooling

Direct die cooling involves removing the CPU’s lid (IHS) to apply the cooler directly to the die for better thermal performance. This technique is advanced and can permanently damage your CPU if done improperly. Key points:

Sand down the IHS to improve thermal transfer.

Use high-quality thermal paste, such as Kryonaut or liquid metal (exercise caution with liquid metal to avoid short circuits).


# Monitor

This is one of the most importat things you can buy, the difference between a cheap 240Hz monitor and a 360Hz OLED monitor is insane.

Super Budget: Cheapest 240Hz, 1ms monitor available.

Moderate Budget: 240Hz, 0.5ms monitor (e.g., BENQ).

Decent Budget: 360Hz monitors from BENQ or ASUS.

High Budget: 240Hz OLED monitors.

Unlimited Budget: High-refresh OLEDs (360Hz or experimental 480Hz).


# Peripherals


## Mouse

For wired mice, the Endgame Gear OP1 8K is a top choice. For wireless, the Razer Viper V3 Pro and Logitech Superlight V2 are excellent options. Avoid using 8000Hz polling rates due to interference with wirless mice, deviations and general bugs with game engine; 1000Hz or 2000Hz are better choices.

## Keyboard

The Apex Pro Mini and Wooting 60HE/80HE are the best keyboards available. The Wooting is superior, offering better latency and software integration. Use the lowest actuation point and enable rapid trigger for competitive gaming.

## Final Notes


Disable RGB wherever possible—it adds no value beyond aesthetics.

For further optimizations, check the [BIOS](https://github.com/Scuubii/KOGC/edit/main/bios.md) section
