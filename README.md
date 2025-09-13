> SIGGRAPH Asia 2025 Conference Paper
<p align="center">
<h1 align="center"><strong>Motion In-Betweening for Densely Interacting Characters</strong></h1>
  <p align="center">
    <a href="https://scholar.google.com/citations?hl=en&user=MHQRNggAAAAJ" target="_blank">Xiaotang Zhang</a><sup>1</sup>,
    <a href="https://scholar.google.com/citations?user=gHhQNlYAAAAJ&hl" target="_blank">Ziyi Chang</a><sup>1</sup>,
    <a href="https://scholar.google.com/citations?user=t1hraiAAAAAJ&hl" target="_blank">Qianhui Men</a><sup>2</sup>,
    <a href="http://hubertshum.com/" target="_blank">Hubert Shum</a><sup>1&dagger;</sup>
    <br>
      <sup>1</sup>Durham University  
      <sup>2</sup>University of Bristol
    <br>
      &dagger; Corresponding Author
  </p>
</p>

<div id="top" align="center">
  
[[Paper]]() [[Video]]() [[arXiv]]()

</div>

![Teaser](/materials/Teaser.png)
### Abstract
Motion in-betweening is the problem to synthesize movement between keyposes. Traditional research focused primarily on single characters. Extending them to densely interacting characters is highly challenging, as it demands precise spatial-temporal correspondence between the characters to maintain the interaction, while creating natural transitions towards predefined keyposes. In this research, we present a method for long-horizon interaction in-betweening that enables two characters to engage and respond to one another naturally. To effectively represent and synthesize interactions, we propose a novel solution called Cross-Space In-Betweening, which models the interactions of each character across different conditioning representation spaces. We further observe that the significantly increased constraints in interacting characters heavily limit the solution space, leading to degraded motion quality and diminished interaction over time. To enable long-horizon synthesis, we present two solutions to maintain long-term interaction and motion quality, thereby keeping synthesis in the stable region of the solution space. We first sustain interaction quality by identifying periodic interaction patterns through adversarial learning. We further maintain the motion quality by learning to refine the drifted latent space and prevent pose error accumulation. We demonstrate that our approach produces realistic, controllable, and long-horizon in-between motions of two characters with dynamic boxing and dancing actions across multiple keyposes, supported by extensive quantitative evaluations and user studies.
