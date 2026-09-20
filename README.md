<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14213D,100:2F6FA8&height=220&section=header&text=Sujeeth%20Sukumar&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Low-latency%20systems%20%C2%B7%20RTL%20%C2%B7%20Quant%20%C2%B7%20Applied%20ML%20%C2%B7%20Data%20Engineering&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>

<a href="https://sujeeth2003.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-2F6FA8?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/sujeeth73/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:sujeeth@umd.edu"><img src="https://img.shields.io/badge/Email-14213D?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://calendar.app.google/6z1MAE1pPd1BCqET7"><img src="https://img.shields.io/badge/Schedule%2030min-2F6FA8?style=for-the-badge&logo=googlecalendar&logoColor=white"></a>

</div>

<br>

### About

M.S. Data Science candidate at the University of Maryland, College Park. I build things end to end and benchmark every claim I make about them, from a cache-aware C++ matching engine down to a hand-verified RISC-V pipeline.

Five tracks I keep coming back to:

- **Low-latency systems** - lock-free C++, atomics, AVX2, kernel bypass, core pinning
- **RTL / hardware** - SystemVerilog, UVM, formal verification, AXI-Lite, CDC
- **Quant & trading** - regime detection, walk-forward backtesting, from-scratch HMMs
- **Applied ML / GenAI** - transformer architectures from scratch, RAG, agent orchestration
- **Data engineering** - AWS pipelines, PostgreSQL, MongoDB, Redis

Full write-ups with real benchmarks (not vibes) live on my [portfolio](https://sujeeth2003.github.io/Portfolio/).

<br>

### Featured builds

<table>
<tr>
<td width="50%" valign="top">

**Limit Order Book & Matching Engine**
A price-time-priority matching engine taken from a correct-but-slow `std::map` baseline to a cache-aware, branchless, SIMD-accelerated, single-writer design. Six versions, each benchmarked.
`C++` `Atomics` `AVX2` `Lock-free design`

</td>
<td width="50%" valign="top">

**5-Stage Pipelined RISC-V CPU + UVM**
A fetch-decode-execute-memory-writeback pipeline in SystemVerilog with hazard forwarding, a CDC bridge, and a 100+ test UVM regression at zero scoreboard mismatches.
`SystemVerilog` `UVM` `SVA` `SymbiYosys`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Building DeepSeek LLM From Scratch**
A tested PyTorch implementation of the architecture, scaling laws, training loop, and DPO alignment from the DeepSeek LLM paper, verified against the paper's own reference numbers.
`PyTorch` `RoPE / GQA` `SFT + DPO`

</td>
<td width="50%" valign="top">

**AI-Powered Startup Deal Sourcing** ([founder-scout](https://github.com/sujeeth2003/founder-scout))
A LangGraph agent that enriches founder signals via the GitHub API and scores Series A fit with a gradient-boosted classifier (0.81 ROC-AUC).
`LangGraph` `Claude` `Streamlit`

</td>
</tr>
</table>

<br>

### Stack

<p>
<img src="https://skillicons.dev/icons?i=cpp,python,cs,verilog,pytorch,tensorflow,aws,postgres,mongodb,redis,docker,git&theme=dark"/>
</p>

<br>

### Systems, hardware and low-latency

- **Low-latency C++:** [limit-order-book-matching-engine](https://github.com/sujeeth2003/limit-order-book-matching-engine) · [market-data-feed-handler](https://github.com/sujeeth2003/market-data-feed-handler) · [low-overhead-latency-tracer](https://github.com/sujeeth2003/low-overhead-latency-tracer) · [q-timeseries-toolkit](https://github.com/sujeeth2003/q-timeseries-toolkit)
- **RTL and compilers:** [rtl-digital-design](https://github.com/sujeeth2003/rtl-digital-design) · [verilog-compiler](https://github.com/sujeeth2003/verilog-compiler)
- **Distributed and real-time systems:** [google-file-system-simplified](https://github.com/sujeeth2003/google-file-system-simplified) · [tank-control-modbus](https://github.com/sujeeth2003/tank-control-modbus) · [p2p](https://github.com/sujeeth2003/p2p)

<br>

### Machine learning, data and tools

- **Research implementations and RL:** [deepseek-llm-from-scratch](https://github.com/sujeeth2003/deepseek-llm-from-scratch) · [sparse-autoencoder](https://github.com/sujeeth2003/sparse-autoencoder) · [dcgan-mnist](https://github.com/sujeeth2003/dcgan-mnist) · [text-to-image-generator](https://github.com/sujeeth2003/text-to-image-generator) · [rl-puzzle-solver](https://github.com/sujeeth2003/rl-puzzle-solver) · [DC-Motor-control-using-Reinforcement-Learning---DDPG](https://github.com/sujeeth2003/DC-Motor-control-using-Reinforcement-Learning---DDPG)
- **Applied ML:** [time-series-anomaly-detection](https://github.com/sujeeth2003/time-series-anomaly-detection) · [remaining-useful-life-turbofan](https://github.com/sujeeth2003/remaining-useful-life-turbofan) · [anime-recommender](https://github.com/sujeeth2003/anime-recommender) · [founder-scout](https://github.com/sujeeth2003/founder-scout) · [AI_Classifier](https://github.com/sujeeth2003/AI_Classifier) · [Real-vs-AI-Classifier](https://github.com/sujeeth2003/Real-vs-AI-Classifier) · [Fraud-Detection](https://github.com/sujeeth2003/Fraud-Detection) · [Spending-Assistant](https://github.com/sujeeth2003/Spending-Assistant) · [content-analytics-platform](https://github.com/sujeeth2003/content-analytics-platform) · [hotel-site-selection](https://github.com/sujeeth2003/hotel-site-selection)
- **LLM and data engineering:** [multi-agent-analytics](https://github.com/sujeeth2003/multi-agent-analytics) · [dmv-rag-pipeline](https://github.com/sujeeth2003/dmv-rag-pipeline) · [aws-healthcare-pipeline](https://github.com/sujeeth2003/aws-healthcare-pipeline) · [Healthcare-Interoperability-Care-Coordination-Platform](https://github.com/sujeeth2003/Healthcare-Interoperability-Care-Coordination-Platform) · [eureka-research-lineage](https://github.com/sujeeth2003/eureka-research-lineage) · [datalineage](https://github.com/sujeeth2003/datalineage)
- **Quant and trading:** [TradingAlgo](https://github.com/sujeeth2003/TradingAlgo) · [PairTrade](https://github.com/sujeeth2003/PairTrade) · [quant-learning-platform](https://github.com/sujeeth2003/quant-learning-platform)
- **Tools:** [csv-version-control](https://github.com/sujeeth2003/csv-version-control) · [RentTracker](https://github.com/sujeeth2003/RentTracker) · [Email-Read-Receipt](https://github.com/sujeeth2003/Email-Read-Receipt)
- **Sites:** [Portfolio](https://github.com/sujeeth2003/Portfolio) · [data-consulting-portfolio](https://github.com/sujeeth2003/data-consulting-portfolio)

<br>

### GitHub

<div align="center">


<img src="https://github-readme-streak-stats.herokuapp.com/?user=sujeeth2003&theme=tokyonight&hide_border=true&background=0D1117&ring=7DB3E8&fire=7DB3E8&currStreakLabel=7DB3E8"/>

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F6FA8,100:14213D&height=100&section=footer"/>
