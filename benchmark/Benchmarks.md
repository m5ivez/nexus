# Benchmarks
## Methodology
Benchmarks are done by firing the event 1000 times per frame with the same data every frame for 10 seconds.<br>

**Credits to Blink for this networker, everything is completely redone with my computer & latest versions of all the networkers.**<br>

Benchmark done by 1Axen can be found [here](https://github.com/1Axen/blink/blob/main/benchmark/Benchmarks.md).<br>
Data used for benchmarks can be found [here](https://github.com/1Axen/Blink/blob/main/benchmark/src/shared/benches).<br>
Definition files used for benchmarks can be found [here](https://github.com/1Axen/Blink/blob/main/benchmark/definitions).

## Results

`P[NUMBER]` = [NUMBER] Percentile  
*The tables below are calculated averages across multiple test runs.*

## Last Updated 2026-10-20 21:38:49 CEST

## Tool Versions
- `nexus`: Latest
- `blink`: v0.18.9
- `zap`: v0.6.29
- `bytenet`: v0.4.3

## Computer Specs
- Processor: `AMD Ryzen 5 2600 Six-Core Processor`
- Graphics Card: `NVIDIA GeForce RTX 3050`
- Memory #1: `8GB 2666`
- Memory #2: `8GB 2666`

## Averages
|Tool|Booleans Avg FPS|Booleans Avg Kbps|Entities Avg FPS|Entities Avg Kbps|Sent Packets (Avg)|
|---|---|---|---|---|---|
|roblox|15.00|138708.06|16.00|449541.53|49125|
|blink|51.25|8.33|22.50|41.92|365750|
|zap|27.50|8.77|22.00|42.03|248125|
|bytenet|18.00|8.97|16.00|41.55|168750|
|nexus|58.00|17.43|60.00|583.59|586750|

## Entities
|Tool (FPS)|Median|P0|P80|P90|P95|P100|Loss (%)|
|---|---|---|---|---|---|---|---|
|roblox|16.00|16.00|16.00|16.00|16.00|15.00|0%|
|blink|22.50|26.25|21.50|21.50|21.50|21.25|0%|
|zap|22.00|23.75|22.00|22.00|22.00|21.00|0%|
|bytenet|16.00|17.25|15.50|15.00|15.00|15.00|0%|
|nexus|60.00|60.25|60.00|59.75|59.75|59.25|0%|

|Tool (Kbps)|Median|P0|P80|P90|P95|P100|Loss (%)|
|---|---|---|---|---|---|---|---|
|roblox|449541.53|449541.53|449541.53|449541.53|449541.53|655685.53|0%|
|blink|41.92|26.64|43.14|43.65|43.65|43.99|0%|
|zap|42.03|28.25|42.96|43.14|43.14|44.06|0%|
|bytenet|41.55|26.34|43.12|44.11|44.11|45.09|0%|
|nexus|583.59|542.24|588.22|589.76|589.76|592.19|0%|

## Booleans
|Tool (FPS)|Median|P0|P80|P90|P95|P100|Loss (%)|
|---|---|---|---|---|---|---|---|
|roblox|15.00|16.00|15.00|15.00|15.00|15.00|0%|
|blink|51.25|52.25|50.00|49.00|49.00|47.00|0%|
|zap|27.50|29.00|27.00|26.75|26.75|26.50|0%|
|bytenet|18.00|19.00|18.00|17.25|17.25|17.25|0%|
|nexus|58.00|58.50|57.25|57.00|57.00|56.00|0%|

|Tool (Kbps)|Median|P0|P80|P90|P95|P100|Loss (%)|
|---|---|---|---|---|---|---|---|
|roblox|138708.06|100448.87|178403.72|178403.72|178403.72|224171.37|0%|
|blink|8.33|7.02|8.48|8.56|8.56|8.70|0%|
|zap|8.77|6.41|9.01|9.05|9.05|9.14|0%|
|bytenet|8.97|6.13|9.19|9.29|9.29|9.52|0%|
|nexus|17.43|15.32|17.65|17.73|17.73|17.86|0%|
