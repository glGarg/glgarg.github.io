## Patents and Pulications
---
<u>Spandan Garg</u>, Paul Harrington, Roshanak Zilouchian Moghaddam, Chen Wu and Neel Sundaresan. 2021. Pattern-based Bottleneck Detection and Patch Generation (Patent filed).

<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, Chen Wu, and Neel Sundaresan. 2021. PerfLens: A Data-driven Performance Bug Detection and Fix Platform. In <i>Proceedings of the 10th ACM SIGPLAN International Workshop on the State of the Art in Program Analysis (SOAP’2021)</i>.

<u>Spandan Garg</u>, Paul Harrington, Roshanak Zilouchian Moghaddam, and Chen Wu. 2021. Performance Bug Detection and Code Recommendation (Patent filed).

<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, Yevhen Mohylevskyy and Jason Shaver. 2019. Command-line Script Generation with Relevance Search (Patent filed).

Roshanak Zilouchian Moghaddam, <u>Spandan Garg</u>, Jason Shaver and Neel Sundaresan. 2019. Machine Generated Examples of Command-line Commands with Parameter Values (Patent filed).
<br></br>


## AI For Software Engineering
---
### Performance Bottleneck Detection and Patch Generation using Transformers (Ongoing)

<div style="text-align: justify">
<b>Bottleneck detection in ETW Traces</b>: Developed a bottleneck detection approach for .NET applications by identifying
patterns of function calls corresponding to known performance issues among call-stacks in profiler traces, which has been integrated into the Azure Application Insights Profiler and was demoed at VSLive! Conference (2021).
<br></br>
<b>Patch Generation</b>: Finetuned Facebook's BART model to generate patches to fix performance issues. Further details cannot be revealed due to NDA.</div>
<br>

---

### PerfLens: A Data-Driven Performance Bug Detection and Fix Platform

<div style="text-align: justify">PerfLens is a data-driven approach to software performance improvement in C#. We first compile a large dataset of hundreds of performance improvements made in open source
projects. We then leverage this data to build a tool called PerfLens for performance improvement recommendations via code search. PerfLens indexes the performance improvements, takes a codebase as an input and searches a pool of performance improvements for similar code. We show that
when our system is further augmented with profiler data information our recommendations are more accurate. Our
experiments show that PerfLens can suggest performance improvements with 90% accuracy when profiler data is available and 55% accuracy when it analyzes source code only.</div>

<center><img src="images/PerfLensSuggestions.PNG"/></center>

---
### Genie: Human Language to Azure CLI Snippets

<div style="text-align: justify"> Genie translates human language queries to snippets of Azure CLI commands. We first create an index of common snippets by mining snippets of successful commands from CLI's usage telemetry. Given a human language query, we use FastText word embeddings and Azure documentation to resolve out of vocab (OoV) words, fix typos, perform query expansion, etc. We leverage the hierarchical nature of CLI modules to score the query against the different modules, command groups and commands in CLI and then aggregating the scores to produce a ranked list of snippets.
</div>

<center><img src="images/Genie.PNG"/></center>

---
### Aladdin: Artificial Example Generation for Azure CLI

<div style="text-align: justify">Aladdin is an AI framework to automate the creation of usage examples for reference docs of command line
tools like Azure-CLI, Powershell and Azure SDKs. We leverage the product telemetry, documentation and a Random Forest model to generate examples for the most popular commands and parameter sets. For Azure-CLI, Aladdin is able to provide coverage for 99% of the commands as opposed to the current in-product coverage of 46% provided by human written examples.</div>
<br>
<center><img src="images/Aladdin.PNG"></center>
<br>


## Hobbies & Side-Projects
---
### Voxels Game Engine
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/glGarg/Voxels)

<div style="text-align: justify">A game engine I wrote from scratch using C++ and OpenGL.</div>
<br>
<center><img src="images/Voxels.jpg"/></center>
<br>

---
### 4Kb Demo Scenes

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/glGarg/4Kb-Demo-Scenes)

<div style="text-align: justify">Ray-Marching demos I wrote using C++, GLSL and OpenGL.</div>
<br>
<center><img src="images/4Kb.PNG"/></center>
<br>

---
### Straights Card Game

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/glGarg/Straights)

<div style="text-align: justify">A simple card game I wrote in C++ using gtkmm for the GUI and GStreamer for the background music.</div>
<br>
<center><img src="images/Straights.png"/></center>
<br>

---
### Sketching

[![View My Artwork](https://img.shields.io/badge/Tumblr-View_My_Artwork-grey?logo=tumblr&labelColor=blue)](https://spandangarg.tumblr.com)

<div style="text-align: justify">Outside of work, I also have a great passion for art, particularly sketching. Below are a few of my sketches that I felt turned out well. Please visit my tumblr to view my other works :)</div>
<br>
<center><img src="images/Sketches.PNG"/></center>
<br>

---
<center>© 2021 Spandan Garg. Powered by Jekyll and the Minimal Theme.</center>
