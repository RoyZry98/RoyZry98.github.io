---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<head>
    <link rel="stylesheet" href="bootstrap.min.css">
    <script>var clicky_site_ids = clicky_site_ids || []; clicky_site_ids.push(101296995);</script>
    <script async src="//static.getclicky.com/js"></script>    
    <style>
	:root {
	  --theme-color: #EC707D; /* 确保这是一个有效的颜色 */
	  --venue-bg-color: rgb(108, 149, 181);
	}
	    
	g {
		color: #aaaaaa
	}

	 pt {
		/* color:chocolate; */
		/* color:#c50e0e; */
		color: var(--title-color);
		/* color:tomato; */
		font-weight: 500;
	}

	 em {
		font-style: italic;
	}

	 venue {
		/* background-color:royalblue; */
		/* background-color:rgb(80, 80, 80); */
		/* background-color: #d1a7a7; */
		/* background-color: #ca3737; */
		background-color: #EC707D;
		/* background-color: rgb(217, 229, 244); */
		/* color: rgb(16, 68, 158); */
		color: #ffffff;
		/* font-family: 'Nunito'; */
		font-size: 70%;
		font-weight: bold;
		line-height: 170%;
		/* padding-left: 1em;
		padding-right: 1em; */
		margin-right: 0.25em;
		width: 5em;
		display:inline-block;
		text-align: center;
		/* border-color: #ffffff; */
		border-width: 0px;
		border-style: none;
		border-radius: 0.1rem;
		/* -webkit-box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
		box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12); */
		/* border-radius: 4px; */
		/* -webkit-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    -moz-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    box-shadow:inset 0px 0px 0px 0.25em #fff; */
		/* border: #ffffff; */
		height: 1.7em;
		vertical-align:text-bottom;
		margin-bottom: 0.1em;
		/* letter-spacing: 0.1cap; */
	}

	 venue1 {
		/* background-color:royalblue; */
		/* background-color:rgb(80, 80, 80); */
		/* background-color: #d1a7a7; */
		/* background-color: #ca3737; */
		background-color: var(--venue-bg-color);
		/* background-color: rgb(217, 229, 244); */
		/* color: rgb(16, 68, 158); */
		color: #ffffff;
		/* font-family: 'Nunito'; */
		font-size: 70%;
		font-weight: bold;
		line-height: 170%;
		/* padding-left: 1em;
		padding-right: 1em; */
		margin-right: 0.25em;
		width: 5em;
		display:inline-block;
		text-align: center;
		/* border-color: #ffffff; */
		border-width: 0px;
		border-style: none;
		border-radius: 0.1rem;
		/* -webkit-box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);
		box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12); */
		/* border-radius: 4px; */
		/* -webkit-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    -moz-box-shadow:inset 0px 0px 0px 0.25em #fff;
	    box-shadow:inset 0px 0px 0px 0.25em #fff; */
		/* border: #ffffff; */
		height: 1.7em;
		vertical-align:text-bottom;
		margin-bottom: 0.1em;
		/* letter-spacing: 0.1cap; */
	}
 
	.filter {
		color: var(--color);
		background-color: #fff;
		border: var(--border);
		border-style: solid;
		border-radius: 0.2rem;
		border-width: 1.5px;
		transition: all .3s;
		touch-action: manipulation;
		font-size: 80%;
		line-height: 120%;
		/* width: 5em; */
	}
	
	.filter:focus {
		color: #171e29;
	}
	  
	  .filter:hover {
		border-color: var(--theme-color);
		color: white;
		background-color: var(--theme-color);
		fill: var(--theme-color);
	  }
	  
	  .filter:active {
		border-color: var(--theme-color);
		color: var(--theme-color);
		fill: var(--theme-color);
	  }
	  
	.button-59 {
	  align-items: center;
	  background-color: #fff;
	  border: 1px solid #dadada;
	  box-sizing: border-box;
	  color: #000000;
	  cursor: pointer;
	  display: inline-block; /* 修改为 inline-block */
	  fill: #000;
	  font-family: 'Nunito';
	  font-size: 0.7rem;
	  height: 1.1rem;
	  justify-content: center;
	  line-height: 1.3;
	  min-width: 60px; /* 增加最小宽度 */
	  outline: 0;
	  padding: 0 10px; /* 增加左右内边距 */
	  text-align: center;
	  text-decoration: none;
	  transition: color .3s, background-color .3s, border-color .3s; /* 限制过渡范围 */
	  user-select: none;
	  -webkit-user-select: none;
	  touch-action: manipulation;
	  margin-right: 0.2em;
	  border-radius: 0.2rem;
	}
	
	.button-59:hover {
	  border-color: var(--theme-color);
	  color: #fff;
	  fill: var(--theme-color);
	  background-color: var(--theme-color);
	  text-decoration: none;
	}
	
	.button-59:active {
	  border-color: var(--theme-color);
	  color: #fff;
	  fill: var(--theme-color);
	  background-color: var(--theme-color);
	}
	
	@media (min-width: 768px) {
	  .button-59 {
	    padding-left: 5px;
	    padding-right: 5px;
	  }
	}
    </style>
    <script>
        try{
            if (window.screen.width < 700) {
                setActiveStyleSheet("jemdoc_mobile.css"); 
            } 
            else if(/iPad/i.test(navigator.userAgent)){ 
                setActiveStyleSheet("jemdoc.css"); 
            } 
            else{
                setActiveStyleSheet("jemdoc.css"); 
            } 
        } 
        catch(e){} 
	
        function setActiveStyleSheet(filename){
            document.write("<link href="+filename+" rel=stylesheet>");
        }

        function checkFilter(type, li) {
            if (type == "All") {
                return true
            }
            else if (type == "First-authored") {
                res = li.getAttribute("first_authored")
                return res
            }
            else {
                cate = li.getAttribute("category")
                if (!cate) {
                    return false
                }
                items = cate.split(',')
                for (j = 0; j < items.length; j++) {
                    console.log(items[j])
                    if (type.toUpperCase() == items[j].toUpperCase()) {
                        return true
                    }
                }
                return false
            }
        }

        function filterPub(type) {
            ul = document.getElementById("publications")
            li = ul.getElementsByTagName("li")
            for (i = 0; i < li.length; i++) {
                if (!checkFilter(type, li[i])) {
                    li[i].style.display = "none";
                }
                else {
                    li[i].style.display = ""
                }
            }
            // change the button color
            bts = document.getElementsByClassName("filter")
            for (k = 0; k < bts.length; k++) {
                if (bts[k].textContent == type) {
                    bts[k].style.setProperty("--color", "#000")
                    bts[k].style.setProperty("--border", "#000")
                    // bts[k].style.color = "#000"
                }
                else {
                    bts[k].style.setProperty("--color", "#a0a0a0")
                    bts[k].style.setProperty("--border", "#d3d3d3")
                    // bts[k].style.color = "#a0a0a0"
                }
            }
        }

    </script>

    <script>
        // import data from './bibtex.json' assert { type: 'json' };

        function getBibTex(key) {
            prompt("You can copy the text manually.", data[key]);
        }
    </script>
</head>

<span class='anchor' id='about-me'></span>

# 👤 Biography
Rongyu is a third-year dual Ph.D. candidate at **Nanjing University** and **The Hong Kong Polytechnic University**, where he is co-supervised by [Prof. Yuan Du](https://iscl.nju.edu.cn/42925/list.htm) and [Prof. Dan Wang](https://wangdan.people.ust.hk/). He is also a long-term visiting student at **Peking University** under the supervision of [Prof. Shanghang Zhang](https://www.shanghangzhang.com). Previously, he received the M.Phil. degree from **The Chinese University of Hong Kong, Shenzhen**, supervised by [Prof. Fangxin Wang](https://mypage.cuhk.edu.cn/academics/wangfangxin/), the B.Mang. and B.Eng. degree from the joint program of **Beijing University of Posts and Telecommunications** and **Queen Mary University of London**. He has published over 20 papers in top-tier CCF-A and CAS-Q1 international conferences and journals such as **Nature Computational Science**, **NeurIPS**, **ICML**, **CVPR**, **AAAI**, **TMC**, and **TCSVT**, etc.

Feel free to reach out, or learn more from [My CV](assets/curriculum_vitae.pdf).

<div class="highlight-blocks">
  <div class="highlight-block">
    <h3>🔬 AI Researcher</h3>
    <ul>
      <li>Research focus on <strong>efficient</strong> and <strong>generalization</strong> learning</li>
      <li>Efficiency: Dynamic Neural Network</li>
      <li>Multimodal Generalization: Embodied AI including Robotics and Autonomous Driving</li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>✍️ Given Credits</h3>
    <ul>
      <li><strong>NSFC</strong> “<strong>Youth Student Basic Research Program (Ph.D.)</strong>”</li>
      <li><strong>CAST</strong> “<strong>Young Talent Support Project Doctoral Special Program</strong>”</li>
      <li><a href="https://scholar.google.com/citations?user=rRcc9eoAAAAJ&hl=zh-CN" target="_blank">
  <img src="https://img.shields.io/badge/Google%20Scholar-342%20Citations-9cf?logo=Google%20Scholar&labelColor=f6f6f6&style=flat" alt="Google Scholar Citations">
</a></li>
	<li><a href="https://github.com/RoyZry98" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Stars%20316-9cf?logo=GitHub&labelColor=f6f6f6&color=EC707D&logoColor=000000&style=flat" alt="GitHub Stars">
</a></li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>☎️ Contact Info</h3>
    <ul>
      <li><strong>Address:</strong> <a href="https://www.google.com/maps/search/%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6%E7%90%86%E7%A7%91%E4%BA%8C%E5%8F%B7%E6%A5%BC/@39.990772,116.3112251,17z/data=!3m1!4b1?entry=ttu&g_ep=EgoyMDI0MTIxMS4wIKXMDSoASAFQAw%3D%3D">Room 2728, Science Building No. 2, Peking University, Beijing, China</a></li>
      <li><strong>Phone:</strong> +(86) 188-1305-1303</li>
      <li><strong>Email:</strong> <email>royz981203@hotmail.com rongyu.zhang@connect.polyu.hk</email></li>
    </ul>
  </div>
</div>

<div class="highlight-blocks">
  <div class="highlight-block">
    <h3>🗺️ Research Path</h3>
    <div style="text-align: center;">
      <img src="images/path.png" alt="Research Focus Image" style="width:80%; height:auto; display: inline-block;">
    </div>
  </div>
</div>


<br>

# 🎓 Educations
- <img src="images/polyu_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **The Hong Kong Polytechnic University** (2023.09-Present) Dual Ph.D. in Computing Science
- <img src="images/nju_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **Nanjing University** (2023.09-Present) Dual Ph.D. in Electrical Science and Technology 
- <img src="images/cuhk_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **The Chinese University of Hong Kong, Shenzhen** (2021.09-2023.03) M.Phil. in Computer and Information Engineering
- <img src="images/bupt_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **Beijing University of Posts and Telecommunications** (2017.09-2021.06) Dual B.Mang. in E-Commerce Engineering with Law
- <img src="images/qmul_.png" style="width: 20px;height: auto;display: inline-block;vertical-align: middle"> **Queen Mary University of London** (2017.09-2021.06) Dual B.Eng. in Electrical Engineering and Computer Sciences

<br>

# 🔥 News
<div id="news" class="w3-container w3-margin-top-2 w3-cursive">
	  <div style="height:200px; width:100%; overflow:auto;">
	    <h4>📌 We have several academic intern positions at HMI Lab (Peking University). We actively work on AI4Science and Embodied AI. If you like what we do, don't hesitate to contact me.</h4>
		<p>[12.2025] 📕 I am selected for the 2025 “<strong>Youth Student Basic Research Program (Ph.D. Candidate)</strong>” of <strong>National Natural Science Foundation of China (NSFC)</strong> (around 900 recipients nationwide)</p>
		<p>[11.2025] 🎉 Two paper <strong>MoASE</strong> and <strong>MoLe-VLA</strong> were accepted by <strong>AAAI</strong> as <strong style="color: red;">Oral</strong> and Poster, respectively (CCF-A).</p>
		<p>[09.2025] 🎉 One paper <strong>Orochi</strong> was accepted by <strong>NeurlPS</strong> as Spotlight (CCF-A).</p>
	    <p>[05.2025] 📕 I am selected for the “<strong>Endeavor Scholarship — Integrated Circuit Talent Development Program</strong>” of <strong>China Education Development Foundation</strong> (93 recipients nationwide).</p>
	    <p>[05.2025] 🎉 One paper <strong>INIF</strong> was accepted by <strong>Nature Computational Science</strong> (CAS-Q1).</p>
	    <p>[05.2025] 🎉 One paper <strong>UTMP</strong> was accepted by <strong>IEEE TMC</strong> (CCF-A) as first author.</p>
	    <p>[05.2025] 🎉 One paper <strong>EVA</strong> was accepted by <strong>ICML 2025</strong> (CCF-A).</p>
	    <p>[04.2025] 🎉 One paper <strong>FBQuant</strong> was accepted by <strong>IJCAI 2025</strong> (CCF-A).</p>
	    <p>[04.2025] 🎉 One paper <strong>RepCaM++</strong> was accepted by <strong>IEEE TMC</strong> (CCF-A) as first author.</p>
	    <p>[03.2025] 💻 <strong>PAT</strong> (AAAI'25) has been applied to Samsung’s on-device applications for smartphones and TVs.</p>
	    <p>[01.2025] 📕 I am selected for the First session “<strong>Young Talent Support Project Doctoral Special Program</strong>” of <strong>China Association for Science and Technology</strong> (3,226 recipients nationwide)</p>
	    <p>[12.2024] 🎉 One paper <strong>BEVUDA++</strong> was accepted by <strong>IEEE TCSVT</strong> (CAS-Q1) as first author.</p>
	    <p>[12.2024] 🎉 One paper <strong>PAT</strong> was accepted by <strong>AAAI 2025</strong> (CCF-A).</p>
	    <p>[12.2024] 🏅 I was named <strong>"Outstanding Ph.D. Candidate"</strong> by NJU.</p>
	    <p>[11.2024] 💰 I was offered <strong>"Bank of Jiangsu"</strong> Scholarship from NJU.</p>
	    <p>[09.2024] 💻 The Panasonic Corporation is integrating the <strong>VeCAF</strong> (MM'24) into its actual business operations.</p>
	    <p>[08.2024] 💼 I joined the Beijing Academy of Artificial Intelligence supervised by <a class="blue-text" href="https://www.shanghangzhang.com/" target="_blank"><strong>Prof. Shanghang Zhang</strong></a>.</p>
	    <p>[07.2024] 🎉 One paper <strong>VeCAF</strong> was accepted by <strong>ACMMM 2024</strong> (CCF-A) as first author.</p>
	    <p>[07.2024] 🎓 I am offered a <strong>dual Ph.D.</strong> at The Hong Kong Polytechnic University supervised by <a class="blue-text" href="https://web.comp.polyu.edu.hk/csdwang/" target="_blank"><strong>Prof. Dan Wang</strong></a>.</p>
	    <p>[05.2024] 🎉 One paper <strong>MuPFL</strong> was accepted by <strong>IEEE TMC</strong> (CCF-A) as first author.</p>
	    <p>[04.2024] 📕 Our project: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation, has been selected as one of the <strong>Jiangsu Province Graduate Research and Practical Innovation Projects</strong>.</p>
	    <p>[03.2024] 💻 The Panasonic Corporation is integrating the <strong>MoFME</strong> (AAAI'24) into its actual business operations.</p>
	    <p>[01.2024] 🎉 One paper <strong>BEVUDA</strong> was accepted by <strong>IEEE ICRA 2024</strong> (CCF-B) as first author.</p>
	    <p>[12.2023] 🎉 One paper <strong>MoFME</strong> was accepted by <strong>AAAI 2024</strong> (CCF-A) as first author.</p>
	    <p>[08.2023] 🏅 We won <strong>2nd place</strong> in the SHIFT Challenge 2023 - Continuous Test-time Adaptation for Semantic Segmentation in the challenges of VCL Workshop, ICCV2023.</p>
	    <p>[06.2023] 🎓 I joined the ISCL lab at <strong>Nanjing University</strong> and the HMI Lab of the NATIONAL ENGINEERING RESEARCH CENTER OF VISUAL TECHNOLOGY at <strong>Peking University</strong> as a joint Ph.D. student.</p>
	    <p>[03.2023] 🎓 I received <strong>M.Phil.</strong> degree from <strong>The Chinese University of Hong Kong, Shenzhen</strong></p>
	    <p>[03.2023] 🎉 One paper <strong>RepCaM</strong> was accepted by <strong>ACM NOSSDAV 2023</strong> (CCF-B) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>CdFed</strong> was accepted by <strong>IEEE ICME 2023</strong> (CCF-B) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>FedFHN</strong> was accepted by <strong>IEEE Network</strong> (CAS-Q2) as first author.</p>
	    <p>[03.2023] 🎉 One paper <strong>FedAB</strong> was accepted by <strong>IEEE IoTJ</strong> (CAS-Q1).</p>
	    <p>[03.2023] 🎉 Two papers <strong>BEVSAN</strong> and <strong>CDCCA</strong> were accepted by <strong>IEEE CVPR 2023</strong> (CCF-A).</p>
	    <p>[09.2022] 💼 I joined <strong>OPPO Research</strong> as a Research Intern.</p>
	    <p>[08.2021] 🎓 I joined INML lab at <strong>The Chinese University of Hong Kong, Shenzhen</strong> as an <strong>M.Phil.</strong> student.</p>
	  </div>
	</div>
 
<br>
<br>

# 📝 Publications 
## 📒 Selected publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'2026</div><img src='images/moase.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Decomposing the Neural: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation**

- **Rongyu Zhang**, Aosong Cheng, Yulin Luo, Gaole Dai, Huanrui Yang, Jiaming Liu, Ran Xu, Li Du, Dan Wang, Yuan Du
- The AAAI Conference on Artificial Intelligence <br><strong>(AAAI|<img src="https://img.shields.io/badge/CCF-A-red">)</strong>, 2026.
- [[Paper]](https://arxiv.org/pdf/2405.16486) [[Code] ![](https://img.shields.io/github/stars/RoyZry98/MoASE-Pytorch?style=social)](https://github.com/RoyZry98/MoASE-Pytorch)<font color="red">[Oral Presentation]</font>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'2026</div><img src='images/mole.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MoLe-VLA: Dynamic Layer-skipping Vision Language Action Model via Mixture-of-Layers for Efficient Robot Manipulation**

- **Rongyu Zhang**, Menghang Dong, Yuan Zhang, Liang Heng, Xiaowei Chi, Gaole Dai, Li Du, Dan Wang, Yuan Du, Shanghang Zhang
- The AAAI Conference on Artificial Intelligence <br><strong>(AAAI|<img src="https://img.shields.io/badge/CCF-A-red">)</strong>, 2026.
- [[Paper]](https://arxiv.org/abs/2503.20384) [[Code] ![](https://img.shields.io/github/stars/RoyZry98/MoLe-VLA-Pytorch?style=social)](https://github.com/RoyZry98/MoLe-VLA-Pytorch)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMC'2025</div><img src='images/tmc_repcam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**RepCaM++: Exploring Transparent Visual Prompt with Inference-time Re-parameterization for Neural Video Delivery**

- **Rongyu Zhang**, Xize Duan, Jiaming Liu, Li Du, Yuan Du, Dan Wang, Shanghang Zhang, Fangxin Wang
- IEEE Transactions on Mobile Computing <br><strong>(TMC|<img src="https://img.shields.io/badge/CCF-A-red">)</strong>, 2025.
- [[Paper]](https://www.computer.org/csdl/journal/tm/5555/01/10949820/25DZuw4IHTy) [[Code] ![](https://img.shields.io/github/stars/RoyZry98/RepCaM-Pytorch?style=social)](https://github.com/RoyZry98/RepCaM-Pytorch)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM'2024</div><img src='images/mm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**VeCAF: Vision-language Collaborative Active Finetuning with Training Objective Awareness**

- **Rongyu Zhang**, Zefan Cai, Huanrui Yang, Zidong Liu, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Baobao Chang, Yuan Du, Li Du, Shanghang Zhang
- ACM International Conference on Multimedia <br><strong>(MM|<img src="https://img.shields.io/badge/CCF-A-red">)</strong>, 2024.
- [[Paper]](https://dl.acm.org/doi/abs/10.1145/3664647.3681135) [[Code] ![](https://img.shields.io/github/stars/RoyZry98/VeCAF-Pytorch?style=social)](https://github.com/RoyZry98/VeCAF-Pytorch)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'2024</div><img src='images/aaai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
	
**Efficient Deweather Mixture-of-Experts with Uncertainty-aware Feature-wise Linear Modulation**

- **Rongyu Zhang**, Yulin Luo, Jiaming Liu, Huanrui Yang, Zhen Dong, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Yuan Du, Shanghang Zhang
- The AAAI Conference on Artificial Intelligence <br><strong>(AAAI|<img src="https://img.shields.io/badge/CCF-A-red">)</strong>, 2024.
- [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/download/29622/31055) [[Code] ![](https://img.shields.io/github/stars/RoyZry98/MoFME-Pytorch?style=social)](https://github.com/RoyZry98/MoFME-Pytorch)
</div>
</div>

## 📚 Full publications
*: Equal Contribution. <br>
CCF-A/CAS-Q1 as First-author: <venue>AAAI</venue>x 3, <venue>ACM MM</venue>x 1, <venue>TMC</venue>x 3, <venue>TCSVT</venue>x 1 <br><br>

<button class="filter" type="button" onclick="filterPub('All')" style="--color: #000; --border: #000">All</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('First-authored')">First author</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('Efficiency')">Efficiency</button>&nbsp;
<button class="filter" type="button" onclick="filterPub('Generalization')">Generalization</button>&nbsp;


<ul id="publications">
		<li first_authored=true category="Generalization">
        <venue>AAAI'26</venue><pt>Decomposing the Neural: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation</pt><br>
        <b>Rongyu Zhang*</b><g>, Aosong Cheng*, Yulin Luo*, Gaole Dai, Huanrui Yang, Jiaming Liu, Ran Xu, Li Du, Dan Wang, Yuan Du</g> <br />
	AAAI Conference on Artificial Intelligence<br />
        <p>
			<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2405.16486" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/MoASE-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/MoASE-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
		<font color="red">[Oral Presentation]</font>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>AAAI'26</venue><pt>MoLe-VLA: Dynamic Layer-skipping Vision Language Action Model via Mixture-of-Layers for Efficient Robot Manipulation</pt><br>
        <b>Rongyu Zhang*</b><g>, Menghang Dong*, Yuan Zhang*, Liang Heng, Xiaowei Chi, Gaole Dai, Li Du, Dan Wang, Yuan Du, Shanghang Zhang</g> <br />
	AAAI Conference on Artificial Intelligence<br />
        <p>
			<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="http://arxiv.org/abs/2503.20384" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/MoLe-VLA-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/MoLe-VLA-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Generalization">
        <venue>NIPS'25</venue><pt>Orochi: Versatile Biomedical Image Processor</pt><br>
        <g>Gaole Dai, Chenghao Zhou, Yu Zhou, </g><b>Rongyu Zhang</b><g>, Yuan Zhang, Chengkai Hou, Tiejun Huang, Jianxu Chen, Shanghang Zhang</g> <br />
		Neural Information Processing Systems <br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2509.22583" class="button-59">PDF</a>
            <a href="https://github.com/daviddaiiiii/Orochi-Versatile-Biomedical-Image-Processor" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/daviddaiiiii/Orochi-Versatile-Biomedical-Image-Processor?style=social" class="star-badge" alt="GitHub Stars">
		<font color="red">[Spotlight]</font>
        </p>
    </li>
    <li category="Efficiency">
        <venue>NCS'24</venue><pt>Implicit Neural Image Field for Biological Microscopy Image Compression</pt><br>
        <g>Gaole Dai, </g><b>Rongyu Zhang*</b><g>, Cheng-Ching Tseng*, Qingpo Wuwu*, Shaokang Wan*, Ming Lu, Tiejun Huang, Yu Zhou, Ali Ata Tuz, Matthias Gunzer, Jianxu Chen, Shanghang Zhang</g> <br />
		Nature Computational Science<br />
        <p>
		<img src="https://img.shields.io/badge/CAS-Q1-red">
            <a href="http://arxiv.org/abs/2405.19012" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/INIF-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/INIF-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue>TMC'25</venue><pt>Unimodal Training-Multimodal Prediction: Cross-modal Federated Learning with Hierarchical Aggregation</pt><br>
        <b>Rongyu Zhang</b><g>, Xiaowei Chi, Wenyi Zhang, Guiliang Liu, Dan Wang, Fangxin Wang</g> <br />
		IEEE Transactions on Mobile Computing<br />
        <p>
	    <img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2303.15486" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li category="Generalization">
        <venue>ICML'25</venue><pt>EVA: An Embodied World Model for Future Video Anticipation</pt><br>
        <g>Xiaowei Chi, Hengyuan Zhang, Chun-Kai Fan, Xingqun Qi, </g><b>Rongyu Zhang</b><g>, Anthony Chen, Chi-min Chan, Wei Xue, Wenhan Luo, Shanghang Zhang, Yike Guo</g> <br />
		International Conference on Machine Learning<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2405.16486" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/EmbodiedVideoAnticipator" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/litwellchi/EmbodiedVideoAnticipator?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Efficiency">
        <venue>IJCAI'25</venue><pt>FBQuant: FeedBack Quantization for Large Language Models</pt><br>
        <g>Yijiang Liu, Hengyu Fang, Liulu He, </g><b>Rongyu Zhang</b><g>, Yichuan Bai, Yuan Du, Li Du</g><br />
		International Joint Conference on Artificial Intelligence<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2501.16385" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>TMC'25</venue><pt>RepCaM++: Exploring Transparent Visual Prompt with Inference-time Re-parameterization for Neural Video Delivery</pt><br>
        <b>Rongyu Zhang</b><g>, Xize Duan, Jiaming Liu, Li Du, Yuan Du, Dan Wang, Shanghang Zhang, Fangxin Wang</g><br>
		IEEE Transactions on Mobile Computing<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
		<a href="https://www.computer.org/csdl/journal/tm/5555/01/10949820/25DZuw4IHTy" class="button-59">PDF</a>
		<a class="button-59" href="https://github.com/RoyZry98/RepCaM-Pytorch">Code</a>
		<img src="https://img.shields.io/github/stars/RoyZry98/RepCaM-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Efficiency">
        <venue>AAAI'25</venue><pt>PAT: Pruning-Aware Tuning for Large Language Models</pt><br>
        <g>Yijiang Liu, Huanrui Yang, Youxin Chen, </g><b>Rongyu Zhang</b><g>, Miao Wang, Yuan Du, Li Du</g><br />
		AAAI Conference on Artificial Intelligence<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/abs/2006.04558" class="button-59">PDF</a>
	    <a href="https://github.com/kriskrisliu/PAT" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/kriskrisliu/PAT?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue>TCSVT'25</venue><pt>BEVUDA++: Geometric-aware Unsupervised Domain Adaptation for Multi-View 3D Object Detection</pt><br>
        <b>Rongyu Zhang</b><g>, Jiaming Liu, Xiaoqi Li, Xiaowei Chi, Dan Wang, Li Du, Yuan Du, Shanghang Zhang</g><br>
		IEEE Transactions on Circuits and Systems for Video Technology<br />
        <p>
		<img src="https://img.shields.io/badge/CAS-Q1-red">
		<a href="https://ieeexplore.ieee.org/document/10816404" class="button-59">PDF</a>
		<a class="button-59" href="https://github.com/liujiaming1996/BEVUDA">Code</a>
		<img src="https://img.shields.io/github/stars/liujiaming1996/BEVUDA?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>AAAI‘24</venue><pt>Efficient Deweather Mixture-of-Experts with Uncertainty-aware Feature-wise Linear Modulation</pt><br>
	<b>Rongyu Zhang</b><g>, Yulin Luo, Jiaming Liu, Huanrui Yang, Zhen Dong, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Yuan Du, Shanghang Zhang</g><br>
		AAAI Conference on Artificial Intelligence<br />
        <p>
	    <img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://ojs.aaai.org/index.php/AAAI/article/download/29622/31055" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/MoFME-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/MoFME-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>MM'24</venue><pt>VeCAF: Vision-language Collaborative Active Finetuning with Training Objective Awareness</pt><br>
        <b>Rongyu Zhang*</b><g>, Zefan Cai*, Huanrui Yang*, Zidong Liu, Denis Gudovskiy, Tomoyuki Okuno, Yohei Nakata, Kurt Keutzer, Baobao Chang, Yuan Du, Li Du, Shanghang Zhang</g><br />
		ACM International Conference on Multimedia<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://arxiv.org/pdf/2401.07853" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98/VeCAF-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/VeCAF-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Generalization">
	<venue>TMC'24</venue><pt>Multi-level Personalized Federated Learning on Heterogeneous and Long-Tailed Data</pt><br>
	<b>Rongyu Zhang</b><g>, Yun Chen, Chenrui Wu, Fangxin Wang, Bo Li</g><br>
	IEEE Transactions on Mobile Computing<br />
	<p>
		<img src="https://img.shields.io/badge/CCF-A-red">
		<a class="button-59" href="https://arxiv.org/pdf/2405.06413">PDF</a>
		<a class="button-59" href="https://github.com/RoyZry98">Code</a>
	</p>
    </li>
    <li first_authored=true category="Generalization">
        <venue>ICRA'24</venue><pt>BEVUDA: Multi-geometric Space Alignments for Domain Adaptive BEV 3D Object Detection</pt><br>
        <g>Jiaming Liu*, </g><b>Rongyu Zhang*</b><g>, Xiaowei Chi, Xiaoqi Li, Ming Lu, Yandong Guo, Shanghang Zhang</g><br />
		International Conference on Robotics and Automation<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-B-blue">
            <a href="https://arxiv.org/pdf/2211.17126" class="button-59">PDF</a>
	    <a class="button-59" href="https://github.com/liujiaming1996/BEVUDA">Code</a>
	    <img src="https://img.shields.io/github/stars/liujiaming1996/BEVUDA?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>Noss'23</venue><pt>RepCaM: Re-parameterization Content-aware Modulation for Neural Video Delivery</pt><br>
        <b>Rongyu Zhang*</b><g>, Lixuan Du*, Jiaming Liu*, Congcong Song, Fangxin Wang, Xiaoqi Li, Ming Lu, Yandong Guo, Shanghang Zhang</g><br />
		ACM Network and Operating System Support for Digital Audio and Video<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-B-blue">
            <a href="https://dl.acm.org/doi/pdf/10.1145/3592473.3592567" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98/RepCaM-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/RepCaM-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
	    <font color="red">[Oral Presentation]</font>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>ICME'23</venue><pt>Cluster-driven GNN-based Federated Recommendation System with Biased Message Dropout</pt><br>
        <b>Rongyu Zhang*</b><g>, Yun Chen*, Chenrui Wu, Fangxin Wang</g><br />
		IEEE International Conference on Multimedia and Expo.<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-B-blue">
            <a href="https://ieeexplore.ieee.org/abstract/document/10219619" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue>Netw'23</venue><pt>Optimizing Efficient Personalized Federated Learning with Hypernetworks at Edge</pt><br>
        <b>Rongyu Zhang</b><g>, Yun Chen, Chenrui Wu, Fangxin Wang, Jiangchuan Liu</g><br />
		IEEE Network<br />
        <p>
		<img src="https://img.shields.io/badge/CAS-Q3-green">
            <a href="https://arxiv.org/pdf/2211.17126" class="button-59">PDF</a>
            <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li category="Generalization">
        <venue>CVPR'23</venue><pt>Cloud-Device Collaborative Adaptation to Continual Changing Environments in the Real-world</pt><br>
        <g>Yulu Gan, Mingjie Pan, </g><b>Rongyu Zhang</b><g>, Zijian Ling, Lingran Zhao, Jiaming Liu, Shanghang Zhang</g><br />
		The IEEE/CVF Conference on Computer Vision and Pattern Recognition<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Pan_Cloud-Device_Collaborative_Adaptation_to_Continual_Changing_Environments_in_the_Real-World_CVPR_2023_paper.pdf" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li category="Generalization">
        <venue>CVPR'23</venue><pt>BEV-SAN: Accurate BEV 3D Object Detection via Slice Attention Networks</pt><br>
        <g>Xiaowei Chi, Jiaming Liu, Ming Lu, </g><b>Rongyu Zhang</b><g>, Zhaoqing Wang, Yandong Guo, Shanghang Zhang</g><br />
		The IEEE/CVF Conference on Computer Vision and Pattern Recognition<br />
        <p>
		<img src="https://img.shields.io/badge/CCF-A-red">
            <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Chi_BEV-SAN_Accurate_BEV_3D_Object_Detection_via_Slice_Attention_Networks_CVPR_2023_paper.pdf" class="button-59">PDF</a>
	    <a href="https://github.com/litwellchi/BEV-SAN" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/litwellchi/BEV-SAN?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Efficiency">
        <venue>IoTJ'23</venue><pt>FedAB: Truthful Federated Learning with Auction-based Combinatorial Multi-armed Bandit</pt><br>
        <g>Chenrui Wu, Yifei Zhu, </g><b>Rongyu Zhang</b><g>, Yun Chen, Fangxin Wang, Shuguang Cui</g><br />
		IEEE Internet of Things Journal<br />
        <p>
		<img src="https://img.shields.io/badge/CAS-Q2-blue">
            <a href="https://ieeexplore.ieee.org/abstract/document/10092911" class="button-59">PDF</a>
	    <a href="https://github.com/RoyZry98" class="button-59">Code</a>
        </p>
    </li>
    <li first_authored=true category="Efficiency">
        <venue1>arXiv'25</venue1><pt>T-REX: Mixture-of-Rank-One-Experts with semantic-aware Intuition for Multi-task Large Language Model Finetuning</pt><br>
        <b>Rongyu Zhang*</b><g>, Yijiang Liu*, Huanrui Yang*, Shenli Zheng, Chongkang Tan, Dan Wang, Yuan Du, Li Du, Shanghang Zhang</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2404.08985" class="button-59">PDF</a>
             <a href="https://github.com/RoyZry98/T-REX-Pytorch" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/RoyZry98/T-REX-Pytorch?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li first_authored=true category="Generalization">
        <venue1>arXiv'24</venue1><pt>M2Chat: Empowering VLM for Multimodal LLM Interleaved Text-Image Generation</pt><br>
        <g>Xiaowei Chi*, </g><b>Rongyu Zhang*</b><g>, Zhengkai Jiang, Yijiang Liu, Yatian Wang, Xingqun Qi, Wenhan Luo, Peng Gao, Shanghang Zhang, Qifeng Liu, Yike Guo</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2311.17963" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/M2Chat" class="button-59">Code</a>
		<img src="https://img.shields.io/github/stars/litwellchi/M2Chat?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
    <li category="Generalization">
        <venue1>arXiv'24</venue1><pt>ViML: A Video, Music, Language Unified Dataset for Understanding and Generation</pt><br>
        <g>Xiaowei Chi, Aosong Chen, Pengjun Fang, Yatian Wang, Zeyue Tian, Yingqing He, Zhaoyang Liu, Xingqun Qi, </g><b>Rongyu Zhang</b><g>, Mengfei Li, Jiahao Pan, Yanbing Jiang, Wei Xue, Wenhan Luo, Qifeng Chen, Shanghang Zhang, Qifeng Liu, Yike Guo</g> <br />
        <p>
            <a href="https://arxiv.org/pdf/2407.20962" class="button-59">PDF</a>
            <a href="https://github.com/litwellchi/MMTrail" class="button-59">Code</a>
	    <img src="https://img.shields.io/github/stars/litwellchi/MMTrail?style=social" class="star-badge" alt="GitHub Stars">
        </p>
    </li>
</ul>
  
<br>

<!-- <span class='anchor' id='honors-and-awards'></span>

# 🥇 Honors and Awards
Lead PI Project:
- *(2025.05)*: &nbsp;The third "Youth Student Basic Research Program (Ph.D. Candidate): Edge–cloud collaborative generalization and compression mechanisms for multimodal large models" with 300,000¥, National Natural Science Foundation of China (国家自然科学基金委青年学生基础研究项目（博士研究生）：多模态大模型端云协同泛化压缩机制研究)
- *(2025.05)*: &nbsp;The “Endeavor Scholarship — Integrated Circuit Talent Development Program” with 100,000¥  (93 recipients nationwide), China Education Development Foundation (中国教育发展基金会“奋进奖学金—集成电路人才培养”项目；全国93人入选)
- *(2025.01)*: &nbsp;The First Session “Young Talent Support Project Doctoral Special Program” with 40,000¥ (3,226 recipients nationwide), China Association for Science and Technology (首届中国科协“青年人才托举工程博士生专项”计划；全国3,226人入选)
- *(2024.05)*: &nbsp;Jiangsu Province Graduate Research and Practical Innovation Project “Mixture-of-Activation-Sparsity-Experts for Continuous Test-time Adaptation” with 15,000¥, Jiangsu Provincial Department of Education (江苏省"研究生科研与实践创新"计划)

Awards:
- *(2025.09)*: &nbsp;Hong Kong Post-Graduate Scholarship (HKPGS) with 18,840¥/month, The Hong Kong Polytechnic University
- *(2024.12)*: &nbsp;Outstanding Ph.D. Candidate with 2,000¥/year, Nanjing University
- *(2024.12)*: &nbsp;"Bank of Jiangsu" Scholarship with 5,000¥, Nanjing University
- *(2023.10)*: &nbsp;The 2nd place of the SHIFT Challenge 2023 - Continuous Test-time Adaptation for Semantic Segmentation in the challenges of VCL Workshop with 2,000$, International Conference on Computer Vision

<br> -->

<span class="anchor" id="grants-and-projects"></span>
# 💰 Grants and Projects
<div class="row">
  <div class="col-12 col-lg-8">

    <div class="description">
      <ul class="ul-edu fa-ul mb-0">
        <!-- 条目 1 -->
        <li>
          <i class="fa-li fas fa-clipboard-list" aria-hidden="true"></i>
          <strong class="highlight-text">NSFC Youth Student Basic Research Program (Ph.D. Candidate):</strong>
          “Edge–cloud collaborative generalization and compression mechanisms for multimodal large models”
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">国家自然科学基金委青年学生基础研究项目（博士研究生）：</strong>
              多模态大模型端云协同泛化压缩机制研究
            </p>
          </div>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">Lead PI ▪️</strong>
              <span class="middot-divider-big"></span>
              <span class="nowrap">300,000¥ ▪️</span>
              <span class="middot-divider-big"></span>
              January 2026 - December 2027
            </p>
          </div>
        </li>

        <!-- 条目 2 -->
        <li>
          <i class="fa-li fas fa-clipboard-list" aria-hidden="true"></i>
          <strong class="highlight-text">CEDF “Endeavor Scholarship — Integrated Circuit Talent Development” Program</strong>
          <i> (93 recipients nationwide)</i>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">中国教育发展基金会“奋进奖学金—集成电路人才培养”项目</strong>
              （全国93人入选）
            </p>
          </div>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">Awardee ▪️</strong>
              <span class="middot-divider-big"></span>
              <span class="nowrap">100,000¥ ▪️</span>
              <span class="middot-divider-big"></span>
              May 2025
            </p>
          </div>
        </li>

        <!-- 条目 3 -->
        <li>
          <i class="fa-li fas fa-clipboard-list" aria-hidden="true"></i>
          <strong class="highlight-text">CAST Young Talent Support Project — Doctoral Special Program</strong>
          <i> (3,226 recipients nationwide)</i>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">中国科协青年人才托举工程博士生专项</strong>
              （全国3,226人入选）
            </p>
          </div>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">Awardee ▪️</strong>
              <span class="middot-divider-big"></span>
              <span class="nowrap">40,000¥ ▪️</span>
              <span class="middot-divider-big"></span>
              January 2025 - December 2026
            </p>
          </div>
        </li>

        <!-- 条目 4 -->
        <li>
          <i class="fa-li fas fa-clipboard-list" aria-hidden="true"></i>
          <strong class="highlight-text">Jiangsu Province Graduate Research and Practical Innovation Project:</strong>
          “Mixture-of-Activation-Sparsity-Experts for Continuous Test-time Adaptation”
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">江苏省“研究生科研与实践创新”计划：</strong>
              连续测试时自适应的激活稀疏专家混合模型
            </p>
          </div>
          <div class="article-metadata">
            <p>
              <strong class="highlight-text">PI Lead ▪️</strong>
              <span class="middot-divider-big"></span>
              <span class="nowrap">15,000¥ ▪️</span>
              <span class="middot-divider-big"></span>
              May 2024 - May 2025
            </p>
          </div>
        </li>
      </ul>
    </div>

  </div>
</div>

# 🥇 Honors and Awards
- *(2025.09)*: &nbsp;Hong Kong Post-Graduate Scholarship (HKPGS) with 18,840¥/month, The Hong Kong Polytechnic University
- *(2024.12)*: &nbsp;Outstanding Ph.D. Candidate with 2,000¥/year, Nanjing University
- *(2024.12)*: &nbsp;"Bank of Jiangsu" Scholarship with 5,000¥, Nanjing University
- *(2023.10)*: &nbsp;The 2nd place of the SHIFT Challenge 2023 - Continuous Test-time Adaptation for Semantic Segmentation in the challenges of VCL Workshop with 2,000$, International Conference on Computer Vision

<br>

<span class='anchor' id='services'></span>

# 💼 Services
#### Journal reviewer
- IEEE Transactions on Mobile Computing (TMC)
- IEEE Transactions on Computers (TC)
- IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
- IEEE Transactions on Dependable and Secure Computing  (TDSC)
- IEEE Internet of Things Journal (IoTJ)
- IEEE Transactions on Communications (TCOM)
- IEEE Network Magazine (Network)

#### Conference reviewer
- IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2025
- ACM International Conference on Multimedia (MM) 2024, 2025
- IEEE/CVF International Conference on Computer Vision (ICCV) 2023, 2025
- Annual Conference on Neural Information Processing Systems (NeurIPS) 2025
- The Fortieth AAAI Conference on Artificial Intelligence (AAAI) 2026

<br>

<span class='anchor' id='internships'></span>

# 💻 Internships
- **Beijing Academy of Artificial Intelligence** (2024.08-2024.11) Research Intern, supervised by [Prof. Shanghang Zhang](https://www.shanghangzhang.com/) 
- **OPPO Research Institute** (2022.09-2023.03) Research Intern, supervised by [Dr. Yandong Guo](https://scholar.google.com/citations?user=fWDoWsQAAAAJ&hl=zh-CN) 
- **LENOVO Research Institute** (2020.11-2021.05) Research Intern, supervised by [Prof. Jiangtao Gong](https://scholar.google.com/citations?user=AktmI14AAAAJ&hl=zh-CN&oi=ao)

<br>

<span class='anchor' id='talks'></span>

# 🎤 Talks
- 'Research on Key Technologies for Improving the Performance and Efficiency of On-device Models Based on Mixture-of-Experts' @ The Chinese University of Hong Kong, Shenzhen, invited by Prof. Fangxin Wang (2025.08.05) [Slides](assets/cuhksz_talk.pptx)

<br>

<span class='anchor' id='teaching'></span>

# 🧑‍🏫 Teaching
Teaching Assistant at PolyU
- COMP 6704: Advanced Machine Learning

<br>

<span class='anchor' id='miscellaneous'></span>

# 😄 Miscellaneous
<div class="highlight-blocks">
  <div class="highlight-block">
    <h3>❤️ Family</h3>
    <ul>
      <img src="images/qiaoqiao.jpg" alt="family Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
     <br>
	    <li>I have a beautiful girlfriend, <a href='https://scholar.google.com/citations?user=G_BypiwAAAAJ&hl=zh-CN&oi=ao'>Ziqi Qiao</a>, who is also a Ph.D. student at Peking University. We also own an adorable cat 🐱 named QiuQiu. He brings us tremendous fun and happiness.</li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>🧑‍🤝‍🧑 Friends</h3>
    <ul>
	<img src="images/friends.png" alt="friend Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
      <br>
	    <li>My closest academic friends: <a href='https://liujiaming1996.github.io/'>Jiaming Liu</a>, <a href='https://scholar.google.com/citations?user=SgeV4NkAAAAJ&hl=zh-CN&oi=ao'>Yulin Luo</a>, <a href='https://gumpest.github.io/'>Yuan Zhang</a>, and <a href='https://scholar.google.com/citations?user=2Of6xZUAAAAJ&hl=zh-CN'>Gaole Dai</a> from PKU; <a href='https://scholar.google.com/citations?hl=zh-CN&user=Vl1X_-sAAAAJ'>Xiaowei Chi</a> from HKUST; <a href='https://www.liuyijiang.com/'>Yijiang Liu</a> from NJU; <a href='https://wuchenrui.github.io/'>Chenrui Wu</a> from ZJU&SFU; <a href='https://yilijin.github.io/'>Yili Jin</a> and <a href='https://slyfooox666.github.io/Kaiyuan_Hu/'>Kaiyuan Hu</a> from McGill.</li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3>😄 Hobbies</h3>
    <ul>
	<img src="images/football_new.png" alt="hobby Image" style="display: block; margin: auto; max-width: 100%; height: auto;">
      <br>
	    <li>I am a crazy basketball 🏀 & football ⚽️ fan. I enjoy the games of Kevin Durant 🕷️ and Kyrie Irving 🧙. I also wholeheartedly pledge my allegiance to Chelsea Football Club, KTBFFH! 💙</li>
    </ul>
  </div>
</div>

<br>

<!-- <div style="text-align: center;"> -->
<div style="width: 20%; position:relative; left:40%">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=TexC6zB_7AOUKNMMshe4U4igIY-rca8pyS5kiQ7N6C8"></script>
    <!-- 地图小部件代码结束 -->
</div>

