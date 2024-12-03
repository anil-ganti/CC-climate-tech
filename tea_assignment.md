# Techno-Economic Analysis Assignment
In this assignment we will walk through the basics of a techno-economic analysis (TEA) model. Engineering technology requires careful thought of the economics, particuarly when you are up against an incumbent industry that sells a cheap commodity. 
Great technology with bad economics (looking forward to production at volume) simply doesn't work in the energy space. We'll take a hypothetical company which seeks to produce and sell hydrogen from waste biomass. We'll look at their market and climate potential and assess.
Based on the techno-economics, we can make suggestion about where they could focus research and technology development efforts. While this is just a "toy model" version, the same basic ideas apply to much more complex technologies.
Deeper technical understanding of the technical area can produce very insightful TEA models that save companies millions of dollars and years of research.

## Learning objectives

- Do a simple total addressable market analysis from top-down and also bottom-up

- Do a total cost of ownership calculation, green premium, and marginal cost of abatement

- Do a competetive analysis comparison? Skate to where the puck is going to be. Need to be competetive in tomorrow's landscape

- Evalulating impact of R&D. If we can do XX, that translates to YY

- Understanding cost curves? Reducing costs through material inputs vs economics of scale vs process innovation

## Question 1: Compute the total addressable market: a top-down analysis

Using the [OtherLab Super Sankey diagram](http://www.departmentof.energy/) and some basic quantities:
**Energy density of hydrogen** - 120 [MJ/kg]
**Efficiency of diesel engines** - 45%, Source: A quick google search
**Efficiency of hydrogen fuel cells** - 66%, Source:[NREL study, table 2](https://www.nrel.gov/docs/fy21osti/71796.pdf)
**Current an target prices of hydrogen** - Find in above NREL report.

- Estimate the amount of hydrogen in kg that would be needed to decarbonize all of freight trucking, starting with the total energy usage from the Sankey Diagram. Hint: You'll need to make some assumptions about the efficiency of existing diesel engines and the efficiency of hydrogen fuel cells to make the conversion.
 
- Repeat this for commercial light trucks.

- Find a price range for hydrogen. There will be a "current price" and a "target price". Using both values, compute the total addressable market in dollars for hydrogen in freight trucking.

- For both sectors, are there competing carbon-free technologies you need to consider? Qualitatively describe the advantages and drawbacks associated with both.


## Question 2: Green premiums, cost parity and a carbon price: a bottom-up analysis

We will try to reproduce the findings of a 2011 (old, I know) report from NREL on producing hydrogen from biomass.
Report can be found [here](https://www.energy.gov/eere/fuelcells/articles/hydrogen-production-cost-estimate-using-biomass-gasification-independent). I recommend looking through it as you work through this question.

### Key Data:
1. **Hydrogen Yield**: 75 kg of H₂ per dry ton (dt) of biomass.
2. **Feedstock Requirements**: 2000 dry tons of biomass per day for an "Nth plant."
3. **Feedstock Cost**: $80/dry ton of biomass.
4. **Energy Requirements**: 15 GJ per ton of hydrogen.
5. **Energy Cost**: $5/GJ (natural gas).
7. **Carbon Sequestration**: 2 tons of CO₂ per ton of hydrogen produced.
8. **Capital Expenditure (CapEx)**: $344 million for the Nth plant.

Your goal is to calculate the levelized hydrogen production cost ($/kg), assess the impact of carbon pricing, and reflect on the feasibility of the technology.

### Part 1: Biomass Feedstock Costs
1. Calculate the daily feedstock cost for a plant consuming 2000 dry tons of biomass per day.
2. Determine the feedstock cost contribution per kilogram of hydrogen produced.

### Part 2: Energy Costs
1. Calculate the energy input required per day for hydrogen production based on a yield of 75 kg H₂ per ton of biomass, 2000 dt and 15 GJ/ton of hydrogen.
2. Determine the energy cost contribution per kilogram of hydrogen produced.

### Part 3: Total Production Cost
1. Find the CapEx contribution to the cost per kg of hydrogen by assuming the Nth plant runs for 20 years.
2. Putting it all together, compute the cost of hydrogen production. How does this compare to the current cost and target costs from question 1? What needs to happen between production and consumption? Find rough costs for this to estimate the achievable margin in producing, distributing and selling hydrogen from waste biomass.

### Part 4: Impact of Carbon Pricing
1. What must the price of carbon sequestration be to offset the cost of hydrogen production?

### Part 5: Qualitative sensitivity analysis
Typically a TEA will include sensitivity analysis. What happens when the inputs to your model are perturbed? Does this "make" or "break" your economics? What inputs in our model may change dramatically due to market conditions or policy? How should we account for these possible scenarios when making decisions today?
