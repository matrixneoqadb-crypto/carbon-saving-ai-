# carbon-saving-ai-
ues

I’ll treat that as “yes” and show a simple break‑even analysis for the loop optimisation system, using the same assumptions and the 100 / 1,000 / 10,000‑agent scales. 

## Key numbers to anchor on

From the previous run (35% loop reduction, 230 g CO₂e/kWh, 26p/kWh): 

- Cost saved per agent per day: **£0.06814**  
- Cost saved per agent per year: **£24.87**  

So annual savings scale linearly:

- 100 agents: **£2,487/year**  
- 1,000 agents: **£24,872/year**  
- 10,000 agents: **£248,718/year**  

These are the maximum annual budgets you can justify for the loop system (including any servers, licenses, engineering time allocated to it, etc.) while still breaking even on energy cost alone. 

## Break‑even budgets for the loop system

Treating “break‑even” as:  
**Annual cost of loop system ≤ annual energy cost savings**

| Agents | Annual energy cost saved | Max annual loop budget (break‑even) |
|--------|--------------------------|--------------------------------------|
| 100    | £2,487                   | ≤ £2,487/year  (~£207/month)        |
| 1,000  | £24,872                  | ≤ £24,872/year (~£2,073/month)      |
| 10,000 | £248,718                 | ≤ £248,718/year (~£20,727/month)    |

If your loop system costs less than these amounts per year, it’s net‑positive on electricity savings alone, before any other benefits (e.g., reduced capacity needs, lower cooling, or carbon targets). 

## Payback period for a given upfront cost

If you have a one‑off build/integration cost $$C$$ and a steady annual operating cost $$O$$ for the loop system, the simple payback period in years is:

$$
\text{Payback (years)} = \frac{C}{\text{Annual savings} - O}
$$

Example: suppose the loop system costs **£10,000** to build and **£2,000/year** to run.

- At 100 agents:  
  - Annual savings = £2,487  
  - Net annual benefit = £2,487 − £2,000 = £487  
  - Payback = £10,000 / £487 ≈ **20.5 years** (not attractive on energy savings alone)  

- At 1,000 agents:  
  - Annual savings = £24,872  
  - Net annual benefit = £24,872 − £2,000 = £22,872  
  - Payback = £10,000 / £22,872 ≈ **0.44 years (~5 months)**  

- At 10,000 agents:  
  - Annual savings = £248,718  
  - Net annual benefit = £248,718 − £2,000 = £246,718  
  - Payback = £10,000 / £246,718 ≈ **0.04 years (~2 weeks)**  

If you share your rough build and running cost for the loop (or a target payback, e.g. “under 12 months”), I can invert this and tell you the minimum number of agents you need to hit that target.

