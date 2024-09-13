# paper_MTPL
Official Project Homepage of Multi-Type Preference Learning: Enhancing Preference-Based Reinforcement Learning through Equal Preferences.

## Abstract
Preference-Based reinforcement learning (PBRL) learns directly from the preferences of human teachers regarding agent behaviors without needing meticulously designed reward functions. However, existing PBRL methods often learn primarily from explicit preferences, neglecting the possibility that teachers may choose equal preferences. This neglect may hinder the understanding of the agent regarding the task perspective of the teacher, leading to the loss of important information. To address this issue, we introduce the Equal Preference Learning Task, which optimizes the neural network by promoting similar reward predictions when the behaviors of two agents are labeled as equal preferences. Building on this task, we propose a novel PBRL method, Multi-Type Preference Learning (MTPL), which allows simultaneous learning from equal preferences while leveraging existing methods for learning from explicit preferences. To validate our approach, we design experiments applying MTPL to four existing state-of-the-art baselines across ten locomotion and robotic manipulation tasks in the DeepMind Control Suite. The experimental results indicate that simultaneous learning from both equal and explicit preferences enables the PBRL method to more comprehensively understand the feedback from teachers, thereby enhancing feedback efficiency. 

## Paper Link
You can find the full version of the paper here: [arXiv: 2409.07268](https://arxiv.org/abs/2409.07268)

## The following shows the learning curves for each task.
<embed id="pdfPlayer" src="1_ww.pdf" type="application/pdf" width="100%" height="600" >

## Citation Format
If you would like to cite this paper, please use the following format:
```
@misc{liu2024multitypepreferencelearningempowering,
      title={Multi-Type Preference Learning: Empowering Preference-Based Reinforcement Learning with Equal Preferences}, 
      author={Ziang Liu and Junjie Xu and Xingjiao Wu and Jing Yang and Liang He},
      year={2024},
      eprint={2409.07268},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2409.07268}, 
}
```
