+++
title =  "Van Nguyen Nguyen"
date = 2022-08-25T21:30:04+08:00
img = "/images/nguyen.png"
draft = false
+++

I am a Research Scientist at [United Imaging Intelligence (UII America)](https://www.linkedin.com/company/uii-america-inc/) in Greater Boston, MA, USA.

I completed my PhD at [IMAGINE team](http://imagine.enpc.fr/), [École des Ponts ParisTech](http://www.enpc.fr/), under the supervision of [Prof. Vincent Lepetit](https://vincentlepetit.github.io/). 

My research focuses on 3D computer vision and robotics.

**Our team is always looking for self-motivated research interns. Please drop me a line if you are interested!**

[Email](mailto:vanngn.nguyen@gmail.com)
[CV](/download/cv_nguyen.pdf)
[Scholar](https://scholar.google.com/citations?user=wctJ37UAAAAJ)
[Linkedin](https://www.linkedin.com/in/nv-nguyen/)
[Github](https://github.com/nv-nguyen)

---
## News

<div id="news-container">
  <ul>
    <li>02/2026: <a href="https://arxiv.org/pdf/2512.14126">CIF</a> and <a href="https://arxiv.org/pdf/2512.06581">MedGRPO</a> accepted to CVPR 2026.</li>
    <li>01/2026: <a href="https://arxiv.org/pdf/2510.03312">Universal Beta Splatting</a> accepted to ICLR 2026.</li>
    <li>06/2025: Joined <a href="https://www.linkedin.com/company/uii-america-inc/">United Imaging Intelligence</a> in Burlington, MA as a research scientist.</li>
    <li>06/2025: <a href="https://arxiv.org/pdf/2504.02812">BOP challenge 2024 report</a> received Best Paper Award at CV4MR workshop at CVPR 2025.</li>
    <li>04/2024: <a href="https://arxiv.org/pdf/2504.02812">BOP challenge 2024 report</a> and <a href="https://arxiv.org/pdf/2506.07155">GoTrack</a> accepted to CV4MR workshop at CVPR 2025.</li>
    <li>12/2024: PhD defended!</li>
    <li>06/2024: <a href="https://bop.felk.cvut.cz/challenges/bop-challenge-2024/">BOP challenge 2024</a> opened!</li>
    <li class="older-news" style="display: none;">05/2022: Joined <a href="https://about.facebook.com/realitylabs/">Meta Reality Labs</a> as a research intern with <a href="https://thodan.github.io/">Tomas Hodan</a>.</li>
    <li class="older-news" style="display: none;">04/2024: Accepted to <a href="https://cvpr.thecvf.com/Conferences/2024/CallForDoctoralConsortium">CVPR 2024 Doctoral Consortium</a>.</li>
    <li class="older-news" style="display: none;">04/2024: <a href="https://arxiv.org/pdf/2403.09799.pdf">BOP challenge 2023 report</a> accepted to CVPRW 2024.</li>
    <li class="older-news" style="display: none;">02/2024: <a href="https://arxiv.org/pdf/2311.14155">GigaPose</a>, <a href="https://arxiv.org/pdf/2303.13612">NOPE</a>, <a href="https://arxiv.org/pdf/2404.18873">OSV5M</a> accepted to CVPR 2024.</li>
    <li class="older-news" style="display: none;">10/2023: <a href="https://arxiv.org/abs/2307.11067">CNOS</a> accepted to R6D workshop at ICCV 2023. Awarded best 2D detection method for unseen objects at <a href="https://bop.felk.cvut.cz/challenges/bop-challenge-2023">BOP challenge 2023</a>.</li>
    <li class="older-news" style="display: none;">08/2022: <a href="https://arxiv.org/abs/2209.07589.pdf">PIZZA</a> accepted (as Oral) to 3DV 2022.</li>
    <li class="older-news" style="display: none;">05/2022: Joined <a href="https://about.facebook.com/realitylabs/">Meta Reality Labs</a> as a research intern, working with <a href="https://www.linkedin.com/in/pierre-moulon/">Pierre Moulon</a>.</li>
    <li class="older-news" style="display: none;">03/2022: <a href="https://arxiv.org/abs/2203.17234.pdf">Template-pose</a> accepted to CVPR 2022.</li>
    <li class="older-news" style="display: none;">10/2020: Started PhD at <a href="http://imagine.enpc.fr/">IMAGINE team</a>, advised by <a href="https://vincentlepetit.github.io/">Prof. Vincent Lepetit</a>.</li>
  </ul>
  
  <button id="toggle-news" onclick="toggleOlderNews()" style="margin-top: 10px; padding: 8px 16px; background: #1e70bf; color: white; border: none; border-radius: 20px; cursor: pointer; font-size: 12px; font-family: monospace; transition: background-color 0.3s ease;">Show more</button>
</div>

<script>
function toggleOlderNews() {
  const olderNewsItems = document.querySelectorAll('.older-news');
  const button = document.getElementById('toggle-news');
  
  if (olderNewsItems[0].style.display === 'none') {
    olderNewsItems.forEach(item => {
      item.style.display = 'list-item';
    });
    button.textContent = 'Show less';
  } else {
    olderNewsItems.forEach(item => {
      item.style.display = 'none';
    });
    button.textContent = 'Show more';
  }
}

// Add hover effect
document.addEventListener('DOMContentLoaded', function() {
  const button = document.getElementById('toggle-news');
  if (button) {
    button.addEventListener('mouseenter', function() {
      this.style.backgroundColor = '#0071bc';
    });
    button.addEventListener('mouseleave', function() {
      this.style.backgroundColor = '#1e70bf';
    });
  }
});
</script>

---
## PhD thesis: Pose Estimation of Novel Rigid Objects

**Supervisor**: [Prof. Vincent Lepetit](https://vincentlepetit.github.io/)  
**Reviewers**: [Prof. Markus Vincze](https://www.acin.tuwien.ac.at/en/staff/vm/), [Dr. Benjamin Busam](https://www.cs.cit.tum.de/camp/members/benjamin-busam/)  
**Examiners**: [Prof. Josef Sivic](https://people.ciirc.cvut.cz/~sivic/), [Prof. Dima Damen](https://dimadamen.github.io/), [Dr. Slobodan Ilic](https://campar.in.tum.de/Main/SlobodanIlic)

- [📄 Thesis (PDF)](/download/thesis.pdf)
- [📑 Slides (PDF)](/download/thesis_slide.pdf)

---