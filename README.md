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

