# Building Task Bots with Self-Learning for Enhanced Adaptability, Extensibility, and Factuality

This thesis advocates for a paradigm shift toward task bots that can autonomously adapt, extend their functionalities, and ensure factual accuracy with minimal or zero human intervention. To achieve this, we explore three core research questions:

1. **Adaptability to Unseen User Behaviors**: How can task bots automatically adapt to unforeseen user behaviors?
2. **Extensibility of Task Definitions**: How can task bots extend their functionalities with minimal human effort?
3. **Factuality Assurance**: How can task bots mitigate factual errors ("hallucinations") despite possessing relevant knowledge?

### Chapter Summaries

- **Chapter 2: Literature Review**  
  An overview of neural approaches for building end-to-end task bots, addressing three post-deployment challenges:  
  1. Adapting to unforeseen user behaviors.  
  2. Handling task definition extensions.  
  3. Mitigating factual errors ("hallucinations").

- **Chapter 3: Self-Learning for Adaptability**  
  SL-AGENT is introduced as a self-learning framework enabling task bots to adapt to changing environments by learning from unlabeled human-bot interactions with minimal or zero human annotations. This framework employs a pre-trained reward model with a novel data augmentation strategy to evaluate response quality.  
  - **Code**: [SL-Agent Repository](https://github.com/zhangxy-2019/SL-Agent)

- **Chapter 4: Schema-Guided LLM Prompting for Extensibility**  
  SGP-TOD is presented as a schema-guided prompting strategy for developing and maintaining task bots with minimal human effort. It integrates symbolic knowledge (task schemas) into large language models (LLMs), enabling schema-compliant responses and facilitating extensibility to new tasks through schema modifications.  
  - **Code**: [SGP-TOD Repository](https://github.com/zhangxy-2019/sgp-tod)

- **Chapter 5: Self-Alignment for Factuality**  
  A self-alignment framework is proposed to reduce hallucinations in LLMs by leveraging their self-evaluation capabilities. Additionally, SK-TUNING is introduced to enhance LLMs' confidence estimation and calibration, further improving self-evaluation abilities.  
  - **Code**: [Self-Alignment for Factuality Repository](https://github.com/zhangxy-2019/Self-Alignment-for-Factuality)

- **Chapter 6: Conclusions and Future Directions**  
  A summary of findings and potential avenues for future research.

### Citation

If you find this work useful, please cite:

```bibtex
@article{zhang2025selflearning,
  title={Building Task Bots with Self-learning for Enhanced Adaptability, Extensibility, and Factuality},
  author={Xiaoying Zhang},
  journal={Preprint},
  url = "https://github.com/zhangxy-2019/thesis_self_learning_agent",
  year={2025}
}
