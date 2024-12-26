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

<span class='anchor' id='about-me'></span>

I am currently a master's candidate from the Department of Earth and Space Sciences, Southern University of Science and Technology, Shenzhen China, advised by [Prof. Dikun Yang](https://scholar.lanfanshu.cn/citations?hl=zh-CN&user=BFpLy2cAAAAJ) and expect to be conferred upon Master's degree in 2025.
Over the past three years, I have been engaged in advancing geophysical methods and addressing engineering geophysics issues, including contamination site investigations and karst cave location.

My research interest includes:
- Electrical resistivity tomography (ERT)
- Multichannel analysis of surface waves (MASW) 
- Seismic ambient noise imaging
- Shallow surface geophysics, Environmental issues.

# 🎓 Educations
- 2022.09 - Present, <a href="https://www.sustech.edu.cn/en/"><img class="png" src="images/sustech.png" width="30pt"></a> Southern University of Science and Technology, Shenzhen China (GPA: 3.56/4). 
- 2018.09 - 2022.06, <a href="https://english.yangtzeu.edu.cn/"><img class="png" src="images/Yangtz-512x512.png" width="26pt"></a> Yangtze University, Wuhan China (GPA: 3.73/5, Rank: 4/43). 

# 📝 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024.10 </div><img src='images/MT.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- When conducting a nearshore Magnetotelluric (MT) survey, deploying a magnetometer on the seafloor with long-term waterproofing is quite challenging.
  Additionally, the magnetic field measurements can be significantly impacted by seawater currents and other electromagnetic sources.
- To address these challenges, the MT survey adopted an inter-station pattern as an alternative method. An inter-station acquisition experiment was conducted in Zhanjiang, Guangdong, recording onshore magnetic field data and seafloor electric field data approximately 3 km apart.
- We hired two local fishing boats to acquire seafloor electric signals.  One boat carried an electrode connected by cable to the main ship, manually laying cable as the boat moved and laid the electrode with weights into the seafloor at set locations.  Repeat this process until all four electrodes are set at the bottom of the sea.
- Whereafter, the main boat carrying the MT meter (MTU-5A), maintained a stable location and took measurements according to the pre-set script. Meanwhile, another MT meter recorded onshore magnetic signals simultaneously. After 18 hours of continuous data collection, the equipment was recovered.
- The impedance obtained from inter-station acquisition showed a downward trend in the low-frequency range compared to regular impedance, consistent with previous synthetic simulation results, suggesting its reliability field survey.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023.12 </div><img src='images/2023EastRiver.jpeg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 - ERT was employed to locate potential karst cave areas beneath rivers. This study set up six 700-meter-long ERT survey lines across the East River.
 - Using the specially designed 200-meter underwater cable with 5-meter electrode spacing, a pole-dipole electrode configuration was utilized to conduct observations of the underground structures.
 - The inverted resistivity profiles revealed high-resistance anomalies in the surface layer and bedrock which were interpreted as gravel, pebble, and limestone. Meanwhile, they delineated the spatial distribution of low
   resistance anomalies such as sandstone and conglomerate. 
 - Deploying electrodes in water to observe underground resistivity structure is highly challenging, nevertheless, it will provide guidance significant for subsequent underwater geological structure imaging.
 - more details in [[PDF]](/appendix/wang-et-al-2024-underwater-ert-method-to-image-karst-cave-distribution-below-the-river-water.pdf)     [[PPT]](/appendix/2023ICEG_EastRiverPPT.pdf).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022.12 </div><img src='images/longgangproject.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Because ERT inversion results are highly subject to initial model, using a conventional uniform half-space as the initial model may lead to undesirable or even incorrect results.
  However, ambient noise tomography (ANT) can recover a relative solidity of the underground velocity structure compared to ERT.
- To tackle this challenge, we propose to add seismic data to constrain the ERT inversion. By mapping the images of velocity or H/V spectral ratio (HVSR) onto the resistivity model via empirical formulas,
  and employing it as a model constraint for the ERT inversion, we can alleviate the sensitivity of the results to the initial model.
<!-- - The ERT survey is carried out along a line of 40 electrodes with a spacing of 5m. At the same time, we place 81 nodal seismic stations to continuously collect 1-hour ambient seismic noise. -->
- A field survey demonstrates that ERT inversion with seismic constraint not only confirms the general distribution of the three cavities but also provides higher resolution compared to regular inversion.
- more details in [[PDF]](/appendix/2023SEG_abstract.pdf) [[PPT]](/appendix/2023SEGPPT.pdf).

</div>
</div>

# 💬 Presentations
- <p>
  <span style="background-color: #F8FAFC; color: #AA5486; padding: 0 3px;"><strong>Poster</strong></span>: <span style="background-color: #F2F9FF; color: #474E93; padding: 0 3px;"><strong>Interpreting Cross-river Underwater Electric Resistivity Data for Dam Construction: Lessons Learned from 2D and 3D Inversions.</strong></span><br>
  <span class="underline">Daopu Wang,</span>
  Dikun Yang, The International Meeting for Applied Geoscience and Energy <a href="https://www.imageevent.org/" target="_blank" rel="noopener noreferrer">(IMAGE2024)</a>, August 26-30, 2024, Houston, Texas, USA.</p>
- <p>
  <span style="background-color: #F8FAFC; color: #AA5486; padding: 0 3px;"><strong>Oral</strong></span>: <span style="background-color: #F2F9FF; color: #474E93; padding: 0 3px;"><strong>Development and Application of Joint Nodal Acquisition Stations for Seismic and ERT Data.</strong></span><br>
 <span class="underline">Daopu Wang,</span>
  Dikun Yang, The International Meeting for Applied Geoscience and Energy <a href="https://ess.sustech.edu.cn/iceeg2024/" target="_blank" rel="noopener noreferrer">(11th ICEEG)</a>, June 27-30, 2024, Shenzhen, China.</p>
- <p>
  <span style="background-color: #F8FAFC; color: #AA5486; padding: 0 3px;"><strong>Oral</strong></span>: <span style="background-color: #F2F9FF; color: #474E93; padding: 0 3px;"><strong>Underwater ERT Method to Image Karst Cave Distribution Below the River Water.</strong></span><br>
  <span class="underline">Daopu Wang,</span>
  Haibin Chai, Dikun Yang, The Seventh International Conference on Engineering Geophysics <a href="https://conferences.uaeu.ac.ae/iceg2023/en/" target="_blank" rel="noopener noreferrer">(7th ICEG)</a>, October 16-19, 2023, AI Ain, UAE.</p>
- <p>
  <span style="background-color: #F8FAFC; color: #AA5486; padding: 0 3px;"><strong>Oral</strong></span>: <span style="background-color: #F2F9FF; color: #474E93; padding: 0 3px;"><strong>Electric Resistivity Tomography Inversion Guided by Passive Microtremor Data for Detection of Karst Cavities.</strong></span><br>
  <span class="underline">Daopu Wang,</span>
  Dikun Yang, Zhentao Yang, The International Meeting for Applied Geoscience and Energy <a href="https://www.imageevent.org/" target="_blank" rel="noopener noreferrer">(IMAGE2023)</a>, August 26-30, 2023, Houston, Texas, USA.</p>

# 🎖 Fellowships and Awards
<ul>
  <li>2023.10 The <span class="highlight">Third Prize</span> in the Eighth National College Students "Innovation Cup" Geophysical Knowledge Competition
  <strong>(￥1000)</strong>. 
   <a href="https://newshub.sustech.edu.cn/html/202306/43985.html" target="_blank" rel="noopener noreferrer">Newsreport</a>
  </li>
  <li>2021.09 The <span class="highlight">Second Prize</span> in the Seventh National College Students "Innovation Cup" Geophysical Knowledge Competition.</li>
  <li>2019.12 The <span class="highlight">National Encouragement Scholarship</span><strong>(￥5000)</strong>.</li>
</ul>

# 🧸 Societies
- *2024.08*, Volunteer at the International Meeting for Applied Geoscience and Energy, Houston, Texas, USA`(IMAGE2024).` 
- *2024.06*, Volunteer at the 11th International Conference on Environmental and Engineering Geophysics, Shenzhen, China `(ICEEG2024).`
- *2024.05*, Volunteer at the International Workshop on Gravity, Electrical & Magnetic Methods and Their Applications, Shenzhen, China`(GEM2024).`
- *2023.08*, Volunteer at the 16th China International Geo-electromagnetism Workshop, Shenzhen, China `(CIGEW2023).`
- *2023.06 - 2023.09,* Seminar Assistant at the Department of Earth and Space Sciences in SUSTechm Shenzhen, China. 

# 🏄 Skills and Languages
- **Programming**: Python, Matlab, Jekyll, Linux, etc.
- **Software**: SimPEG, SSMT2000, SAC, Adobe (Photoshop, Lightroom), Cartopy, Disba, etc.
- **Instruments**: SmartSolo Geophone, Phoenix System MTU-5A, Multi-channel Electrical System GD-20, RTK, etc.
- **Language**: Mandarin (Native), English (IELTS 6.5).

# 📷 Interests
- **Sports**: Swimming, Hiking.
- **Photography**: [Photography Portfolio](https://www.xiaohongshu.com/user/profile/5f8ef7ff0000000001002b56) Sometimes I just wanna go out and enjoy the sunshine.
- **Volunteering**: Conferences Volunteering(100+ hours), maintain individual dedication and zest for life first hand.
