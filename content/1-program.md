---
title: Program
nav: Program

---

## Agenda

<table class="table table-bordered table-striped mt-3">
  <thead class="table-dark">
    <tr>
      <th style="vertical-align:middle">Time</th>
      <th style="vertical-align:middle">Topic</th>
      <th style="vertical-align:middle">Speaker & Institution</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">14:00 – 14:45</td>
      <td style="vertical-align:middle">The Aversion to Systematization in Systems Research</td>
      <td style="vertical-align:middle">Prof. Timothy Roscoe<br><small class="text-muted">ETH Zürich</small></td>
    </tr>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">14:45 – 15:05</td>
      <td style="vertical-align:middle">From Paper to Community and Deployment: Lessons from Building RL Infrastructure</td>
      <td style="vertical-align:middle">Guangming Sheng<br><small class="text-muted">University of Hongkong</small></td>
    </tr>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">15:05 – 15:45</td>
      <td style="vertical-align:middle">AI Systems Research in a Vibe Coding Era</td>
      <td style="vertical-align:middle">Prof. Kenneth P. Birman<br><small class="text-muted">Cornell University</small></td>
    </tr>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">15:45 – 16:05</td>
      <td style="vertical-align:middle"><em>Coffee Break</em></td>
      <td></td>
    </tr>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">16:05 – 16:45</td>
      <td style="vertical-align:middle">Towards A Learning-Directed Operating System</td>
      <td style="vertical-align:middle">Prof. Aditya Akella<br><small class="text-muted">University of Texas at Austin</small></td>
    </tr>
    <tr>
      <td style="vertical-align:middle; white-space:nowrap">16:45 – 17:30</td>
      <td style="vertical-align:middle">How Will AI Systems Do Systems Research?</td>
      <td style="vertical-align:middle">Ant Rowstron<br><small class="text-muted">CTO at ARIA</small></td>
    </tr>
  </tbody>
</table>

---

## Speakers
<!-- speaker1 -->
<div class="row mt-4 mb-4">
  <div class="col-md-3 d-flex align-items-center justify-content-center">
    <img src="{{ '/images/speaker-timothy-roscoe.jpg' | relative_url }}" alt="Timothy Roscoe" class="rounded-circle img-fluid mb-2" style="width:140px;height:140px;object-fit:cover;">
  </div>
  <div class="col-md-9">
    <h4>Prof. Timothy Roscoe</h4>
    <p><strong> - Full Professor at the Department of Computer Science, ETH Zürich</strong></p>
    <p><em>Talk: The Aversion to Systematization in Systems Research</em></p>
  </div>
</div>



<hr>


<!-- speaker2 -->
<div class="row mt-4 mb-4">
  <div class="col-md-3 d-flex align-items-center justify-content-center">
    <img src="{{ '/images/guangming.jpg' | relative_url }}" alt="Sheng Guangming" class="rounded-circle img-fluid mb-2" style="width:140px;height:140px;object-fit:cover;">
  </div>
  <div class="col-md-9">
    <h4>Guangming Sheng</h4>
    <p><strong> - University of Hong Kong</strong></p>
    <p><em>Talk: From Paper to Community and Deployment: Lessons from Building RL Infrastructure</em></p>
  </div>
</div>



<hr>


<!-- speaker3 -->
<div class="row mt-4 mb-4">
  <div class="col-md-3 d-flex align-items-center justify-content-center">
    <img src="{{ '/images/Ken.jpg' | relative_url }}" alt="Aditya Akella" class="rounded-circle img-fluid mb-2" style="width:140px;height:140px;object-fit:cover;">
  </div>
  <div class="col-md-9">
    <h4>Prof. Kenneth P. Birman</h4>
    <p><strong> - N. Rama Rao Professor of Computer Science, Cornell University</strong></p>
    <p><em>Talk: AI Systems Research in a Vibe Coding Era</em></p>
  </div>
</div>


<hr>


<!-- speaker4 -->
<div class="row mt-4 mb-4">
  <div class="col-md-3 d-flex align-items-center justify-content-center">
    <img src="{{ '/images/speaker-Aditya.jpg' | relative_url }}" alt="Aditya Akella" class="rounded-circle img-fluid mb-2" style="width:140px;height:140px;object-fit:cover;">
  </div>
  <div class="col-md-9">
    <h4>Prof. Aditya Akella</h4>
    <p><strong> - Professor & Regents Chair, University of Texas at Austin<br>
                - ACM Fellow</strong></p>
    <p><em>Talk: Towards A Learning-Directed Operating System</em></p>
  </div>
</div>


<hr>


<!-- speaker5 -->
<div class="row mt-4 mb-4">
  <div class="col-md-3 d-flex align-items-center justify-content-center">
    <img src="{{ '/images/speaker-ant-rowstron.jpg' | relative_url }}" alt="Ant Rowstron" class="rounded-circle img-fluid mb-2" style="width:140px;height:140px;object-fit:cover;">
  </div>
  <div class="col-md-9">
    <h4>Ant Rowstron</h4>
    <p><strong> - CTO of ARIA Research<br>
                - Ex-Distinguished Engineer at Microsoft Research</strong></p>
    <p><em>Talk: How Will AI Systems Do Systems Research?</em></p>
  </div>
</div>


<hr>


---


## Talk Abstracts

### The Aversion to Systematization in Systems Research

*Prof. Timothy Roscoe*

Frequent concerns in systems research include rising submission volumes, heavy reviewer workloads, overly broad conference scopes, and a growing gap from real-world practice. While discussions often focus on improving peer review, a deeper issue is the field’s resistance to systematizing knowledge. Few papers provide reusable principles, and those that do are rarely cited. This leads to repeated ideas and limited impact. Addressing this requires understanding why systematization is resisted, what benefits it could bring, and how we might begin to build more structured, generalizable knowledge—particularly in areas like operating system design.


---


### From Paper to Community and Deployment: Lessons from Building RL Infrastructure

*Guangming Sheng*

Large-scale RL post-training is emerging as a first-class systems workload, combining distributed LLM training, high-throughput generation, reward and verifier execution, data movement, and evolving control flow. This talk examines RL infrastructure evolution through HybridFlow, its open-source implementation verl, DAPO, and Laminar. HybridFlow/verl enables flexible RL dataflow representation and efficient distributed execution, while verl extends to reproducible recipes, configurable pipelines, and system–algorithm co-design (DAPO). Laminar studies asynchronous RL execution, where system decisions affect policy staleness, convergence, and reward. These cases highlight open challenges in rollout optimization, reproducibility, and validating system optimizations that impact learning at scale.


---


### AI Systems Research in a Vibe Coding Era

*Prof. Kenneth P. Birman*

Pervasive adoption of coding agents like Claude Opus and OpenAI Codex is rapidly transforming software development, especially for teams building applications on complex APIs—work that previously required substantial expertise. This talk examines how this shift changes the questions systems researchers should ask, and how evolving coding practices impact the scope of experimental research. While these trends boost productivity, they risk locking us into ideas current AIs can learn from, leaving them unprepared for fundamentally new paradigms. Using RDMA as an example, I highlight what such shifts demand from researchers and what they warn about future emerging technologies.


---


### Towards A Learning-Directed Operating System

*Prof. Aditya Akella*

Modern applications run on increasingly heterogeneous and dynamic platforms, yet current operating systems still rely on rigid, locally optimized, and weakly coordinated policies that adapt slowly, often making performance and tail latency limited by poor policy choices rather than hardware constraints. To address this, LDOS (Learning-Directed Operating System) treats policy design as a data-driven, system-wide optimization problem, providing rich observability, fast feedback, and coordinated, trustworthy ML-based control, unlike Linux where policies and mechanisms are tightly coupled. The talk introduces three core components: UNUM for system-wide state embeddings and coordinated decisions, Darwin for making ML-driven policies practical by balancing optimality, generalization, and overhead, and C3 for enforcing system-wide and tail-latency guarantees under adaptive control, and concludes with LDOS’s clean-slate design principles and current progress.


---


### How Will AI Systems Do Systems Research?

*Ant Rowstron*

AI is increasingly capable of writing code, running experiments, and reading papers. What happens when AI systems start doing systems research? This talk explores what that means for the field, for researchers, and for the kinds of problems we choose to work on.