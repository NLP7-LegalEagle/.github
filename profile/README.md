# Legal Eagle 🦅

## 👥 NLP Team Project - Team 7 👥 - BoMin LEE, Jeonhui LEE, Chanwoo LIM, Hyeongbin SEO, Sebin JEONG


### Transformers
-    BitsAndBytesConfig: model의 bit format을 임의로 지정하여 큰 gpu 자원이 필요치 않도록 함. 해당 모델에서는 NF4(정규화된 부동 소수점) 양자화를 사용하고, dtype을 float16으로 지정하여 계산이 빠르게 진행되도록 함.
-    AutoModelForCausalLM: 경로나 url을 지정하여 모델을 불러오는데 사용됨.
-    AutoTokenizer: 해당 모델의 tokenizer
-    TrainingArguments: training에 필요한 arguments를 지정

### Peft
-    Parameter-Efficient Fine-Tuning 소수의 모델 파라미터를 fine tuning 함으로 효율적 및 적은 컴퓨팅 자원으로 fine tuning이 가능해짐. Loar, Prefix Tuning, P-Tuning 등 이러한 기법들을 쉽게 사용하게 해주는 라이브러리로, 해당 모델에는 Loar 기법을 사용함.

### Trl
-    Trl은 transformer 강화 학습을 제공하는 라이브러리로 해당 모델에서는 SFTTrainer(Supervised fine-tuning)를 이용.


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
