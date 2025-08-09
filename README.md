<p align="center">
  <img src="READMEimages/SpatialGeo.png" width="15%"/>
</p>

# SpatialGeo: Boosting Spatial Reasoning in Multimodal LLMs via Geometry-Semantics Fusion
______________________________________________________________________

***SpatialGeo*** enhances ***spatial reasoning*** in MLLMs based on the novel vision encoder generating spatial-aware visual embedding.

The overall architecture of ***SpatialGeo*** is shown in the figure below, which is composed of three major modules: 1) ***CLIP module*** with the CLIP encoder and its adapter to extract instance-level semantic features; 2) ***MoGe module*** with the MoGe encoder and its adapter to embed a mixture of geometry and semantic features; 3) ***LLM module*** with interleaved geometry and semantic embeddings together with text tokens as inputs to generate question answering.

<p align="center">
  <img src="READMEimages/structure.png" width="80%"/>
</p>
<br>  <!-- 增加一个空行 -->

______________________________________________________________________

## Code
You can obtain detailed information about the source code and model on the following website.

(https://github.com/Ricky-PLUS/SpatialGeo)
______________________________________________________________________

## Spatial VQA Datasets
We compare SpatialGeo with SOTA MLLMs, i.e., ***LLaVA-v1.5-7B*** [1], ***GPT-4.1*** [2], ***SpatialRGPT*** [3] on spatial VQA datasets, including ***SpatialRGPT-Bench*** [3] and ***SpatialScore*** [4]

______________________________________________________________________

### Examples From SpatialRGPT-Bench
We select different types of questions from ***SpatialRGPT-Bench*** for demonstration.
<p align="center">
  <strong>Fig.1 Vertical Distance</strong><br>
  <img src="READMEimages/rgpt2.png" width="80%"/>
</p>   

<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.2 Width Data</strong><br>
  <img src="READMEimages/rgpt3.png" width="80%"/>
</p>    

<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.3 Height Data</strong><br>
  <img src="READMEimages/rgpt4.png" width="80%"/>
</p>
<br>  <!-- 增加一个空行 -->

______________________________________________________________________

### Examples From SpatialScore
We select different types of questions from ***SpatialScore*** for presentation.
<p align="center">
  <strong>Fig.4 Boundingboxs Distance</strong><br>
  <img src="READMEimages/spatialscoredepthanddistance2.png" width="80%"/>
</p>   

<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.5 Objects Distance</strong><br>
  <img src="READMEimages/spatialscoredepthanddistance1.png" width="80%"/>
</p>    

<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.6 Objects Distance</strong><br>
  <img src="READMEimages/spatialscoredepth.png" width="80%"/>
</p>    

<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.7 Object Localization</strong><br>
  <img src="READMEimages/spatialscoreObjectLocalization.png" width="80%"/>
</p>
<br>  <!-- 增加一个空行 -->

<p align="center">
  <strong>Fig.8 Camera and Image Transformation</strong><br>
  <img src="READMEimages/spatialscoreCameraandImageTransformation.png" width="80%"/>
</p>

<br>  <!-- 增加一个空行 -->
______________________________________________________________________
