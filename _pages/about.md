---
permalink: /
title: "Qi Luo"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<span style="color:gray;">Last updated: Apr 20, 2025</span>

👋 Hello! This is Qi Luo. I am a graduate student of Southern University of Science and Technology (SUSTech), working with Prof. [Yuqun Zhang](https://scholar.google.com/citations?hl=en&user=pPyNyusAAAAJ). I have a board interests in large language models and security. I'm collaborating with Dr. [Tan](https://scholar.google.com/citations?user=IQp5awMAAAAJ&hl=zh-CN) on a project about **LLM4Binary**. Feel free to contact me if you're interested in collaboration.

🎓 Education
======
* (2022.09-) M.S. in Southern University of Science and Technology.
  * Supervised by Prof. [Yuqun Zhang](https://zhangyuqun.github.io)
* (2015.09-2019.06) B.S. in Xidian University. 

📄 Publications
======
+ (TOSEM'2025) **Prompt-based Code Completion via Multi-Retrieval Augmented Generation.**
   + <u>Hanzhuo Tan<sup>*</sup>, <strong>Qi Luo<sup>*</sup></strong></u>, Jing Li,Yuqun Zhang
   + <span style="color:#00688A;">[<a href="https://dl.acm.org/doi/abs/10.1145/3725812" style="text-decoration:none; color:#00688A;">paper</a>]</span>
+ (EMNLP'2024) **LLM4Decompile: Decompiling Binary Code with Large Language Models.** 
  <div style="display: inline-flex; align-items: center;">
       <a href="https://github.com/albertan017/LLM4Decompile" style="display: inline-flex; align-items: center; padding: 5px 10px; border: 1px solid #ddd; border-radius: 5px; font-family: Arial, sans-serif; text-decoration: none; color: #333; background-color: #f5f5f5; margin-right: 5px;" target="_blank">
           <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub logo" width="20" height="20" style="margin-right: 5px;">
           Star
       </a>
       <span style="display: inline-flex; align-items: center; padding: 5px 10px; border: 1px solid #ddd; border-radius: 5px; font-family: Arial, sans-serif; background-color: #f5f5f5;" id="star-count">Loading...</span>
   </div>
   + Hanzhuo Tan, **Qi Luo**, Jing Li, Yuqun Zhang
   + <span style="color:#00688A;">[<a href="https://aclanthology.org/2024.emnlp-main.203" style="text-decoration:none; color:#00688A;">paper</a>] [<a href="https://github.com/albertan017/LLM4Decompile" style="text-decoration:none; color:#00688A;">code</a>] [<a href="https://huggingface.co/LLM4Binary" style="text-decoration:none; color:#00688A;">models</a>]</span>
+ (FSE'2023) **Enhancing Coverage-Guided Fuzzing via Phantom Program.**
   + Mingyuan Wu, Kunqiu Chen, **Qi Luo**, Jiahong Xiang, Ji Qi, Junjie Chen, Heming Cui, Yuqun Zhang.
   + <span style="color:#00688A;">[<a href="https://shadowmydx.github.io/papers/fse2023a.pdf" style="text-decoration:none; color:#00688A;">paper</a>]</span>

💼 Experience
======
+ (2023.06-2024.12) **Kwai**, LLM Algorithm Engineer Intern.
+ (2019.07-2021.06) **Streamax Technology**, Algorithm Engineer.
+ (2018.05-2018.07) **Huawei**, Software Development Engineer Intern.
  

<script>
    async function fetchStarCount() {
        try {
            const response = await fetch('https://api.github.com/repos/albertan017/LLM4Decompile');
            const data = await response.json();
            document.getElementById('star-count').textContent = data.stargazers_count;
        } catch (error) {
            console.error('Error fetching star count:', error);
            document.getElementById('star-count').textContent = 'Error';
        }
    }

    fetchStarCount();
</script>