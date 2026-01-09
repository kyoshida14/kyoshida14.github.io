---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---

## PhD Research (Brown University)

My PhD research mainly focuses on these research questions:
1. At the local level: How do individual pedestrians interact with/influence each other?
2. At the global level: What types of collective motion patterns emerge from these local interactions?
3. Connecting the two levels: What is the underlying mechanism of how the local interactions scale up to the global collective motion patterns?


### Visual influence networks in walking crowds

We introduced an approach that estimates local influences in observational data on moving human crowds and represents them as spatially-embedded dynamic networks (*visual influence networks*). This method uses a correlation-based measure called Time-Dependent Delayed Correlation (TDDC). See <a href="https://doi.org/10.1371/journal.pcbi.1004089" target="_blank">Giuggioli et al. (2015)</a> and <a href="https://doi.org/10.1038/s41598-020-75551-2" target="_blank">Lombardi et al. (2020)</a>.

![Dynamics of visual influence networks](/images/networks.png){: width="80%" }


We also developed measures to quantify local and global influence strengths of individual pedestrians. We quantitatively showed the front of crowds as the most influential position.

![Heat Map of Local and Global Influence Strengths in Space](/images/influence_heatmap.png){: width="80%" }


Read more about visual influence networks in this preprint: <a href="https://doi.org/10.1101/2025.01.29.635594" target="_blank">https://doi.org/10.1101/2025.01.29.635594</a>.

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    Collective motion in human crowds has been understood as a self-organizing phenomenon that is generated from local visual interactions between neighboring pedestrians. To analyze these interactions, we introduce an approach that estimates local influences in observational data on moving human crowds and represents them as spatially-embedded dynamic networks (visual influence networks). We analyzed data from a human “swarm” experiment (N = 10, 16, 20) in which participants were instructed to walk about the tracking area while staying together as a group. We reconstructed the network every 0.5 seconds using Time-Dependent Delayed Correlation (TDDC). Using novel network measures of local and global leadership (direct influence and branching influence), we find that both measures strongly depend on an individual’s spatial position within the group, yielding similar but distinctive leadership gradients from the front to the back. There was also a strong linear relationship between individual influence and front-back position in the crowd. The results reveal that influence is concentrated in specific positions in a crowd, a fact that could be exploited by individuals seeking to lead collective crowd motion.
  </div>
</details>


### Crowd experiment with assigned leaders (confederates)

In this experiment, we strategically placed **covert** or **explicit** leaders (confederates) at previously shown influential positions in a group of walking pedestrians. We instructed them to change walking direction (heading) on a signal. Participants were either told to follow the crowd (covert) or follow the confederates with flags (explicit), and we tested the confederate influence on collective motion.

![Covert confederates steering a crowd](/images/confederate_steer.png){: width="80%" }

I presented this work in 2024 at <a href="https://tgf2024.sciencesconf.org" target="_blank">Traffic and Granular Flow</a>, and the conference proceedings have been published. Read more about this experiment and the initial findings here: <a href="https://doi.org/10.1051/epjconf/202533404010" target="_blank">https://doi.org/10.1051/epjconf/202533404010</a>.

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    Previous research has suggested that some positions in human crowds are more influential than others. The present study aims to manipulate the influence networks in real human crowds by specifying the causal relationship among some pedestrians. We strategically placed covert or explicit leaders (confederates) in a group of walking pedestrians, instructed them to change walking direction (heading) on a signal, and tested their influence on collective motion. We reconstructed visual influence networks from video data and analyzed the effect of these leaders on the movements of other pedestrians. Our results suggest that both covert and explicit leaders in influential positions can steer and split a crowd, but explicit leaders change the network topology and are significantly more influential than their covert counterparts. The results have potential applications to directing emergency evacuations.

  </div>
</details>

### Agent-based models and simulation of the confederate experiment

Using the previously introduced agent-based models of pedestrian following behavior, I am working on simulating the participant trajectories from the confederate experiment. Treating the covert leaders’ motion as input, we are testing model agreement with the experimental data.

![Simulation with explicit leaders](/images/explicit_simulation.png){: width="40%" }

I presented this work in 2025 at <a href="https://www.ped25.cz" target="_blank">Pedestrian and Evacuation Dynamics</a>.

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    We previously reported an experiment in which covert or explicit leaders (confederates) were placed in a group of walking pedestrians in order to test leader influence on human crowd motion. Here we simulate the participant trajectories with variants of an empirical pedestrian model, treating the covert leaders’ motion as input, and test model agreement with the experimental data. We are currently using reconstructed influence networks to modify the model weights in order to simulate the influence of explicit leaders. The results help us to understand how leader influence propagates via local interactions in real human crowds.
  </div>
</details>

### Reconstruction of "causation networks" using information theory

I am currently working on reconstructing "causation networks" from the same crowd experiment data using information-theoretic measures, such as Transfer Entropy and Causation Entropy. Rather than relyin on correlation measures, this approach quantifies causal effects between pedestrians as information passed from leading to following individuals.


## Previous Research (Coe College)

### Perceptual-motor recalibration in naturalistic and virtual environments
<!-- **TODO: summary** -->

I wrote about this work in my undergraduate <a href="https://coecollege.on.worldcat.org/oclc/1258120465" target="_blank">honors thesis</a>.
We also presented a poster on this work in 2020 at the 61st Annual Meeting of the Psychonomic Society (held virtually).
<!-- See the published abstract [here](https://cdn.ymaws.com/www.psychonomic.org/resource/resmgr/annual_meeting/2020_meeting/2020_abstract_book/ps20_abstracts_11_19_2020.pdf#page=247) (poster 3015). -->

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    The way people learn to interact with the physical world can be conceptualized as a perception-action loop. For new situations, existing schemes are used to make predictions, take actions, and adjust actions based on the feedback. Through this system, people can adapt their motions, such as walking and turning, as environmental conditions change. This locomotive recalibration has been investigated in several experiments in the naturalistic environment. However, there has been less research examining recalibration effects in immersive virtual environments which allow for studies with lower costs and smaller facilities. Further experiments in virtual environments are necessary in order to gain a better understanding of the processes underlying recalibration effects. The present research investigated (1) how perceptions and actions work together and (2) how people respond differently to virtual and naturalistic environments. Specifically, it examined whether a recalibration effect created in a virtual environment had the same characteristics as rotational locomotion in the naturalistic environment. It followed the designs of previous experiments in naturalistic environments and consisted of a pre-test, recalibration phase, and a post-test. The results indicated that there is the same recalibration effect in naturalistic and virtual environments, and rotational recalibration effects transfer between naturalistic and virtual contexts.
  </div>
</details>


### Simple models of movement coordination account for limited portions of pedestrian road-crossing behavior in virtual environments
<!-- **TODO: summary** -->

![road-crossing behavior VR study](/images/road_crossing.png){: width="80%" }

We presented a poster on this work in 2019 at the 60th Annual Meeting of the Psychonomic Society (Montreal, QC, Canada).
<!-- See the published abstract [here](https://cdn.ymaws.com/www.psychonomic.org/resource/resmgr/annual_meeting/2019_meeting/ps2019annualmeeting-FINAL.pdf#page=206) (poster 2194). -->

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    The ability to coordinate self-movement with the movements of other objects is an important survival skill. Movement coordination tasks such as navigating across a busy intersection have high consequences for failure. Critical to reducing the injury rates of roadway users is understanding what perceptual information and movement control strategies individuals use to cross heavily trafficked streets. A number of models of movement control have proposed simple perceptual mechanisms to explain how humans coordinate self- and object-movement. However previous research in virtual environments has shown that no movement strategy based on a single perceptual variable adequately describes how drivers, bicyclists, and pedestrians cross through gaps in traffic. Instead, findings suggest that people crossing busy intersections are employing complex road-crossing strategies that are likely the product of a number of perceptual processes. In the current study, participants were asked to walk through target gaps in a single lane of bicycle traffic presented in a virtual environment. Preliminary results suggest that pedestrian road-crossing behavior may consist of a predictable combination of simple movement control strategies.
  </div>
</details>


### How roadway design affects cyclist-motorist interactions
<!-- **TODO: summary** -->

![Collected data](/images/cyclist_data.png){: width="80%" }

We presented a poster on this work in 2018 at the Tri-State Undergraduate Psychology Conference (Loras College, Dubuque, IA, USA).

<details>
  <summary><em>Click here to see the abstract</em></summary>
  <div style="margin-left: 1em;">
  <br>
    As the global population continues to concentrate into urban environments, the number of conflicts and collisions between different types of roadway users are increasing. In order to share the limited roadway space as efficiently and safely as possible, it is imperative that researchers investigate how pedestrians, bicyclists, and motorists interact with each other. Behavioral work in other labs investigating the overtaking of bicyclists by motorists has begun to explore how cyclists and motorists share the road. In this study, we built and programmed a multi-sensored, GPS-aware distance measurement system based on the Arduino microprocessor. The position-recording capability allows us to identify the specific mechanisms through which roadway features such as bike lanes and sharrows affect the cyclist-motorist interaction. Over a period of five weeks the experimenters rode the instrumented bicycle on city streets and recorded the lateral safety margin motorists afforded the bicyclists while overtaking. As the last phase of the project, all the data collected are currently being processed and analyzed. The development of this novel data collection methodology will strengthen the overall research field by providing a real-world validation of work conducted in laboratory contexts. The end goal of enhanced understanding of how cyclists and motorists interact on the roadway is likely to yield tangible real-world safety benefits for all roadway users.
  </div>
</details>

