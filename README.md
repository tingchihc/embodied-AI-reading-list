# Embodied-AI  

This repository offers a brief summary of essential papers and blogs on embodied AI, alongside a categorized collection of 3D scene representation, LLM agents papers and useful code repositories for starting your own project.

# Table of Contents  

Topic 1: <b>[Learning about 3D reconstruction and scene rendering](#nerf)</b>  
Topic 2: <b>[Learning about 3D scene representation](#3d-scene-rep)</b>  
Topic 3: <b>[Learning about LLM agents](#llm-agent)</b>  
Topic 4: <b>[Learning about Text-to-image/video](#t2iv)</b>  
Topic 5: <b>[Learning about Auto driving](#auto-drive)</b>  
Topic 6: <b>[Diffusion for Robotics and RL](#dif-RL)</b>  
Topic 7: <b>[Benchmarks: simulators, environments, datasets](#benchmark)</b>

<details>
  <summary><b>Topic 1: Learning about 3D reconstruction and scene rendering</b><a name="nerf"></a></summary>
  <ul>
    <li>(ICRA'24 <b>Oral</b>) Kashu Yamazaki, et al. Open-Fusion: Real-time Open-Vocabulary 3D Mapping and Queryable Scene Representation. <a href="https://arxiv.org/pdf/2310.03923">📚</a> <a href="https://uark-aicv.github.io/OpenFusion/">🌍</a></li>
    <li>(arxiv) Yuqi Zhang, et al. Efficient Large-scale Scene Representation with a Hybrid of High-resolution Grid and Plane Feature. <a href="https://arxiv.org/pdf/2303.03003">📚</a> <a href="https://zyqz97.github.io/GP_NeRF/">🌍</a> </li>  
    <li>(ICLR'24) Francis Engelmann, et al. OpenNeRF: OpenSet 3D Neural Scene Segmentation with Pixel-Wise Features and Rendered Novel Views. <a href="https://arxiv.org/pdf/2404.03650">📚</a> <a href="https://github.com/opennerf/opennerf">🌍</a> </li>  
  </ul>
</details>

<details>
  <summary><b>Topic 2: Learning about 3D scene representation</b><a name="3d-scene-rep"></a></summary>
  <ul>
    <li>(CVPR'24) Alexandros Delitzas, et al. SceneFun3D: Fine-Grained Functionality and Affordance Understanding in 3D Scenes. <a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Delitzas_SceneFun3D_Fine-Grained_Functionality_and_Affordance_Understanding_in_3D_Scenes_CVPR_2024_paper.pdf">📚</a> <a href="https://scenefun3d.github.io/">🌍</a> </li>  
    <li>(CVPR'23) Songyou Peng, et al. OpenScene: 3D Scene Understanding with Open Vocabularies. <a href="https://arxiv.org/pdf/2211.15654">📚</a> <a href="https://pengsongyou.github.io/openscene">🌍</a> </li>  
    <li>(NeurIPS'23) Yining Hong, et al. 3D-LLM: Injecting the 3D World into Large Language Models. <a href="https://arxiv.org/pdf/2307.12981">📚</a> <a href="https://vis-www.cs.umass.edu/3dllm/">🌍</a> </li>  
    <li>(ICCV'23) Yicong Hong, et al. Learning Navigational Visual Representations with Semantic Map Supervision. <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Hong_Learning_Navigational_Visual_Representations_with_Semantic_Map_Supervision_ICCV_2023_paper.pdf#:~:text=Inspired%20by%20the%20behavior%20that%20hu-mans%20naturally%20build">📚</a> <a href="https://github.com/YicongHong/Ego2Map-NaViT">🌍</a> </li>  
    <li>(NeurIPS'23) Ayça Takmaz, et al. OpenMask3D: Open-Vocabulary 3D Instance Segmentation. <a href="https://arxiv.org/pdf/2306.13631">📚</a> <a href="https://openmask3d.github.io/">🌍</a> </li>  
    <li>(ICCV'23 <b>Oral</b>) Justin Kerr, et al. LERF: Language Embedded Radiance Fields. <a href="https://arxiv.org/pdf/2303.09553">📚</a> <a href="https://www.lerf.io/">🌍</a> </li>  
  </ul>
</details>

<details>
  <summary><b>Topic 3: Learning about LLM agents</b><a name="llm-agent"></a></summary>
  <ul>
    <li>(arxiv) Yuhang Liu, et al. InfiGUIAgent: AMultimodalGeneralist GUI Agent with Native Reasoning and Reflection. <a href="https://arxiv.org/pdf/2501.04575">📚</a> </li>
    <li>(TMLR'22) Scott Reed, et al. A Generalist Agent. <a href="https://arxiv.org/pdf/2205.06175">📚</a> </li>
    <li>(arxiv) Michael S. Ryoo, et al. xGen-MM-Vid (BLIP-3-Video): You Only Need 32 Tokens to Represent a Video Even in VLMs. <a href="https://arxiv.org/pdf/2410.16267">📚</a> <a href="https://www.salesforceairesearch.com/opensource/xGen-MM-Vid/index.html">🌍</a> </li>
    <li>(CVPR'24) Xiaoqi Li, et al. ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation. <a href="https://arxiv.org/pdf/2312.16217">📚</a> <a href="https://sites.google.com/view/manipllm">🌍</a> </li>  
    <li>(COLM'24) Tianhua Tao, et al. CRYSTAL: Illuminating LLM Abilities on Language and Code. <a href="https://openreview.net/attachment?id=kWnlCVcp6o&name=pdf">📚</a> <a href="https://www.llm360.ai/#crystal">🌍</a> </li>  
    <li>(COLM'24) Qingyun Wu, et al. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversations. <a href="https://openreview.net/attachment?id=BAakY1hNKS&name=pdf">📚</a> <a href="https://github.com/microsoft/autogen">🌍</a> </li>  
    <li>(ECCV'24) Runsen Xu, et al. PointLLM: Empowering Large Language Models to Understand Point Clouds. <a href="https://arxiv.org/pdf/2308.16911">📚</a> <a href="https://github.com/OpenRobotLab/PointLLM">🌍</a> </li>  
    <li>(ICML'24 <b>Oral</b>) Ziniu Hu, et al. SceneCraft: An LLM Agent for Synthesizing 3D Scenes as Blender Code. <a href="https://openreview.net/attachment?id=gAyzjHw2ml&name=pdf">📚</a> </li>  
  </ul>
</details>

<details>
  <summary><b>Topic 4: Learning about Text-to-image/video</b><a name="t2iv"></a></summary>
  <ul>
    <li>(COLM'24) Abhay Zala, et al. DiagrammerGPT: Generating Open-Domain, Open-Platform Diagrams via LLM Planning. <a href="https://openreview.net/attachment?id=NV8yRJRET1&name=pdf">📚</a> <a href="https://diagrammergpt.github.io/">🌍</a> </li>  
    <li>(COLM'24) Han Lin, et al. VideoDirectorGPT: Consistent Multi-Scene Video Generation via LLM-Guided Planning. <a href="https://openreview.net/attachment?id=sKNIjS2brr&name=pdf">📚</a> <a href="https://videodirectorgpt.github.io/">🌍</a> </li>  
  </ul>
</details>

<details>
  <summary><b>Topic 5: Learning about Auto driving</b><a name="auto-drive"></a></summary>
  <ul>
    <li>(Technical report) Wayve. GAIA-2: Pushing the Boundaries of Video Generative Models for Safer Assisted and Automated Driving. <a href="https://drive.google.com/file/d/1L_FwiQS0KvrzERaYeG08AA1GO5HpIMfq/view">📚</a> <a href="https://wayve.ai/thinking/gaia-2/">🌍</a></li>
    <li>(COLM'24) Jiageng Mao, et al. A Language Agent for Autonomous Driving. <a href="https://openreview.net/attachment?id=UPE6WYE8vg&name=pdf">📚</a> <a href="https://usc-gvl.github.io/Agent-Driver/">🌍</a> </li>  
    <li>(ICLR'24) Licheng Wen, et al. DiLu🐴: A Knowledge-Driven Approach to Autonomous Driving with Large Language Models. <a href="https://arxiv.org/pdf/2309.16292">📚</a> <a href="https://pjlab-adg.github.io/DiLu/">🌍</a> </li>
    <li>(ICCV'23) Maximilian Bernhard, et al. MapFormer: Boosting Change Detection by Using Semantic Pre-change Information. <a href="https://arxiv.org/pdf/2303.17859">📚</a> <a href="https://github.com/mxbh/mapformer">🌍</a> </li> 
    <li>(ICCV'23) Yunpeng Zhang, et al. OccFormer: Dual-path Transformer for Vision-based 3D Semantic Occupancy Prediction. <a href="https://arxiv.org/abs/2304.05316">📚</a> <a href="https://github.com/zhangyp15/OccFormer">🌍</a></li>
    <li>(CVPR'23) Yihan Hu, et al. Planning-oriented Autonomous Driving. <a href="https://arxiv.org/pdf/2212.10156">📚</a> <a href="https://github.com/OpenDriveLab/UniAD">🌍</a> </li>  
    <li>(CVPR'22) Tim Meinhardt, et al. TrackFormer: Multi-Object Tracking with Transformers. <a href="https://arxiv.org/pdf/2101.02702">📚</a> <a href="https://github.com/timmeinhardt/trackformer">🌍</a> </li>  
    <li>(NeurIPS'21) Mandela Patrick, et al. Keeping Your Eye on the Ball: Trajectory Attention in Video Transformers. <a href="https://arxiv.org/abs/2106.05392">📚</a> <a href="https://github.com/facebookresearch/Motionformer">🌍</a> </li>  
  </ul>
</details>

<details>
  <summary><b>Topic 6: Diffusion for Robotics and RL</b><a name="dif-RL"></a></summary>
  <ul>
    <li>(arxiv) Carmelo Sferrazza, et al. BodyTransformer:Leveraging Robot Embodiment for Policy Learning. <a href="https://arxiv.org/pdf/2408.06316">📚</a> <a href="https://sferrazza.cc/bot_site/">🌍</a> </li>
    <li>(SIGGRAPH Asia'24) Agon Serifi, et al. Robot Motion Diffusion Model: Motion Generation for Robotic Characters. <a href="https://la.disneyresearch.com/wp-content/uploads/RobotMDM_red.pdf">📚</a> </li>  
    <li>(NeurIPS'23) Biao Jiang, et al. MotionGPT: Human Motion as a Foreign Language. <a href="https://arxiv.org/pdf/2306.14795">📚</a> <a href="https://github.com/OpenMotionLab/MotionGPT">🌍</a> </li>
  </ul>
</details>

<details>
  <summary><b>Topic 7: Benchmarks: simulators, environments, datasets</b><a name="#benchmark"></a></summary>
  <ul>
    <li>(NeurIPS'24) Tianbao Xie, et al. OSWORLD: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments. <a href="https://arxiv.org/pdf/2404.07972">📚</a> <a href="https://os-world.github.io/">🌍</a> </li>  
  </ul>
</details>

# Courses  
- MIT (6.5940, F24) TinyML and Efficient Deep Learning Computing [URL](https://hanlab.mit.edu/courses/2024-fall-65940)
- Stanford (CS 329S, W22) Machine Learning Systems Design [URL](https://stanford-cs329s.github.io/)
- UT Austin Advances in Deep Learning [URL](https://ut.philkr.net/advances_in_deeplearning/)  

# Other Resources  

1. <a href="https://github.com/ActiveVisionLab/Awesome-LLM-3D">Awesome-LLM-3D</a>
2. <a href="https://github.com/Hannibal046/Awesome-LLM">Awesome-LLM</a>  
3. <a href="https://github.com/mbreuss/diffusion-literature-for-robotics">Diffusion-Literature-for-Robotics</a>  
4. <a href="https://github.com/opendilab/awesome-diffusion-model-in-rl">Awesome Diffusion Model in RL</a>
5. <a href="https://github.com/Thinklab-SJTU/Awesome-LLM4AD">Awesome-LLM4AD</a>  
6. <a href="https://github.com/GT-RIPL/Awesome-LLM-Robotics">Awesome-LLM-Robotics</a>
7. <a href="https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List">Embodied_AI_Paper_List</a>
8. <a href="https://github.com/annika-thomas/MIT-PALS?tab=readme-ov-file">MIT Perception and Localization Seminar</a>
9. <a href="https://github.com/ga642381/speech-trident">speech-trident</a>
10. <a href="https://github.com/BaiShuanghao/my_arXiv_daily">my_arXiv_daily</a>  

# Userful Tools

1. <a href="https://github.com/isl-org/Open3D?tab=readme-ov-file">Open3D</a>
2. <a href="https://github.com/OpenGVLab/LLaMA-Adapter">LLaMA-Adapter</a>
3. <a href="https://github.com/docling-project/docling">docling</a>  
4. <a href="https://github.com/deven367/writes-like-you">writes-like-you</a>
