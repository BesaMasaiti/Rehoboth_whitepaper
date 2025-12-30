Bitcoin Mining & The Solar Opportunity: Authored by Besa Masaiti
Structure: Executive summary, Introduction: The Bitcoin Mining Landscape, The Energy Challenge in Bitcoin Mining, Solar as a Strategic Solution, Integration: Solar-powered mining and AI Data Centers, Risks & Feasibility, Roadmap

Executive Summary
It’s been 17 years since Satoshi Nakamoto published the Bitcoin whitepaper. He/she/it introduced a peer-to-peer cashless system that allows peers to interact in a trustless SHA-256 backed environment- cutting out middle men and their associated transaction costs. Bitcoin offset industry launches such as: Decentralized exchanges, price oracles, tokenized real-world-assets, supply chain logistics enhancement and even peer-to-peer betting platforms such as Kalshi and Polymarket. 

Much of the public’s focus when it comes to Bitcoin, is $BTC the cryptocurrency, its volatile speculation and sentiment driven price moves and often comparisons to gold and the S&P 500. #Add market cap comparisons of all 3. However, there is a more pertinent factor that needs addressing, and that is energy. Elon Musk recently pointed out that Bitcoin is valuable not because of speculation but because it is backed by real-world high energy demand required to secure the Bitcoin network. Energy is obviously a big part of everyday life on earth-from: lighting homes, to modes of transport, to powering AI data centers and even now bitcoin mining operations.

Bitcoin mining currently consumes an estimated 175 tWh of electricity annually-more than nordic countries like Norway as an example. The process, which relies on fossil fuels like coal for 60% of global activity- emits an approximate 22M tones(conservative estimates) -98M tones(fossil fuel-intensive estimates) of carbon dioxide annually, a greenhouse gas attributed to global warming. Furthermore, electricity-backed by energy, as an operational expense for bitcoin miners accounts for 60-80% of operational expenses. 

This whitepaper does the following:
Quantifies Bitcoin mining energy costs and emissions
Makes the case for and models solar LCOE for a Botswana-based microgrid
Evaluates mining profitability under energy & Bitcoin price volatility
Proposes a scalable roadmap for solar-powered compute infrastructure 

Introduction: The Bitcoin Mining Landscape
Bitcoin mining is the computational process that secures the bitcoin network and introduces new $BTC into circulation. It relies on a proof-of-work consensus mechanism in which miners/ nodes compete to solve difficult SHA-256 based cryptography puzzles. The reward for solving each puzzle is currently ~3.125 $BTC plus some transaction fees, the solving also appends a new block to the blockchain-securing it. 

The hardware used to mine bitcoin can range from: application specific integrated circuits(ASICs,specialized hardware optimized for SHA-256 hashing) to CPUs and GPUs. ASICs are the most widely used due to their higher efficiency and higher hash rate output. Hash rate in this context, refers to the rate at which an ASIC or bitcoin mining tool can solve the aforementioned difficult cryptography problems-whose difficulty increases with time. Hash rate is a key (key performance indicator) KPI in determining profitability for Bitcoin miners and is measured in H/s(Hashes per second). Typical ASIC efficiency is also measured in Joules per Terahash(J/TH).

Bitcoin’s issuance follows a fixed, anti-inflationary tokenomics model with a maximum supply of 21M coins. Approximately 19M bitcoins are in circulating supply and it is estimated that bitcoin mining will cease by the year 2140 with rewards for miners decreasing over time. This is because Bitcoin supply is governed by halving economics. This means, the reward for bitcoin mining decreases by half every 210K blocks- approximately every 4 years. As a result, miners depend on higher ASIC efficiencies plus reduced electricity costs to keep their profit margins, making energy costs a central determinant of profitability. 

Current global mining relies on fossil fuels driven energy in religions like: Iran, Kazakhstan, USA and China. While ASIC efficiency continues to improve, mining hardware requires significant energy input and contributes to global e-waste as older machines become obsolete. Notably, companies like Mara Holdings have done much to ensure any excess energy from bitcoin mining can be rerouted to heat homes, as seen with their pilot project-heating around 11K homes in Finland. 

Miners face increasing regulatory pressure related to sustainability, grid impact & congestion and emissions. As block rewards continue to decline and competition for hash rate intensifies, the industry is shifting toward low-cost, stable and scalable renewable energy sources as a strategic necessity. 

The Energy Challenge in Bitcoin Mining
Mining bitcoin carries a range of operational expenses. These include: 
Acquiring mining equipment such as ASICs
Acquiring functional cooling equipment/ water sources to cool equipment as it emits heat
Labor and maintenance costs, non-zero and relatively low compared to energy costs
And most importantly- electricity costs which make up 60-80% of OPEX depending on the miner.

Electricity costs measured in $/kWh, range significantly by geo-location. #Add $/kWh electricity costs for a range of geolocations. Before 2022, most bitcoin mining operations were carried out in China(80%) due to cheap coal-based electricity backed by high government subsidies. However, following regulatory crackdowns on energy-intensive activities and concerns over grid stability and emissions, bitcoin mining was outlawed. Today, miners operate in different countries like: Iran, Kazakhstan, some parts of China and Russia, some U.S.A states and such #Add pie chart on percentage of miners by geo-location #Add pie chart on global energy mix for bitcoin miners. Energy is cheapest in regions like Iran and Kazakhstan which are coal-based and in some states like Texas and Kansas which offer incentives to bitcoin miners who relocate to them. Western countries like Ireland offer higher tariffs(electricity costs) for miners due to a higher residential usage/ demand for electricity. 

Mining operations that rely on grid-connected electricity face additional risks: #Add citations of these events/ catastrophes # Add grid vs off-grid parallel
Grid congestion and curtailment, which reduce miner uptime


Seasonal price volatility, particularly in markets with variable renewable generation


Regulatory exposure, including ESG-linked restrictions and emissions-related compliance


Forced shutoffs during high-demand periods, reducing revenue predictability

$BTC being a speculative asset means profitability for miners also depends on the volatility of the asset’s price. Formula: Profit = (BTCreward * BTCprice) -(Energy cost + Opex). We estimated that profitability of mining bitcoin is sensitive to price swings of the cryptocurrency by XX%- a key metric that must be taken into account when modelling profitability margins for miners.
Recent academic literature on cryptocurrency mining and carbon emissions argues that mining should be incentivized in regions ranked higher in the Environment Performance Index, which takes into account: energy price, energy generation, sources, temperature, legal constraints, human capital, R &D. However, the literature primarily focuses on markets with mature energy infrastructure, overlooking high-irradiance regions where renewable energy generation potential is substantial but underdeveloped due to limited grid or generation capacity.
 Solar energy, particularly in regions with exceptional irradiance such as Botswana presents a strategic opportunity to address energy demands and mandates for sustainable energy use.
Botswana’s Solar as a strategic solution
Botswana is a landlocked, Southern African country with approximately 2.5M people, lying on 581,730 km^2 of land. It boasts about 3200 hours of annual sunlight and a direct normal irradiance(DNI) of about 1900+kWh/m^2/year. DNI measures the amount of solar radiation hitting a surface per area, that is perpendicular to the sun’s rays. An alternative measure is GHI, which measures the total solar radiation hitting a horizontal surface- Botswana’s is around 21MJ/m^2 with peaks of up to 45MJ/m^2 annually. 

This environment, combined with the country’s government’s Vision 2036 to ensure 50% of energy generated is renewable, creates an optimal environment for miners seeking to pivot to a geo-location with cleaner and cheaper energy-given that the cost of solar energy has declined by over 80% this past decade.

Solar energy generation consists of two main approaches: Concentrated solar power(CSP) and photovoltaic systems. Our focus will be on the latter, due to its wide usage in utility scale solar projects- most relevant for bitcoin miners. 

Photovoltaic Systems in Solar Energy
A photovoltaic systems broadly, involve the usage of silicon based panels made up of cells that trap photons from solar radiation which offset electrons in the silicon cells creating a direct current( DC) which is then converted into alternating current(AC)  using inverters and then transported via cables to transmitters which transport the electricity to target areas like: residentials, commercials, utility scale project etc. #Add small diagram : Sunlight -> DC(panels)->AC(inverters)-> Homes, businesses, utility grids

There are three well known types of photovoltaic systems: #For each give brief explanation and then draw a pros and cons side-by-side comparison for all three
Monocrystalline
Polycrystalline
And Thin film

Levelized cost of energy (LCOE) Financial Modelling Methodology
To showcase the quantitative incentive for bitcoin miners to pivot to using Botswana based solar energy, we modelled a levelized cost of energy(LCOE) for a 1.5 MW solar microgrid pilot project, taking into account some assumptions.
Key Assumptions:
Capacity factor:
Discount rate:
Project lifespan: 
CAPEX and OPEX: 
Panel degradation: A degradation annual rate of 0.5% for the solar panels, which does impact solar output
Socio-political and regulatory climate: Stable economic and political conditions and friendly environment for independent power producers

LCOE formula is: LCOE = sum(capex+opex)/sum(energy output at time t)
Our base-case model estimates a $0.05/kWh LCOE for the Botswana-based 1.5MW solar off-grid solar microgrid pilot. To assess sensitivity to capital cost uncertainty, we conduct a Monte Carlo scenario analysis in which CAPEX is modeled as a stochastic variable. Under plausible cost distributions, simulated LCOE outcomes fall within a range of X–Y $/kWh, remaining below the estimated global average electricity cost for Bitcoin miners of approximately $0.075/kWh. Furthermore given the pilot nature of the project, the model assumes a flexible mining load, whereby mining operations dynamically scale in response to available solar generation, avoiding the need for large-scale battery storage. This approach prioritizes capital efficiency over continuous uptime and is appropriate for early-stage demonstration projects #Add LCOE comparisons for our model, Botswana, global averages and others(sadc/ african countries and west etc)

It is also worth mentioning, benchmarkable case studies of African countries where pilots have been constructed to power bitcoin miners. These include:
Kenya
Ethiopia

Botswana offers high solar output, stable peace and economic conditions and an opening for (foreign direct investment) FDI, especially Bitcoin miners seeking ways to drive down OPEX due to electricity in order to remain profitable.

Integration: Solar-powered mining and AI Data Centers
