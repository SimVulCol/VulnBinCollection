### Dataset

Our dataset is composed of three parts: vul, tpcs-s, and tpcs-l.

 In the vul part, there are 10 libraries containing a total of 100 CVE vulnerable functions. 

<img src="pic\image-20240613120257076.png" alt="image-20240613120257076" style="zoom: 67%;" /><img src="pic\image-20240613120315183.png" alt="image-20240613120315183" style="zoom: 50%;" />

Each vulnerability consists of five types of data: original (including multiple architectures, compilers, and optimizations), ollvm (obfuscated using the ollvm obfuscator), tigress (obfuscated using the Tigress obfuscator), bintuner (created using the Bintuner tool), and patch (the patched version of the vulnerability).

<img src="pic\image-20240613120333703.png" alt="image-20240613120333703" style="zoom: 90%;" />

<img src="pic\image-20240613120409953.png" alt="image-20240613120409953" style="zoom: 90%;" />

Tpcs-s and tpcs-l, as search pools of different sizes, were compared in the context of gcc-x86-O2.

<img src="pic\image-20240613120427830.png" alt="image-20240613120427830" style="zoom: 67%;" />

------



### Model

Asm2vec    [binary_function_similarity/Models/Asm2vec at main · Cisco-Talos/binary_function_similarity](https://github.com/Cisco-Talos/binary_function_similarity/tree/main/Models/Asm2vec)

Safe            [gadiluna/SAFE: SAFE: Self-Attentive Function Embeddings for binary similarity](https://github.com/gadiluna/SAFE)](https://github.com/gadiluna/SAFE)

Trex           [CUMLSec/trex](https://github.com/CUMLSec/trex)

jTrans         [vul337/jTrans: Official code of jTrans: Jump-Aware Transformer for Binary Code Similarity Detection](https://github.com/vul337/jTrans)

VulHawk    [RazorMegrez/VulHawk: This is the official repository for VulHawk](https://github.com/RazorMegrez/VulHawk)

Asteria       [Asteria-BCSD/Asteria](https://github.com/Asteria-BCSD/Asteria)

GMN          [binary_function_similarity/Models/GGSNN-GMN at main · Cisco-Talos/binary_function_similarity](https://github.com/Cisco-Talos/binary_function_similarity/tree/main/Models/GGSNN-GMN)

OFCI           [sbaresearch/ofci](https://github.com/sbaresearch/ofci)

CodeArt           [ziansu/codeart](https://github.com/ziansu/codeart)
