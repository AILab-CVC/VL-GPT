# VL-GPT

VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation






<div align="center">
    <span class="author-block">
    <a href="https://scholar.google.com/citations?user=YfHg5lQAAAAJ&hl=en" target="_blank">Jinguo Zhu</a><sup>1*</sup>,
    </span>
    <span class="author-block">
    <a href="https://dingxiaohan.xyz/" target="_blank">Xiaohan Ding</a><sup>2*</sup>,
    </span>
    <span class="author-block">
    </span>
    <a href="https://geyixiao.com/" target="_blank">Yixiao Ge</a><sup>2</sup>,
    </span>
     <span class="author-block">
    </span>
    <a href="https://geyuying.github.io/" target="_blank">Yuying Ge</a><sup>2</sup>,
    </span>
    </br>
    <span class="author-block">
    <a target="_blank">Sijie Zhao</a><sup>2</sup>,
    </span>
    <span class="author-block">
    <a href="https://hszhao.github.io/" target="_blank">Hengshuang Zhao</a><sup>3</sup>,
    </span>
    <span class="author-block">
    <a href="https://gr.xjtu.edu.cn/web/xhw" target="_blank">Xiaohua Wang</a><sup>1</sup>,
    </span>
    <span class="author-block">
    <a href="https://scholar.google.com/citations?user=4oXBp9UAAAAJ&hl=en&oi=ao" target="_blank">Ying Shan</a><sup>2</sup>
    </span>

</div>



<div align="center">
    <sup>1</sup> <a  target='_blank'>Xi'an Jiaotong University</a>
    <sup>2</sup> <a href='https://ai.tencent.com/' target='_blank'>Tencent AI Lab</a>
    <sup>3</sup>
    <a  target='_blank'>The University of Hong Kong</a>&emsp;
    </br>
    <sup>*</sup> Equal Contribution&emsp;
</div>

<a href="https://arxiv.org/abs/2312.09251"><img src="https://img.shields.io/badge/Paper-PDF-orange"></a> 
<a href="#LICENSE--citation">
  <img alt="License: Apache2.0" src="https://img.shields.io/badge/LICENSE-Apache%202.0-blue.svg"/>
</a>


<p align="center" width="100%">
<img src="assets/overview.png"  width="100%" height="60%">
</p>



* VL-GPT is a generative pre-trained transformer model for vision and language understanding and generation tasks, which can perceive and generate visual and linguistic data concurrently. By employing a straightforward auto-regressive objective, VL-GPT achieves a unified pre-training for both image and text modalities.

* We also propose an image tokenizer-detokenizer framework for the conversion between raw images and continuous visual embeddings, analogous to the role of the BPE tokenization in language models.


## TODOs

- [ ] Training and evaluation code
- [ ] Pretrained and instruction-tuned model weights



## License
This project is released under the Apache 2.0 license. Please see the [LICENSE](LICENSE) file for more information.