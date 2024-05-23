# From Text to Pixel: Advancing Long-Context Understanding in MLLMs

<p align="center">
   🔥 <a href="?" target="_blank">Project Page</a> 📃 <a href="?" target="_blank">Paper</a><br>
</p>

We introduce SEEKER, a multimodal large language model designed to tackle this issue. SEEKER aims to optimize the compact encoding of long text by compressing the text sequence into the visual pixel space via images, enabling the model to handle long text within a fixed token-length budget efficiently.</a>.

## Overview
Left: Performance plot on First-Sentence-Retrieval task revealing compact nature of image tokens in representing long content. Right: Radar chart demonstrating the superior performance of the SEEKER (ours) model across both short and long-context multimodal tasks.
<p align="center">
<img src="assets/teaser.png" width="1024px"></img>
</p>

Our SEEKER surpass OCR-based model on long multimodal context tasks: 1) process multiple text-rich images naturally. 2) more compact token and fit easily in fix-context length LLM.

<p align="center">
<img src="assets/longcontext_mllm.png" width="1024px"></img>
</p>

Main quantitative results - Long Image and Text Context.
<p align="center">
<img src="assets/longtask_table.png" width="1024px"></img>
</p>

Main quantitative results - Short Image and Text Context.
<p align="center">
<img src="assets/shorttask_table.png" width="1024px"></img>
</p>

Compact Context Length and Inference Efficiency
<p align="center">
<img src="assets/analysis.png" width="1024px"></img>
</p>
