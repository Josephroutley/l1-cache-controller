# L1 Cache Controller with Arbitration

## Project Overview
This project involves the design of a Direct-Mapped (or Set-Associative) **L1 Cache Controller**. It sits between the CPU core and Main Memory, handling data requests to minimize latency.

It includes an **Arbiter** to manage competing requests from the Instruction Fetch and Data Load/Store units.

## Learning Objectives (NVIDIA Target Skills)
* **Computer Architecture:** Understanding Tag, Index, Offset, and Cache Hit/Miss logic.
* **Arbitration:** Implementing Round-Robin or Fixed-Priority arbitration schemes.
* **Memory Hierarchy:** Managing the flow of data between fast cache and slow main memory.

## Architecture
* **Tag RAM & Data RAM:** Storage for cached lines.
* **Cache FSM:** Handles Idle, Compare, Allocate, and Write-Back states.
* **Arbiter:** Decides which requestor (Instruction vs. Data) gets access to the cache.

## Tools & Tech Stack
* **Language:** SystemVerilog

## Roadmap
- [ ] Implement Tag and Data arrays.
- [ ] Design the Cache FSM (Hit/Miss detection).
- [ ] Implement the Arbiter logic.
- [ ] Simulate simple Read/Write traces to verify Hit/Miss behavior.
