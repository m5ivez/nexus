# Nexus

[![GitHub License](https://img.shields.io/github/license/m5ivez/nexus?style=flat-square&color=%23a350af)](LICENSE)

A high-performance and secure Luau buffer networking library for Roblox.  
*Inspired by Blink.*

# Performance

Nexus aims to make networking as fast and lightweight as possible:

- **Lower Bandwidth:** Packing numbers, strings, and booleans into raw buffers means significantly smaller packet sizes.
- **Higher FPS & Less Lag:** Sending smaller batches and processing data.
- & Way more.<br>

You can check out the benchmarks [here](./benchmark/Benchmarks.md). This compares Nexus with other Networkers.<br>

# Why Nexus over Blink or Zap?

Blink and Zap are awesome tools, but Nexus is built with a few different priorities:

- **Tighter Default Security:** Nexus shuffles event structures dynamically per player session instead of using predictable, static packet formats across the entire game.
- **String Deduplication:** Frequently repeated strings are compressed on the fly so you don't waste bandwidth sending the same text back and forth.
- & Way more.

**This networker is currently in use on the following game:**
- [Bayview County, USA](https://www.roblox.com/games/72523637494021/Bayview-County)

# Release Date
n/A

# Credits
Huge credit to [1Axen](https://github.com/1Axen) for the inspiration and benchmark setup.
