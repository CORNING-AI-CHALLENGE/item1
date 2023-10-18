# Corning AI challenge _ ITEM 1

### 🏴‍☠️ Large language models (LLMs)를 이용한 query engine

<br/>

💡 Purpose of project:

With the vast amount of data available on the internet, it has become increasingly challenging for users to find relevant information quickly and efficiently. Traditional search engines rely on keywords and algorithms to rank search results, which can be limiting and often fail to provide accurate and relevant information. To address this issue, we’d like to develop a query engine that leverages the power of large language models to provide more accurate and efficient search results.

<br/>

🔑 Objectives:

The primary objective of this project is to develop a query engine that utilizes large language models to understand the intent behind a user's search query and provide more accurate and relevant search results (including references). The following are the specific objectives of this project.

   * LLMs should be run locally. (The maximum usage of VRAM should be less than 80 GB) 
   * Read/handle various file formats (ppt, excel, word, pdf, and text).
   * Need to extract the exact contents or units of a table contained in the document.
   * Developed model should be able to handle English (or both Korean and English) doucumnets.
   * Need to return a reference list of its contents after searching.

<br/>

📖 참고 내용 

   * 해당 과제 평가는 논문 형식의 pdf, word, 그리고 주어진 웹페이지에서 질문에 대한 올바른 정보를 제공하는 지를 판단합니다. 
   * (Download Llama 2 model) [https://ai.meta.com/llama/] - 13B or 70B  model is preferred 
   * (Open platform for LLM based chatbot) [https://github.com/lm-sys/FastChat]
   * (Interface between LLMs and data) [https://github.com/run-llama/llama_index]


아래는 대회형 인터페이스의 예시입니다. 사용자가 질문을 입력하면, target data 폴더에서 해당 내용 / 위치를 대화형으로 반환합니다. 
![image](https://github.com/CORNING-AI-CHALLENGE/item1/assets/146830948/8f1da305-38a7-45ec-9dd4-a3f7b560e43e)

