# [How Diffusion Models Work](https://www.deeplearning.ai/short-courses/how-diffusion-models-work/)
In How Diffusion Models Work, you will gain a deep familiarity with the diffusion process and the models which carry it out. More than simply pulling in a pre-built model or using an API, this course will teach you to build a diffusion model from scratch.

In this course you will:

- Explore the cutting-edge world of diffusion-based generative AI and create your own diffusion model from scratch.
- Gain deep familiarity with the diffusion process and the models driving it, going beyond pre-built models and APIs.
- Acquire practical coding skills by working through labs on sampling, training diffusion models, building neural networks for noise prediction, and adding context for personalized image generation.
- At the end of the course, you will have a model that can serve as a starting point for your own exploration of diffusion models for your applications.

This one-hour course, taught by Sharon Zhou will expand your generative AI capabilities to include building, training, and optimizing diffusion models.

Hands-on examples make the concepts easy to understand and build upon. Built-in Jupyter notebooks allow you to seamlessly experiment with the code and labs presented in the course.

## 生成资产说明 (weights/ 下文件) —— 中文版
- `run_image_wddpm_uncond.png`：无条件 DDPM 最终模型生成的 32 张样本，作为基线视觉质量。  
  推荐图注：「无条件 DDPM 生成样例（32 张，16x16 Sprite）」。
- `run_image_wddpm_ep{0,4,8,31}.png`：使用不同训练轮次的权重生成的对比图，展示随训练迭代质量提升。  
  推荐图注：「训练轮次 {0,4,8,31} 下的无条件生成对比」。
- `run_image_wctx_ddpm_0_hero.png` ... `run_image_wctx_ddpm_4_side_facing.png`：针对 5 个类别（hero, non_hero, food, spell, side_facing）的条件 DDPM 生成，每类 32 张。  
  推荐图注：「条件 DDPM 生成：<类别名>（32 张）」。
- `run_image_wctx_ddpm_mixed.png`：随机混合类别的条件 DDPM 生成，观察多类混合与多样性。  
  推荐图注：「条件 DDPM 生成：随机混合类别（32 张）」。
- `run_image_wddim_fast.png`：无条件 DDIM 快速采样（25 步）生成的 32 张样本，用于速度-质量对比。  
  推荐图注：「DDIM 快速采样（25 步）无条件生成」。
- `run_image_wddpm_full.png`：无条件 DDPM 全 500 步生成的 32 张样本，用于与 DDIM 对照的高保真参考。  
  推荐图注：「DDPM 全步采样（500 步）无条件生成」。
- `run_image_wddim_ctx_fast.png`：条件 DDIM 快速采样（25 步），涵盖多类标签的 32 张样本，用于展示条件控制下的快速生成。  
  推荐图注：「DDIM 快速采样（25 步）条件生成（多类）」。
