# <b>Portfolio</b>
## <b><i>Updates</i></b>
Dec 15, 2024:
 RAPGen work accepted at <b>ICSE'25</b> SEIP Track! "<b>RAPGen: An Approach for Detecting and Fixing Code Inefficiencies in Zero-Shot</b>"

## <b><i>Patents and Publications</i></b>
---
<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, and Neel Sundaresan. 2023. RAPGen: An Approach for Detecting and Fixing Code Inefficiencies in Zero-Shot. Filed Jan 23rd., 2023. Patent Pending.

<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, Colin B. Clement, Neel Sundaresan and Chen Wu. 2022. <a href="https://dl.acm.org/doi/abs/10.1145/3540250.3549096">DeepDev-PERF: A Deep Learning-Based Approach For Improving Software Performance</a>. In <i>Proceedings of the 30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE'2022)</i>.

Roshanak Zilouchian Moghaddam<sup>\*</sup>, <u>Spandan Garg</u><sup>\*</sup>, Colin B. Clement<sup>\*</sup>, Yevhen Mohylevskyy and Neel Sundaresan. 2022. <a href="https://dl.acm.org/doi/abs/10.1145/3534678.3549983">Generating Examples from CLI Usage: Can Transformers Help?</a>. In <i>Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD'2022)</i>.

<u>Spandan Garg</u>, Paul Harrington, Roshanak Zilouchian Moghaddam, Chen Wu and Neel Sundaresan. 2021. System and Method For Identifying Performance Bottlenecks. Filed November 12th., 2021. Patent Pending.

<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, Chen Wu, and Neel Sundaresan. 2021. <a href="https://dl.acm.org/doi/10.1145/3460946.3464318">PerfLens: A Data-driven Performance Bug Detection and Fix Platform</a>. In <i>Proceedings of the 10th ACM SIGPLAN International Workshop on the State of the Art in Program Analysis (SOAP’2021)</i>.

<u>Spandan Garg</u>, Paul Harrington, Roshanak Zilouchian Moghaddam, and Chen Wu. 2021. Performance Bug Detection and Code Recommendation. Filed March 10th., 2021. Patent Pending.

<u>Spandan Garg</u>, Roshanak Zilouchian Moghaddam, Yevhen Mohylevskyy and Jason Shaver. 2019. Command-line Script Generation with Relevance Search. U.S. Patent Application 20210342357, Filed May 1st., 2020. Patent Pending.

<u>Spandan Garg</u><sup>\*</sup>, Roshanak Zilouchian Moghaddam<sup>\*</sup>, Jason Shaver and Neel Sundaresan. 2019. Machine Generated Examples of Command-line Commands with Parameter Values. U.S. Patent Application 20210342654, Filed April 29th., 2020. Patent Pending.

<sub>\* Equal Contribution</sub>
<br>


## <i><b>AI For Software Engineering</b></i>

---

### <b>DeepPERF: A Deep Learning-Based Approach For Improving Software Performance (<a href="https://dl.acm.org/doi/abs/10.1145/3540250.3549096">Paper</a>)</b>

<div style="text-align: justify">Improving software performance is an important yet challenging part of the software development cycle. Today, the majority of performance inefficiencies are identified and patched by performance experts. Recent advancements in deep learning approaches and the wide-spread availability of open source data creates a great opportunity to automate the identification and patching of performance problems. In this paper, we present DeepPERF, a transformer-based approach to suggest performance improvements for C# applications. We pretrain DeepPERF on English and Source code corpora and followed by finetuning for the task of generating performance improvement patches for C# applications. Our evaluation shows that our model can generate the same performance improvement suggestion as the developer fix in more than 53% of the cases, getting roughly 34% of them verbatim in our expert-verified dataset of performance changes made by real C# developers. Additionally, we evaluate DeepPERF on 50 open source C# repositories on GitHub using both benchmark and unit tests and find that our model is able to suggest valid performance improvements that can improve both CPU usage and Memory allocations. So far we've submitted 19 pull-requests with 28 different performance optimizations and 9 of these PRs have been approved by the project owners. </div>

<center><img src="images/DeepPERF.png"/></center>

---

### <b>PerfLens: A Data-Driven Performance Bug Detection and Fix Platform (<a href="https://dl.acm.org/doi/10.1145/3460946.3464318">Paper</a>)</b>

<div style="text-align: justify">PerfLens is a data-driven approach to software performance improvement in C#. We first compile a large dataset of hundreds of performance improvements made in open source projects. We then leverage this data to build a tool called PerfLens for performance improvement recommendations via code search. PerfLens indexes the performance improvements, takes a codebase as an input and searches a pool of performance improvements for similar code. We show that when our system is further augmented with profiler data information our recommendations are more accurate. Our experiments show that PerfLens can suggest performance improvements with 90% accuracy when profiler data is available and 55% accuracy when it analyzes source code only.</div>

<center><img src="images/PerfLensSuggestions.PNG"/></center>

---
### <b>Optimization Insights</b> (Ongoing)

<div style="text-align: justify">
<b>Bottleneck detection in ETW Traces</b>: Developed a bottleneck detection approach for .NET applications by identifying
patterns of function calls corresponding to known performance issues among call-stacks in profiler traces. This has been integrated into the Azure Application Insights Profiler and was also demoed at VSLive! Conference (2021) keynote. <a href="https://github.com/microsoft/optimization-insights">Sign up</a> for our private preview!</div>

---
### <b>Generating Examples from CLI Usage: Can Transformers Help? (<a href="https://dl.acm.org/doi/abs/10.1145/3534678.3549983">Paper</a>, <a href="https://uspto.report/patent/app/20210342654">Patent</a>)</b>

<div style="text-align: justify">Continuous evolution in modern software often causes documentation, tutorials, and examples to be out of sync with changing interfaces and frameworks. Relying on outdated documentation and examples can lead programs to fail or be less efficient or even less secure. In response, programmers need to regularly turn to other resources on the web such as StackOverflow for examples to guide them in writing software. We recognize that this inconvenient, error-prone, and expensive process can be improved by using machine learning applied to software usage data. In this work, we present our practical system which uses machine learning on large-scale telemetry data and documentation corpora, generating appropriate and complex examples that can be used to improve documentation. We discuss both feature-based and transformer-based machine learning approaches and demonstrate that our system achieves 100% coverage for the used functionalities in the product, providing up-to-date examples upon every release and reduces the numbers of PRs submitted by software owners writing and editing documentation by >68%. We also share valuable lessons learnt during the 3 years that our production quality system has been deployed for Azure Cloud Command Line Interface (Azure CLI).</div>
<br>
<center><img src="images/Aladdin.PNG"></center>
<br>


---
### <b>Genie: Human Language to Azure CLI Snippets (<a href="https://uspto.report/patent/app/20210342357">Patent</a>)</b>

<div style="text-align: justify"> Genie is a AI tool that translates human language queries to snippets of Azure CLI commands. We first create an index of common snippets by splitting the telemetry into usage sessions and mining frequent sequences of successful commands. Given a human language query, we use FastText word embeddings and Azure documentation to resolve out of vocab (OoV) words, fix typos, perform query expansion, etc. We then leverage the hierarchical nature of CLI modules to score the query against the different modules, command groups and commands in CLI and produce a ranked list of snippets based on the aggregated scores of their component commands. This approach was demoed at the Microsoft Azure+AI Conference (2019).
</div>

<center><img src="images/Genie.PNG"/></center>

VS Code Extension Demo:
<center><img src="images/GenieDemo.gif"/></center>

<br><br>
## <b><i>Hobbies & Side-Projects</i></b>
---
### <b>Voxels Game Engine</b>
[![View on GitHub](https://img.shields.io/badge/GitHub-Source_Code-blue?logo=GitHub)](https://github.com/glGarg/Voxels)
[![View Demo](https://img.shields.io/badge/YouTube-Watch_Demo-grey?logo=youtube&labelColor=FF0000)](https://www.youtube.com/watch?v=Dg3rni3DGqM&list=PLWKNAuzDDovlArNzZ5ce_5a7hCr9DGIqS&index=1&ab_channel=SpandanGarg)

<div style="text-align: justify">A game engine I wrote from scratch using C++ and OpenGL.</div>
<br>
<center><img src="images/Voxels.jpg"/></center>
<br>

---
### <b>4Kb Demo Scenes</b>

[![View on GitHub](https://img.shields.io/badge/GitHub-Source_Code-blue?logo=GitHub)](https://github.com/glGarg/4Kb-Demo-Scenes)
[![View Demo](https://img.shields.io/badge/YouTube-Watch_Demo-grey?logo=youtube&labelColor=FF0000)](https://www.youtube.com/watch?v=w7AOLJrzUCw&list=PLWKNAuzDDovlArNzZ5ce_5a7hCr9DGIqS&index=3)

<div style="text-align: justify"><a href="https://developer.nvidia.com/gpugems/gpugems2/part-i-geometric-complexity/chapter-8-pixel-displacement-mapping-distance-functions">Ray-Marching</a> demos I wrote using C++, OpenGL and GLSL.</div>
<br>
<center><img src="images/4Kb.PNG"/></center>
<br>

---
### <b>Overworld RPG Game Engine</b>

[![View on GitHub](https://img.shields.io/badge/GitHub-Source_Code-blue?logo=GitHub)](https://github.com/glGarg/OverworldRPG)

<div style="text-align: justify">A 2D game engine I wrote using javascript and HTML.</div>
<br>
<center><img src="images/prototype.gif"/></center>
<br>

---
### <b>Sketching</b>

[![View My Artwork](https://img.shields.io/badge/Tumblr-View_Artwork-grey?logo=tumblr&labelColor=blue)](https://allthestarsinmybackyard.tumblr.com)

<div style="text-align: justify">Outside of work, I also enjoy art, particularly sketching. Below are a few of my sketches that I felt turned out well. Visit my <a href="https://allthestarsinmybackyard.tumblr.com">Tumblr</a> to view my other works!</div>
<br>
<center><img src="images/Sketches.PNG"/></center>
<br>

---
<center>© 2023 Spandan Garg.</center>
