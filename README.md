# Forecasting_EV_ICEV
Forecasting the Future of EV and ICE Vehicle Markets and Their Associated CO₂ Emissions in Delhi Using a Deep Learning &amp; Statistical Approach.

India's road transport sector contributes to nearly 90% of the country’s transportation-related CO₂ emissions, making it a critical area for decarbonization to meet national climate goals. A recent meta-analysis of eight leading energy and emissions models for India’s road transport sector revealed significant discrepancies in assumptions, particularly in Business-As-Usual (BAU) scenarios. Still, there is broad agreement that vehicle activity and emissions will grow rapidly under current trends. High Ambition and Aggressive Policy scenarios suggest that significant CO₂ reductions—up to 45–50% cumulatively by 2050—are possible through electrification, modal shifts, and grid decarbonization. COVID-19 had a notable short-term impact, altering vehicle sales and travel patterns, thereby shifting energy and emissions trajectories.

In line with these national insights, my thesis project focuses on forecasting vehicle registrations and associated CO₂ emissions in Delhi using a dataset sourced from the Ministry of Road Transport and Highways (MoRTH). I developed a 20-year monthly dataset, initially excluding COVID-19 years for accuracy. After early deep learning attempts (like LSTM) yielded limited results due to sparse data, I applied classical statistical models such as ARIMA, VARMAX, and SARIMAX, which performed significantly better.

Vehicles were categorized by type—Two-wheelers, Three-wheelers, Four-wheelers, Buses, HGVs, LGVs, and Passenger Vehicles—and CO₂ emissions were estimated using standard emission factors. I also modeled Electric Vehicle (EV) growth and compared it against Internal Combustion Engine (ICE) vehicle trends to project future emissions. A key insight from my research is that while EV adoption is vital, true decarbonization can only be achieved if India's power grid shifts significantly toward green energy sources. This holistic approach is essential for sustainable transport planning and meaningful emissions reduction.
