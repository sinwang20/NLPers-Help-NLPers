# NLPers-Help-NLPers

> It was the best of times, it was the worst of times. --Charles Dickens

In the era of "Big Model," the territory for NLPers to thrive is becoming increasingly limited. As a result, we aim to provide support to NLPers through the "NLPers help NLPers" approach, hoping to spark new inspiration and opportunities.

## Embracing the Big Model

Repo: Awesome-LLM [[github]](https://github.com/Hannibal046/Awesome-LLM)

Expanding the capabilities and properties of models, rather than just skooching up benchmark numbers.

- How do you make language models stateful? How can models learn from their experiences? How can we do few shot learning in a way that updates parameters and doesn't require dumping stuff into the context buffer?

- How is information stored in an LLM? How can you efficiently edit this information? Can you design architectures that make this information representation explicit?

- (multilingual)
How do you change/expand the input language of model without fully retraining it? Can you do this through fine-tuning?

- How is the performance of large models predicted by that of smaller ones?

## Data is All You Need

Better benchmarks, Better strategy for obtaining clean data. 

- Dataset quality seems to matter more than model size. How do we measure the quality of a dataset? How do we prune the junk without a ton of human effort? Can curriculum learning speed up training for LLMs (it definitely does for humans)?

## Last Mile of NLP

LLM has successfully resolved 95% of the issues, yet the remaining 5% is crucial in providing a direct and constructive impact on people's lives. The question remains: How can we overcome the "last mile" problem and unleash the full potential of existing technologies?

- Do you want to facilitate users' information needs with precise information (e.g., instead of inflating the answer with something irrelvant)?

Grouding

## NLP for Everything

> The limits of my language are the limits of my world. --Ludwig Wittgenstein

- **nlp+robotics, XR/VR, etc.**

ChatGPT for Robotics: Design Principles and Model Abilities [[link]](https://www.microsoft.com/en-us/research/group/autonomous-systems-group-robotics/articles/chatgpt-for-robotics/)

Repo: Awesome-LLM-Robotics [[github]](https://github.com/GT-RIPL/Awesome-LLM-Robotics)

- **nlp for science**

- Do you want to build NLP systems for high-stakes application (e.g., in the medical domain)?

## Interpretable AI

Fathiful, human-interpretable explanation

200 Concrete Open Problems in Mechanistic Interpretability: Introduction. Neel Nanda [[link]](https://www.alignmentforum.org/posts/LbrPTJ4fmABEdEnLf/200-concrete-open-problems-in-mechanistic-interpretability)


## AI Safety/Alignment

Course: https://course.mlsafety.org/




- What are the security vulnerabilities of API accessible models? Can the weights be extracted efficiently? Can you infer the architecture from adversarial inputs/outputs?

- Do you want to test whether NLP models satisfy certain privacy and fairness constrains (instead of trusting a black-box model)?









- **Transparency:** Transparency tools offer insight into LLM's inner workings. Enhanced interpretability helps with anticipating failure modes of LLMs and identifying what caused them to make a decision.

    Interpretable Explanations of Black Boxes by Meaningful Perturbation. [[pdf]](https://arxiv.org/abs/1704.03296)   

    Locating and Editing Factual Knowledge in GPT. [[pdf]](https://arxiv.org/abs/2202.05262)   

    The Mythos of Model Interpretability. [[pdf]](https://arxiv.org/abs/1606.03490)   

    Sanity Checks for Saliency Maps. [[pdf]](https://arxiv.org/abs/1810.03292)



- **Anomaly detection plays a vital role in identifying various hazards:** out-of-distribution inputs, model misuse, proxy gaming, sudden behavioral shifts, and unanticipated failure modes. Early detection of anomalies greatly improves model reliability in real-world situations.

    Deep Anomaly Detection with Outlier Exposure. [[pdf]](https://arxiv.org/abs/1812.04606)  

    A Baseline for Detecting Misclassified and Out-of-Distribution Examples in Neural Networks. [[pdf]](https://arxiv.org/abs/1610.02136)   

    ViM: Out-Of-Distribution with Virtual-logit Matching. [[pdf]](https://arxiv.org/abs/2203.10807)   



- **Trojans:** Adversaries can implant hidden functionality into ML models, which can trigger unexpected harmful behaviors. Studying trojans sheds light on detecting and removing dangerous hidden behaviors, ultimately leading to safer and more secure models.

    Poisoning and Backdooring Contrastive Learning. [[pdf]](https://arxiv.org/abs/2106.09667)  

    Universal Litmus Patterns: Revealing Backdoor Attacks in CNNs. [[pdf]](https://arxiv.org/abs/1906.10842)  

    Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks. [[pdf]](https://people.cs.uchicago.edu/~ravenben/publications/pdf/backdoor-sp19.pdf)  



- **Proxy Gaming:** Recent LLMs are trained using RL to optimize potentially fragile reward models. Can we improve the robustness of reward model proxies to optimization pressure from the policy? Alternatively, can we detect when reward models are being gamed?

    Scaling Laws for Reward Model Overoptimization. [[pdf]](https://arxiv.org/abs/2210.10760)

- **Adversarial Robustness:** Future agents may be guided by neural network proxies such as networks that model human values. If those proxies are LLMs, can we ensure that they are robust to optimization pressure and adversarial inputs?

    TextGrad: Advancing Robustness Evaluation in NLP by Gradient-Driven Optimization. [[pdf]](https://arxiv.org/abs/2212.09254)   

    Gradient-based Adversarial Attacks against Text Transformers. [[pdf]](https://arxiv.org/abs/2104.13733)


- **Model Honesty:** Models have been observed to lie in games like Diplomacy, which raises concerns about their trustworthiness. Research on encouraging models to honestly report their beliefs is key to fostering trust & improving the reliability of AI systems.

    Discovering Latent Knowledge in Language Models Without Supervision. [[pdf]](https://arxiv.org/abs/2212.03827)

- **Machine Ethics:** As AI systems advance, incorporating moral understanding into our AI systems becomes crucial. Fostering ethical behavior & aligning AI with human values ensures responsible & trustworthy agents.

    What Would Jiminy Cricket Do? Towards Agents That Behave Morally. [[pdf]](https://arxiv.org/abs/2110.13136)   

    Aligning AI With Shared Human Values. [[pdf]](https://arxiv.org/abs/2008.02275)   



(2023.03) Natural Selection Favors AIs over Humans. 
Dan Hendrycks. [[pdf]](https://arxiv.org/abs/2303.16200)


**Pretraining Language Models with Human Preferences**.
Tomasz Korbak, Kejian Shi, Angelica Chen, Rasika Bhalerao, Christopher L. Buckley, Jason Phang, Samuel R. Bowman, Ethan Perez. [[pdf]](https://arxiv.org/abs/2302.08582)

Locating and Editing Factual Associations in GPT

Training Language Models with Language Feedback

(2021.12) **Eliciting latent knowledge: How to tell if your eyes deceive you**.
Paul Christiano, Ajeya Cotra, and Mark Xu (Alignment Research Center). [[google docs]](https://docs.google.com/document/d/1WwsnJQstPq91_Yh-Ch2XRL8H_EpsnjrC1dwZXR37PC8/edit#)

[2017 ACL] **MalwareTextDB: A Database for Annotated Malware Articles**.
 Swee Kiat Lim, Aldrian Obaja Muis, Wei Lu, Chen Hui Ong. [[pdf]](https://aclanthology.org/P17-1143/)
 
 (2023 Arxiv) **On the Feasibility of Specialized Ability Stealing for Large Language Code Models**.
Zongjie Li, Chaozheng Wang, Pingchuan Ma, Chaowei Liu, Shuai Wang, Daoyuan Wu, Cuiyun Gao. [[pdf]](http://export.arxiv.org/abs/2303.03012v1)

 
## Retrieval-based NLP

(2022 Arxiv) **Demonstrate-Search-Predict: Composing retrieval and language models for knowledge-intensive NLP**.
Omar Khattab, Keshav Santhanam, Xiang Lisa Li, David Hall, Percy Liang, Christopher Potts, Matei Zaharia. [[pdf]](https://arxiv.org/abs/2212.14024)


## Others

- What's the best way to do RLHF? Are there better optimizers than PPO? Can we do active learing + RLHF?

- Modern transformers are optimized for training efficiency. Are there architectures thar are better optimized for testing efficiency?

- Do you want to run NLP models with good prediction performance on edge devices (e.g., smartphones)?

proactive search & recommendation systems

Incremental/lifetime learning

distillation

imiation learning

(2023 Arxiv) Eight Things to Know about Large Language Models. Samuel R. Bowman.  [[pdf]](https://arxiv.org/pdf/2304.00612.pdf)

(2023 Arxiv) Choose Your Weapon: Survival Strategies for Depressed AI Academics. Julian Togelius, Georgios N. Yannakakis. [[pdf]](https://arxiv.org/pdf/2304.06035.pdf)


## Rethink your Life Path

> Two roads erged in a wood, and I ---
> I took the one less travelled by,
> And that has made all the difference.
>   --Robert Frost


## Contribution
Please feel free to contribute and promote your insight or advice here! And we will add you to the contributor list😊.

### Credits
[Christopher Potts](https://www.youtube.com/watch?v=-lnHHWRCDGk), Tom Goldstein, Yoav Artzi, [Yangfeng Ji](https://medium.com/@yangfengji/if-you-dont-like-the-question-ask-a-different-one-973b27e61fcf), Dan Hendrycks.
