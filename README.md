<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto" _msttexthash="34496410" _msthash="232">激光雷达 AI 解决方案</h1><a id="user-content-lidar-ai-solution" class="anchor" aria-label="Permalink：激光雷达 AI 解决方案" href="#lidar-ai-solution" _mstaria-label="618501" _msthash="233"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><font _mstmutation="1" _msttexthash="468187018" _msthash="234">这是针对自动驾驶 3D 激光雷达存储库的高度优化解决方案。
它在加速稀疏卷积/CenterPoint/BEVFusion/OSD/Conversion 方面做得很好。</font><p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution/blob/master/assets/title.png"><img src="https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution/raw/master/assets/title.png" alt="标题" style="max-width: 100%;" _mstalt="63531" _msthash="235"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="14672957" _msthash="236">管道概述</h2><a id="user-content-pipeline-overview" class="anchor" aria-label="永久链接： 管道概述" href="#pipeline-overview" _mstaria-label="695344" _msthash="237"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution/blob/master/assets/pipeline.png"><img src="https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution/raw/master/assets/pipeline.png" alt="管道" style="max-width: 100%;" _mstalt="116142" _msthash="238"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="5300477" _msthash="239">获取</h2><a id="user-content-getstart" class="anchor" aria-label="永久链接：GetStart" href="#getstart" _mstaria-label="365950" _msthash="240"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>$ git clone --recursive https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution
$ cd Lidar_AI_Solution
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ git clone --recursive https://github.com/NVIDIA-AI-IOT/Lidar_AI_Solution
$ cd Lidar_AI_Solution" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li _msttexthash="143500318" _msthash="241">对于每个特定任务，请参阅子文件夹中的自述文件。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="15503228" _msthash="242">3D 稀疏卷积</h2><a id="user-content-3d-sparse-convolution" class="anchor" aria-label="永久链接：3D 稀疏卷积" href="#3d-sparse-convolution" _mstaria-label="812877" _msthash="243"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="159355989" _msthash="244">一个使用 int8/fp16 的 <a href="https://github.com/tianweiy/CenterPoint/blob/master/det3d/models/backbones/scn.py" _istranslated="1">3D 稀疏卷积网络</a>的微型推理引擎。</p>
<ul dir="auto">
<li _msttexthash="122260073" _msthash="245"><strong _istranslated="1">微型引擎：</strong>独立于 TensorRT 的微型 Lidar-Backbone 推理引擎。</li>
<li _msttexthash="48496877" _msthash="246"><strong _istranslated="1">灵活：</strong>从 ONNX 构建执行图。</li>
<li _msttexthash="106427438" _msthash="247"><strong _istranslated="1">易于使用：</strong>简单的界面和 onnx 导出解决方案。</li>
<li _msttexthash="100911785" _msthash="248"><strong _istranslated="1">高保真度：</strong>nuScenes 验证的准确率下降。</li>
<li _msttexthash="31517421" _msthash="249"><strong _istranslated="1">内存不足：</strong>422MB@SCN FP16、426MB@SCN INT8。</li>
<li _msttexthash="77562147" _msthash="250"><strong _istranslated="1">紧凑的：</strong>基于 CUDA 内核，独立于 cutlass。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="201903" _msthash="251">CUDA BEVFusion</h2><a id="user-content-cuda-bevfusion" class="anchor" aria-label="永久链接： CUDA BEVFusion" href="#cuda-bevfusion" _mstaria-label="496028" _msthash="252"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="160955665" _msthash="253">CUDA &amp; TensorRT解决方案用于<a href="https://arxiv.org/abs/2205.13542" rel="nofollow" _istranslated="1">BEVFusion</a>推理，包括：</p>
<ul dir="auto">
<li _msttexthash="239019378" _msthash="254"><strong _istranslated="1">摄像头编码器</strong>：ResNet50 和微调的 BEV 池，使用 TensorRT 和 onnx 导出解决方案。</li>
<li _msttexthash="314076230" _msthash="255"><strong _istranslated="1">激光雷达编码器</strong>：独立于 TensorRT 和 onnx 导出解决方案的微型激光雷达骨干推理。</li>
<li _msttexthash="292351176" _msthash="256"><strong _istranslated="1">功能融合</strong>：带有TensorRT和onnx导出解决方案的相机和激光雷达功能熔融器。</li>
<li _msttexthash="250204747" _msthash="257"><strong _istranslated="1">前/后处理</strong>：间隔预计算、激光雷达体素化、使用 CUDA 内核的特征解码器。</li>
<li _msttexthash="163790068" _msthash="258"><strong _istranslated="1">易于使用</strong>：准备、推理、评估合二为一，可重现 torch Impl 精度。</li>
<li _msttexthash="163632664" _msthash="259"><strong _istranslated="1">PTQ</strong>：<a href="https://github.com/mit-han-lab/bevfusion/tree/main/mmdet3d/ops/spconv" _istranslated="1">mmdet3d/spconv</a> 的量化解决方案，易于理解。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="11594375" _msthash="260">CUDA 中心点</h2><a id="user-content-cuda-centerpoint" class="anchor" aria-label="永久链接： CUDA CenterPoint" href="#cuda-centerpoint" _mstaria-label="600431" _msthash="261"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="167120512" _msthash="262">CUDA &amp; TensorRT解决方案用于<a href="https://arxiv.org/abs/2006.11275" rel="nofollow" _istranslated="1">CenterPoint</a>推理，包括：</p>
<ul dir="auto">
<li _msttexthash="75618439" _msthash="263"><strong _istranslated="1">预处理</strong>：使用 CUDA 内核进行体素化</li>
<li _msttexthash="140304398" _msthash="264"><strong _istranslated="1">编码器</strong>：具有 NV spconv-scn 和 onnx 导出解决方案的 3D 主干。</li>
<li _msttexthash="154339523" _msthash="265"><strong _istranslated="1">颈部和头部</strong>：RPN &amp; CenterHead带有TensorRT和onnx导出解决方案。</li>
<li _msttexthash="60846981" _msthash="266"><strong _istranslated="1">后处理</strong>：解码和带有CUDA内核的NMS</li>
<li _msttexthash="163790068" _msthash="267"><strong _istranslated="1">易于使用</strong>：准备、推理、评估合二为一，可重现 torch Impl 精度。</li>
<li _msttexthash="202873762" _msthash="268"><strong _istranslated="1">QAT</strong>：<a href="https://github.com/traveller59/spconv" _istranslated="1">面向 traveller59/spconv</a> 的量化解决方案，易于理解。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="301509" _msthash="269">CUDA PointPillars</h2><a id="user-content-cuda-pointpillars" class="anchor" aria-label="永久链接： CUDA PointPillars" href="#cuda-pointpillars" _mstaria-label="647634" _msthash="270"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="158565576" _msthash="271">CUDA &amp; TensorRT解决方案用于<a href="https://arxiv.org/abs/1812.05784" rel="nofollow" _istranslated="1">点柱</a>推理，包括：</p>
<ul dir="auto">
<li _msttexthash="114304853" _msthash="272"><strong _istranslated="1">预处理</strong>：体素化和使用 CUDA 内核进行功能扩展</li>
<li _msttexthash="127243675" _msthash="273"><strong _istranslated="1">检测器</strong>：具有 TensorRT 和 onnx 导出解决方案的 2.5D 主干。</li>
<li _msttexthash="83847829" _msthash="274"><strong _istranslated="1">后处理</strong>：解析边界框、类类型和方向</li>
<li _msttexthash="163790068" _msthash="275"><strong _istranslated="1">易于使用</strong>：准备、推理、评估合二为一，可重现 torch Impl 精度。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="219648" _msthash="276">CUDA-V2XFusion</h2><a id="user-content-cuda-v2xfusion" class="anchor" aria-label="永久链接：CUDA-V2XFusion" href="#cuda-v2xfusion" _mstaria-label="520013" _msthash="277"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="79324986" _msthash="278">V2XFusion 的训练和推理解决方案。</p>
<ul dir="auto">
<li _msttexthash="191360442" _msthash="279"><strong _istranslated="1">易于使用</strong>：为训练、量化和 ONNX 导出提供易于重现的解决方案。</li>
<li _msttexthash="446381871" _msthash="280"><strong _istranslated="1">基于 Quantification friendly</strong>:P ointPillars 的主干，具有预归一化功能，可以减少量化误差。</li>
<li _msttexthash="175211205" _msthash="281"><strong _istranslated="1">特性融合</strong>：相机和激光雷达特性熔融器和onnx导出解决方案。</li>
<li _msttexthash="138346975" _msthash="282"><strong _istranslated="1">PTQ</strong>：V2XFusion 的量化解决方案，易于理解。</li>
<li _msttexthash="73736780" _msthash="283"><strong _istranslated="1">稀疏度</strong>：4：2 结构稀疏度支持。</li>
<li _msttexthash="253933654" _msthash="284"><strong _istranslated="1">Deepstream 示例</strong>：在 NVIDIA DeepStream SDK 7.0 中使用 CUDA 、 TensorRT/Triton 进行示例推理。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="60978827" _msthash="285">cuOSD（CUDA 屏幕显示库）</h2><a id="user-content-cuosdcuda-on-screen-display-library" class="anchor" aria-label="永久链接： cuOSD（CUDA 屏幕显示库）" href="#cuosdcuda-on-screen-display-library" _mstaria-label="1532154" _msthash="286"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="63420149" _msthash="287">使用单个 CUDA 内核绘制所有元素。</p>
<ul dir="auto">
<li _msttexthash="113077367" _msthash="288"><strong _istranslated="1">线：</strong>通过插值绘制线（最近或线性）。</li>
<li _msttexthash="151037835" _msthash="289"><strong _istranslated="1">旋转框：</strong>支持使用不同的边框颜色和填充颜色绘制。</li>
<li _msttexthash="128723322" _msthash="290"><strong _istranslated="1">圈：</strong>支持使用不同的边框颜色和填充颜色绘制。</li>
<li _msttexthash="139543222" _msthash="291"><strong _istranslated="1">矩形：</strong>支持使用不同的边框颜色和填充颜色绘制。</li>
<li _msttexthash="301319564" _msthash="292"><strong _istranslated="1">发短信：</strong>支持 <a href="https://github.com/nothings/stb/blob/master/stb_truetype.h" _istranslated="1">stb_truetype</a> 和 <a href="https://pango.gnome.org/" rel="nofollow" _istranslated="1">pango-cairo</a> 后端，允许通过 TTF 或使用 font-family 读取字体。</li>
<li _msttexthash="59171359" _msthash="293"><strong _istranslated="1">箭：</strong>由 3 行组成的箭头组合。</li>
<li _msttexthash="108785326" _msthash="294"><strong _istranslated="1">点：</strong>通过插值（最近或线性）绘制点。</li>
<li _msttexthash="72824245" _msthash="295"><strong _istranslated="1">时钟：</strong>基于文本支持的时间绘图</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="44327712" _msthash="296">cuPCL（CUDA 点云库）</h2><a id="user-content-cupclcuda-point-cloud-library" class="anchor" aria-label="永久链接： cuPCL （CUDA Point Cloud Library）" href="#cupclcuda-point-cloud-library" _mstaria-label="1179399" _msthash="297"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="450355165" _msthash="298">同时提供多个高精度和高性能的 GPU 加速点云操作：cuICP、cuFilter、cuSegmentation、cuOctree、cuCluster、cuNDT、Voxelization（传入）。</p>
<ul dir="auto">
<li _msttexthash="213954637" _msthash="299"><strong _istranslated="1">cuICP：</strong>CUDA 加速迭代对应点顶点云（point-to-point）注册实现。</li>
<li _msttexthash="107944070" _msthash="300"><strong _istranslated="1">cuFilter 中：</strong>支持 CUDA 加速功能：PassThrough 和 VoxelGrid。</li>
<li _msttexthash="205333297" _msthash="301"><strong _istranslated="1">cuSegmentation：</strong>支持 CUDA 加速功能：带有平面模型的 RandomSampleConsensus。</li>
<li _msttexthash="117352768" _msthash="302"><strong _istranslated="1">cuOctree 的：</strong>支持 CUDA 加速功能：Approximate Nearest Search 和 Radius Search。</li>
<li _msttexthash="254899411" _msthash="303"><strong _istranslated="1">cuCluster ：</strong>支持 CUDA 加速功能：根据点之间的距离进行聚类。</li>
<li _msttexthash="176887880" _msthash="304"><strong _istranslated="1">cuNDT：</strong>CUDA 加速了点云数据的 3D 正态分布变换配准实现。</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="48050925" _msthash="305">YUVToRGB（CUDA 转换）</h2><a id="user-content-yuvtorgbcuda-conversion" class="anchor" aria-label="永久链接：YUVToRGB（CUDA 转换）" href="#yuvtorgbcuda-conversion" _mstaria-label="939666" _msthash="306"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="221696072" _msthash="307">YUV 到 RGB 的转换。将 Resize/Padding/Conversion/Normalization 合并到一个内核函数中。</p>
<ul dir="auto">
<li><strong _msttexthash="95345341" _msthash="308">大多数时候，它可以与 OpenCV 进行位对齐。</strong>
<ul dir="auto">
<li _msttexthash="130860301" _msthash="309">当缩放因子是有理数时，它将给出精确的结果。</li>
<li _msttexthash="125457098" _msthash="310">当步幅可以除以 4 时，通常会获得更好的表现。</li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="36461685" _msthash="311">支持的输入格式：</font><ul dir="auto">
<li><strong _msttexthash="16985345" _msthash="312">NV12块式线性</strong></li>
<li><strong _msttexthash="260039" _msthash="313">NV12PitchLinear</strong></li>
<li><strong _msttexthash="288145" _msthash="314">YUV422Packed_YUYV</strong></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="35458670" _msthash="315">支持的插值方法：</font><ul dir="auto">
<li><strong _msttexthash="6228456" _msthash="316">最近</strong></li>
<li><strong _msttexthash="1952132" _msthash="317">双</strong></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="48428302" _msthash="318">支持的输出数据类型：</font><ul dir="auto">
<li><strong _msttexthash="7572929" _msthash="319">乌因特8</strong></li>
<li><strong _msttexthash="8602438" _msthash="320">浮点数32</strong></li>
<li><strong _msttexthash="4762667" _msthash="321">浮动16</strong></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="35953229" _msthash="322">支持的输出布局：</font><ul dir="auto">
<li><strong _msttexthash="124384" _msthash="323">CHW_RGB/BGR</strong></li>
<li><strong _msttexthash="124059" _msthash="324">HWC_RGB/BGR</strong></li>
<li><strong _msttexthash="39578058" _msthash="325">CHW16/32/4/RGB/BGR 用于 DLA 输入</strong></li>
</ul>
</li>
<li><font _mstmutation="1" _msttexthash="26202202" _msthash="326">支持的功能：</font><ul dir="auto">
<li><strong _msttexthash="5962801" _msthash="327">调整</strong></li>
<li><strong _msttexthash="4223505" _msthash="328">填充</strong></li>
<li><strong _msttexthash="5987124" _msthash="329">转换</strong></li>
<li><strong _msttexthash="7498751" _msthash="330">正常化</strong></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6995430" _msthash="331">谢谢</h2><a id="user-content-thanks" class="anchor" aria-label="永久链接： 谢谢" href="#thanks" _mstaria-label="304265" _msthash="332"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="128244493" _msthash="333">这个项目利用了许多很棒的开源库，包括：</p>
<ul dir="auto">
<li _msttexthash="21930662" _msthash="334"><a href="https://github.com/nothings/stb" _istranslated="1">stb_image</a> PNG 和 JPEG 支持</li>
<li _msttexthash="50309064" _msthash="335"><a href="https://github.com/pybind/pybind11" _istranslated="1">pybind11</a> 实现无缝 C++ / Python 互操作</li>
<li _msttexthash="64878008" _msthash="336">和其他人！请参阅 dependencies 文件夹。</li>
</ul>
<p dir="auto" _msttexthash="82108104" _msthash="337">非常感谢这些出色项目的作者！</p>
</article></div>
