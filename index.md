# Portfolio

### 1. -- Emora Chatbot: Winner of Amazon Alexa Prize 3 (2020)

Emora is a chatbot developed during the Amazon Alexa Prize Socialbot Grand Challenge which won the competition in 2020, advancing through two elimination rounds based on user ratings and then receiving the highest overall rating from the panel of final invited judges.

An example conversation Emora can hold:
<br>
<div style="text-align: center;">
  <img src="images/emora_convo_example.png" style="width:90%; height:auto;"/>
</div>

The system architecture of the Emora Chatbot:
<br>
<div style="text-align: center;">
  <img src="images/architecture.png" style="width:90%; height:auto;"/>
</div>

The user ratings Emora received during the quarter and semifinal rounds of the competition:
<br>
<div style="text-align: center;">
  <img src="images/dailyrating.png" style="width:90%; height:auto;"/>
</div>

**More Information:**
* Read the Amazon Technical Proceedings paper [here](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexaprize/assets/challenge3/proceedings/Emory-Emora.pdf)

* &#9733; Code for running the winning Emora is available at the [Emora Github Repository](https://github.com/emora-chat/emora_ap3_parlai).

* Emora in the News in an [Amazon Article](https://www.amazon.science/latest-news/alexa-prize-interviews?fbclid=IwAR2Iu7HwssbVvqmy1AB2gSOtZfoOps5nbxcpQqlTLgrz1czMtWnEH5X1JVY) and an [Emory Article](https://news.emory.edu/stories/2020/08/er_alexa_prize/campus.html)!

* Learn more about Emora from our [Youtube Playlist](https://www.youtube.com/playlist?list=PLsMGYQfhCveJE1uSslBZjoiRAVHDJoiQa)!

---

### 2. -- Article QABot using Generative AI

Article QABot is an article-grounded conversational question-answering dialogue system that ingests online FAQ documents in order to offer customer support. It is a modular system that incorporates numerous dialogue-relevant tasks, including information-retrieval, hallucination-detection, and response generation, and leverages prompt-based large language model approaches.

An example prompt for response generation:
<br>
<div style="border: 1px solid black; display: inline-block; padding: 10px; text-align: center;">
  <img src="images/articlebot_response_example.png" style="width:90%; height:auto;"/>
</div>

Overall Article QABot architecture:
<br>
<div style="text-align: center;">
  <img src="images/articlebot_architecture.png" style="width:90%; height:auto;"/>
</div>

Measured response correctness for Article QABot:
<br>
<div style="text-align: center;">
  <img src="images/articlebot_response_prompt_improvement.png" style="width:90%; height:auto;"/>
</div>

---

### 3. -- ConvoSenseGenerator

ConvoSenseGenerator is a fine-tuned T5 model that generates commonsense inferences for a provided dialogue context. It is fine-tuned on a new dialogue commonsense dataset, ConvoSense, collected using GPT that boasts greater contextual novelty, a higher volume of inferences per example, and substantially enriched detail compared to previous datasets. 

Example commonsense inference outputs of the ConvoSenseGenerator:
<br>
<div style="text-align: center;">
  <img src="images/convosense_model_example_edit.png" style="width:90%; height:auto;"/>
</div>

Illustration of the ConvoSense ChatGPT framework including an example of the prompt: 
<br>
<div style="text-align: center;">
  <img src="images/convosense_design.png" style="width:90%; height:auto;"/>
</div>

Empirical results from human evaluation demonstrating the superiority of the ConvoSenseGenerator:
<br>
<div style="text-align: center;">
  <img src="images/convosense_model_results.png" style="width:90%; height:auto;"/>
</div>

**More Information:**

* Read the TACL 2024 paper [here](https://aclanthology.org/2023.acl-long.839/)!

* &#9733; Code for the ConvoSense project is available at the [Github repository]()

* &#9733; **Trained Model:** Our best-performing ConvoSense-trained model is released through HuggingFace [here](https://huggingface.co/sefinch/ConvoSenseGenerator)!

---

### 4. -- Explicit Reasoning over Commonsense for Dialogue Response Generation

ConvoSense-E (CS-E) is a commonsense-grounded dialogue system that leverages explicit reasoning similar to chain-of-thought prompting to integrate ConvoSenseGenerator outputs into dialogue response generation using GPT. It is highly preferred by human judges compared to alternative dialogue systems.

Example dialogue showing motivation of explicit reasoning over commonsense inferences to guide follow-up response generation:
<br>
<div style="text-align: center;">
  <img src="images/dialogue-commonsense-example_cropped.png" style="width:90%; height:auto;"/>
</div>

Illustrative responses generated from the proposed approach (CS-E) and alternatives:
<br>
<div style="text-align: center;">
  <img src="images/rgcs_example.png" style="width:90%; height:auto;"/>
</div>

Human evaluation results showing superiority of proposed approach (ConvoSense-E) against alternatives:
<br>
<div style="text-align: center;">
  <img src="images/rgcs_results.png" style="width:90%; height:auto;"/>
</div>

---

### 5. -- Annotation of Behaviors in Chat Evaluation (ABC-Eval): Dialogue System Evaluation Framework

ABC-Eval is a novel evaluation framework for chat-oriented dialogue systems that measures the rate of 16 different dialogue behaviors that can be expressed by chatbots. It is a web-based annotation platform that was built on top of the ParlAI Javascript framework with major modifications to support the annotation requirements of the 16 ABC-Eval tasks. 

The online interface for annotating the usage of Correct Facts and Incorrect Facts:
<br>
<div style="text-align: center;">
  <img src="images/interface_knowledge.png" style="width:90%; height:auto;"/>
</div>

The online interface for annotating consistency mistakes:
<br>
<div style="text-align: center;">
  <img src="images/interface_consistency.png" style="width:90%; height:auto;"/>
</div>

**More Information:**

* Read the ACL 2023 paper [here](https://aclanthology.org/2023.acl-long.839/)!

* &#9733; Code for running the ABC-Eval platform is available at the [Github repository](https://github.com/emorynlp/ChatEvaluationPlatform)


---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
