# <img src="56870.jpg" width="70" style="vertical-align: middle; margin-right: 10px;"> Rehoboth Research LLC


## Whitepaper: Bitcoin Mining & The Solar Opportunity
**Authored by Besa Masaiti: besa@rehobothresearch.org**


## Structure
- Executive summary
- Introduction: The Bitcoin Mining Landscape
- The Energy Challenge in Bitcoin Mining
- Solar as a Strategic Solution
- Integration: Solar-powered mining and AI Data Centers
- Risks & Feasibility
- Bitcoin Price Volatility and IRR Sensitivity  
- Roadmap
- Sources Cited
- Contact Rehoboth Research


---

## Executive Summary

Seventeen years after Satoshi Nakamoto published the Bitcoin whitepaper, Bitcoin has evolved from a peer-to-peer electronic cash system into a globally distributed settlement network secured by proof-of-work computation. Public discourse around Bitcoin focuses on price volatility, speculation and often comparisons to gold and the S&P500, which have market caps of: **$1.8T**, **$31T** and **$58T** respectively (as of 2025). #Add market cap numbers of all 3. However, there is a more pertinent factor that needs addressing, and that is energy. 

Bitcoin is valuable not because of speculation but because it is backed by a real-world annual **630 billion MJ of high energy demand** required to secure the Bitcoin network. However, the same energy intensity that secures the network has become the primary constraint on mining profitability, regulatory acceptance, and long-term sustainability. Per the Cambridge Bitcoin Electricity Consumption Index, Bitcoin mining currently consumes an estimated **195.9 tWh** of electricity annually-more than nordic countries like Norway(**124 tWh**) as measured by the World Population Review’s Electricity Consumption per country's 2023 data set. 

![Electricity Consumption per country 2023](electricity_consumed_per_country_2023.png)
*Electricity Consumption per Country, 2023.*
Source: [World Population Review (2023)](https://worldpopulationreview.com/country-rankings/electricity-consumption-by-country). *Vizualization modified by author*


The process, which relies on fossil fuels like coal for ~48% of global activity- emits an approximate 39M metric tones(conservative estimates) -98M metric tones(fossil fuel-intensive estimates) of carbon dioxide annually, a greenhouse gas attributed to global warming. Furthermore, electricity-backed by energy, as an operational expense for bitcoin miners accounts for 60-80% of operational expenses. 

This whitepaper argues that the future competitiveness of Bitcoin mining depends on a structural shift toward low-cost, off-grid renewable energy sources in high-irradiance regions. Specifically, it evaluates solar energy deployment in Botswana as a strategic opportunity for Bitcoin miners seeking to reduce operating costs, mitigate regulatory risk, and improve long-term economic resilience.

This paper: 
- Quantifies Bitcoin mining’s energy requirements and cost structure
- Evaluates the economic case for solar-powered, off-grid mining
- Models a Botswana-based solar microgrid achieving **~$0.08/kWh LCOE**
- Evaluates mining profitability under energy & Bitcoin price volatility
- Proposes a scalable roadmap for solar-powered compute infrastructure 

## Introduction: The Bitcoin Mining Landscape

Bitcoin mining is the computational process that secures the bitcoin network and introduces new $BTC into circulation. It relies on a proof-of-work consensus mechanism in which miners compete to solve difficult **SHA-256** based cryptography puzzles. The reward for solving each puzzle is currently **~3.125 $BTC** plus some transaction fees.  

### Block reward formula
$$
Reward_t = \frac{50}{2^{\left\lfloor \frac{\text{Current Block}}{210000} \right\rfloor}}
$$

Bitcoin’s issuance follows a fixed, anti-inflationary tokenomics model with a maximum supply of **21M bitcoins**. Approximately **19M bitcoins** are in circulating supply and it is estimated that bitcoin mining will cease by the year 2140 with rewards for miners decreasing over time.

![$BTC supply curve since inception](btc_supply_circulation.png)
*All-time total $BTC circulating supply.*
Source: [Blockchain.com](https://www.blockchain.com/explorer/charts/total-bitcoins). 

This is because Bitcoin supply is governed by halving economics. This means, the reward for bitcoin mining decreases by half every **210K blocks**- approximately every 4 years. As a result, miners depend on higher ASIC efficiencies plus reduced electricity costs to keep their profit margins, making energy costs a central determinant of profitability. 

The hardware used to mine bitcoin can range from: application specific integrated circuits(ASICs,specialized hardware optimized for SHA-256 hashing) to CPUs and GPUs. ASICs are the most widely used due to their higher efficiency and higher hash rate output. Hash rate in this context, refers to the rate at which an ASIC or bitcoin mining tool can solve the aforementioned cryptography problems-whose difficulty increases with time.

### Mining Difficulty 
$$
Difficulty_t = Difficulty_{t-1} \times \frac{\text{Time for 2016 Blocks}}{2\ \text{Weeks}}
$$

Hash rate is a key performance indicator in determining profitability for Bitcoin miners and is measured in H/s(Hashes per second). Typical ASIC efficiency is also measured in Joules per Terahash(J/TH).

While ASIC efficiency continues to improve, mining hardware requires significant energy input and contributes to global e-waste as older machines become obsolete. Notably, companies like Mara Holdings have done much to ensure any excess energy from bitcoin mining can be rerouted to heat homes, as seen with their pilot project-heating around **11K** homes in Finland. 

Miners face increasing regulatory pressure related to sustainability, grid impact & congestion and emissions. As block rewards decline and competition for hash rate intensifies, the industry is shifting toward low-cost, stable and scalable renewable energy sources as a strategic necessity alongside an eventual reliance on transaction fees. 

## The Energy Challenge in Bitcoin Mining

Mining bitcoin carries a range of operational expenses. These include: 
- ASICs procurement and depreciation
- Cooling infrastructure and thermal management
- Labor and maintenance costs
- Housing and land costs
- Electricity costs which make up **60-80%** of OPEX depending on the miner.

Electricity costs measured in $/kWh, range significantly by geo-location.Before 2022, most bitcoin mining operations were carried out in China(60% of the hash rate) due to cheap coal-based electricity backed by high government subsidies as well as a Hydro-electric power mix. However, following regulatory crackdowns on energy-intensive activities and concerns over grid stability and emissions, bitcoin mining was outlawed. Today, miners operate in different countries like: Iran, Kazakhstan, some parts of China and Russia, some U.S.A states, parts of Africa and Latin America.

![Global Hashrate Distribution](btc_hashrate_2025_country.jpg)
*Global Hashrate Distribution(2025).*
Source: [hashrateindex.com](https://hashrateindex.com/blog/top-10-bitcoin-mining-countries-of-2025/). 

Energy is cheapest in regions like Iran and Kazakhstan which are coal-based and in some states like Texas and Kansas which offer incentives to bitcoin miners who relocate to them. Western countries like Ireland offer higher tariffs(electricity costs) for miners due to a higher residential usage/ demand for electricity. 

A Cambridge Digital mining report also stated that miners’ electricity mix is predominantly sustainable **(52.4%)**, with renewables accounting for **42.6%**. Hydropower constitutes the largest sustainable source **(23.4%)**, followed by wind **(15.4%)**, nuclear **(9.8%)**, solar **(3.2%)**, and other renewables **(0.5%)**. Fossil fuels make up **47.6%**, primarily natural gas **(38.2%)**, which is also the single largest energy source, followed by coal **(8.9%)** and oil **(0.5%)**. 

![Renewable vs Non-Renewable Energy Share](renew_nonrenew_share.png)
*Renewable vs Non-Renewable Energy Share(April 2025).*
Source: [Cambridge Digital Mining Industry Report](https://www.jbs.cam.ac.uk/wp-content/uploads/2025/04/2025-04-cambridge-digital-mining-industry-report.pdf). *Vizualization modified by author*

![Renewable Energy Shares](renew_share.png)
*Renewable Energy Share(April 2025).*
Source: [Cambridge Digital Mining Industry Report](https://www.jbs.cam.ac.uk/wp-content/uploads/2025/04/2025-04-cambridge-digital-mining-industry-report.pdf). *Vizualization modified by author*

![Non-Renewable Energy Shares](nonrenew_share.png)
*Non-Renewable Energy Share(April 2025).*
Source: [Cambridge Digital Mining Industry Report](https://www.jbs.cam.ac.uk/wp-content/uploads/2025/04/2025-04-cambridge-digital-mining-industry-report.pdf). *Vizualization modified by author*

Grid-connected mining operations face several structural risks:
- Public and Environmental Scrutiny: High energy use often leads to media attention and negative public perception, which can influence regulatory action and hinder business expansion plans. This can be seen with President Trump's recent announcement on Truth Social to ensure data centers ‘pay their fair share’ of electricity costs due to grid-connected participation.
- Regulatory exposure: In the US, the U.S Energy Information Administration recently moved to initiate a provisional survey of electricity consumption for U.S cryptocurrency mining companies, which was paused after a series of those companies sued it. 
- Forced shutoffs during high-demand periods: Grid-connected operations often have to shut down operations during high demand periods, to allow for energy use by more critical infrastructure and stabilize prices which has an effect on expected profitability. 

*Off-grid mining, by contrast, offers energy sovereignty. Miners that generate their own electricity avoid grid congestion, price spikes, and curtailment mandates, while gaining greater control over operating costs and regulatory exposure.*

As block rewards decline and competition intensifies, energy economics not hardware alone-becomes the primary determinant of mining viability.
Solar energy, particularly in regions with exceptional irradiance such as Botswana presents a strategic opportunity to address energy demands and mandates for sustainable energy use.


## Botswana’s Solar as a strategic solution

![Botswana Photovoltaic potential](bw_photovoltaic_potential.png)
*Botswana Photovoltaic potential.*
Source: [Solar resource map © 2021 Solargis](https://solargis.com/resources/free-maps-and-gis-data?locality=botswana). 

Botswana is a landlocked, Southern African country with approximately 2.5M people, lying on **581,730 $km^2$** of land. It boasts about **3200 hours** of annual sunlight and a direct normal irradiance(**DNI**) of about **1900+kWh/$m^2$/year**. DNI measures the amount of solar radiation hitting a surface per area, that is perpendicular to the sun’s rays. An alternative measure is **GHI**, which measures the total solar radiation hitting a horizontal surface- Botswana’s is around **21MJ/$m^2$** with peaks of up to **45MJ/$m^2$** annually. 

This environment, combined with the country’s government’s **Vision 2036** to ensure 50% of energy generated is renewable, creates an optimal environment for miners seeking to pivot to a geo-location with cleaner and cheaper energy-given that the cost of solar energy has declined by over 80% this past decade.

__Solar energy generation consists of two main approaches: Concentrated solar power(CSP) and photovoltaic systems. Our focus will be on the latter, due to its wide usage in utility scale solar projects- most relevant for bitcoin miners.__


## Photovoltaic Systems in Solar Energy

A photovoltaic systems broadly, involve the usage of silicon based panels made up of cells that trap photons from solar radiation which offset electrons in the silicon cells creating a direct current( DC) which is then converted into alternating current(AC)  using inverters and then transported via cables to transmitters which transport the electricity to target areas like: residentials, commercials, utility scale project etc. 

$$
Sunlight ->DC(panels)->AC(inverters)-> Homes, businesses, utility scale facilities
$$

There are three well known types of photovoltaic systems: 
- Monocrystalline: Silicone solar cells manufactured using the Czochralski method from single silicone crystals.
- Polycrystalline: Silicone solar cells manufactured using multiple silicone crystals.
- And Thin film: Made from photovoltaic material deposited onto a backing plate made of substrate like glass, aluminium etc.

|Type| Efficiency| Cost in **$/Watt**|
|----|-----------|-------------------|
|Monocrystalline|17-22%|$1-$1.5|
|Polycrystalline|15-17%|$0.9-$1|
|Thin film|10-13%|$0.5-$1|

### Levelized cost of energy (LCOE) Financial Modelling Methodology

To quantify the economic incentive for bitcoin miners to pivot to using Botswana based solar energy, we modelled a levelized cost of energy(**LCOE**) for a 1.5 MW solar microgrid pilot project.
Key Assumptions:
- Capacity factor: ~20%
- Discount rate: 8%
- Project lifespan: 20
- CAPEX + OPEX: ~$1.3M(base case with **$200K** reserved for battery storage)
- Panel degradation: A degradation annual rate of 0.5% for the solar panels, which does impact solar output
- Socio-political and regulatory climate: Stable economic and political conditions and friendly environment for renewable energy independent power producers

### LCOE formula 

$$ LCOE = \frac{\sum_{t=1}^{n} (CAPEX_t + OPEX_t )}{\sum_{t=1}^{n} Energy\ Output_t} $$


Our base-case model estimates a **$0.08/kWh LCOE**. To account for capital cost uncertainty, a Monte Carlo simulation was conducted with CAPEX treated as a stochastic variable. Simulated outcomes produce a **10th–90th percentile** LCOE range of approximately **$0.071–$0.091/kWh**, with a mean near **$0.08**.

![LCOE Probability Distribution](LCOE_prob_distr.png)
*Simulated LCOE probability distribution for solar generation.*  
Source: [ourworldindata](https://ourworldindata.org/grapher/solar-pv-prices), [seef.co.bw](https://www.seeff.co.bw/results/vacant-land/?advanced_search=a0660ee01fe52a19f5723763268231c6&main_type=commercial), [sinovoltaics.com](https://sinovoltaics.com/learning-center/consumers/labor-costs-installing-solar-panels/), [fnbbotswana.co.bw](https://www.fnbbotswana.co.bw/for-my-business/value-adds/index.html#:~:text=Comprehensive%20cover%20for%20the%20unexpected&text=The%20cover%20ranges%20from%20P120,policy%20documents%20are%20issued%20immediately.), [taxsummaries.pwc.com](https://taxsummaries.pwc.com/botswana/corporate/taxes-on-corporate-income). *Author calculations & vizualization*

__The model assumes a flexible mining load that dynamically scales with solar generation, minimizing the need for costly battery storage. This design prioritizes capital efficiency over continuous uptime and is appropriate for pilot-scale deployments.__

![kWh Differences](kWh_cost.png)
*$/kWh cost differences.*  
Source: [pvknowhow.com](https://www.pvknowhow.com/solar-report/botswana/), [pvknowhow.com](https://www.pvknowhow.com/solar-report/botswana/) *Author calculations and visualization*

### Noteable benchmarks 
It is also worth mentioning, benchmarkable case studies of African countries where renewable energy  pilots have been constructed to power bitcoin miners. These include:
- Kenya: In March 2024, Marathon Digital announced a signed deal with Kenya, wherein MARA will be capitalizing on Kenya’s underutilized Geothermal energy resources to power their operations. 
- Ethiopia: UAE-based Phoenix Group, signed a 80MW power purchase agreement with EEP(Ethiopian Electric Power) leveraging primarily hydropower energy, announced January 2025. Though in Q3 2025, EEP announced plans to phase out $BTC miners due to the strain on the electric grid that they pose. 

Recent academic literature on cryptocurrency mining and carbon emissions argues that mining should be incentivized in regions ranked higher in the Environment Performance Index, which takes into account: energy price, energy generation, sources, temperature, legal constraints, human capital, R &D. However, the literature primarily focuses on markets with mature energy infrastructure, overlooking high-irradiance regions where renewable energy generation potential is substantial but underdeveloped due to limited capital or generation capacity.

__Botswana offers high solar output, stable peace and economic conditions and an opening for (foreign direct investment) FDI, especially Bitcoin miners seeking ways to drive down OPEX due to electricity in order to remain profitable.__

## Integration: Solar + Bitcoin + AI

In the last 2-3 years, large-scale Bitcoin mining operators have pivoted to maximizing usage of their facilities by integrating both bitcoin mining and AI data hosting. This is in part due to shared economic and operational characteristics:
- High Computational intensive nature
- Mutual need for efficient cooling systems/ hardware
- Dependence on low-cost electricity 

Leveraging their facilities for their already set: cooling systems, access to energy via independent production/ signed PPAs to serve both bitcoin mining and AI services has proven not only strategic but economically positive for bitcoin miners. An estimate shows converting existing sites for AI hosting can earn miners **$1-4M per MW annually**. 

By colocating Bitcoin mining and AI workloads around a shared renewable energy source, operators can significantly improve asset utilization and revenue stability. This is a version of colocation that this paper presents- referring not just to shared cooling or physical infrastructure, but to the strategic co-siting of multiple compute workloads around a common renewable energy source.


### Load Stacking
Despite their technological similarities, bitcoin mining and AI infra differ in how they absorb or use energy from the grid. In our assumed off-grid solar microgrid model:
1. Solar produces excess power midday with flexible loads that ‘turn off’ during none daylight hours with some energy storage
2. Bitcoin mining acts as a flexible, interruptible load
3. AI workloads (training, inference, data labeling) can be scheduled during predictable generation windows

$$
Solar generation -> AI priority load -> Bitcoin mining (spillover/ flexible)
$$

Under this model:
- Solar energy first serves priority AI workloads
- Excess generation is absorbed by Bitcoin mining
- Mining curtails automatically when generation declines


This ***load stacking*** approach transforms intermittency from a liability into a feature. Bitcoin mining monetizes surplus energy that would otherwise be curtailed, while AI workloads generate higher-margin revenue during periods of reliable supply.

### Economic Implications
Colocated compute infrastructure:
- Increases revenue per MW of installed capacity
- Improves project IRR
- Reduces exposure to Bitcoin price volatility
- Preserves upside optionality during bull markets

This strategy reframes Bitcoin mining not as a standalone activity, but as a flexible energy-balancing layer within renewable-powered compute campuses.

## Risks
**1. Technical Risks**

|Risk| Mitigation|
|----|-----------|
|Solar intermittency|Flexible load|
|Equipment Degradation| Conservative capacity factor|
|Cooling in high-temperature environments| Modular scaling|

**2. Economic Risks**

|Risk| Mitigation|
|----|-----------|
|BTC price volatility|Monte Carlo modelling|
|ASIC obsolescence |Short hardware depreciation assumptions|
|CAPEX inflation |Optional dual-use compute|

**3. Regulatory & Policy Risks**

|Risks| Mitigation|
|-----|-----------|
|Energy Policy changes|Botswana’s stable regime|
|Mining restrictions| Off-grid set-up reduces grid exposure|
|Import duties/ licensing relays| Pilot-scale footprint|


**4. Execution Risks**

Risks|Mitigation|
|----|----------|
|Solar site feasibility risk|Rehoboth Research proprietary AI/ML feasibility MVP that classifies solar-viable sites across Botswana using irradiance, land-use, and terrain data, reducing early-stage CAPEX misallocation|
|Supply Chain delays|EPC partnerships|
|Skilled labor shortages|Phased deployment|
|Project overruns|Conservative timelines|

## Bitcoin Price Volatility and IRR Sensitivity

$BTC being a speculative asset means profitability for miners also depends on the volatility of the asset’s price. 
### Formula
$$
Profit_t = (BTCreward_t × BTCprice_t) − (Energycost_t + OPEX_t)
$$

We estimated that profitability of mining bitcoin is sensitive to price swings of the cryptocurrency by XX- a key metric that must be taken into account when modelling profitability margins for miners.

## Roadmap & Timelines

**Phase 0 Pre-pilot (3–6m)**  
`[■■■■■■]` Launch Solar feasibility MVP

**Phase 1 Pilot (0–12m)**  
`[■■■■■■■■■■■■]` 1–2 MW solar pilot· flexible mining load · data collection · regulatory alignment

**Phase 2 Optimization(12–36m)**  
`[■■■■■■■■■■■■■■■■■■■■■■]` Scale to 5–10 MW · Optional storage · Hybrid AI workloads

**Phase 3 Replication(36m+)**  
`[■■■■■■■■■■■■■■■■■■■■■■]` Regional expansion · Infra fund model

**Key Metrics by Phase**
- Phase 1: LCOE achieved, Uptime , Hashrate per $ CAPEX  
- Phase 2: Cost per MW subsidized, Revenue stability, Load efficiency  
- Phase 3: IRR, Payback period, Portfolio diversification  

## Sources Cited

## Contact Rehoboth Research
**Rehoboth Research LLC is a Pennsylvani- basedspecialized research firm focused on the convergence of renewable energy, high-performance compute, and decentralized finance. We provide data-driven feasibility studies and strategic roadmaps for infrastructure investors and technology operators in the SADC region.**

**Get in Touch**

For inquiries regarding our Solar Feasibility MVP, research & consulting services, or to discuss the data models used in this paper, please reach out via the following channels:

**Founder & Financial Research Analyst: ***Besa Masaiti***

Email: **besa@rehobothresearch.org**

X (Twitter): https://x.com/BesaMasaiti

LinkedIn: https://www.linkedin.com/in/besa-masaiti/

**Legal Disclaimer**:
*This white paper is for informational and research purposes only and does not constitute financial, investment, or legal advice. The calculations, including Levelized Cost of Energy (LCOE) and Internal Rate of Return (IRR) estimates, are based on current market data and stochastic modeling which are subject to change. Cryptocurrency mining involves significant risks, including asset volatility and regulatory shifts. Rehoboth Research LLC shall not be held liable for any financial losses or decisions made based on the contents of this document.*
