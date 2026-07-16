---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title:
layout: home
---

## <center><span style="color:#2F5597">Open World Navigation</span> in the Foundation Model Era: Robustness and Failure Recovery</center>

##### <center>RSS 2026, Sydney, Australia</center>
##### <center><font color='red'>UTS Building 7, Lecture Theatre: CB07.02.025 (Directions below) </font></center>
##### <center>8:30am - 12:30pm, 17th July 2026, Friday</center>


<video controls="" width="100%" muted="" loop="" autoplay="">
<source src="assets/img/own26_banner_cropped.mp4" type="video/mp4">
</video>

This workshop focuses on robust open-world navigation (OWN) in the era of foundation models. While large-scale data and foundation models have enabled impressive generalization across environments, embodiments, and scenarios, training data is bounded and such models have shown signs of brittleness, leading to failures that undermine reliable deployment. Discussions at the previous iteration of the OWN workshop clearly highlighted these and other persistent gaps in robustness and reliability when applying foundation models to navigation. Building on these insights, this second edition of the OWN workshop aims to explore these gaps by advancing our understanding of foundation models’ failure modes and exploring principled approaches to failure handling. Overall, the workshop seeks to drive a focused discussion on how to progress toward OWN with foundation models, with an emphasis on building robust, reliable, and failure-resilient systems.

In particular, this workshop aims to answer the questions:

* What role do foundation models play in building systems for open-world navigation? What capabilities do current models provide, and what missing capabilities must be developed to support open-world navigation? 
* What are the key failure modes of foundation models in navigation, and how should we evaluate and address them?
* How should navigation systems handle the inevitable out-of-distribution scenarios and failures in the open world? How can uncertainty be quantified and failures handled in the context of foundation models?
* What benchmarks are needed to gauge progress in open-world navigation?

<br>

### <center>Getting to OWN</center>

<center>From the Jones St entrance to UTS Building 7, head to the lower level (Level 2), to reach the lecture theatre (CB07.02.025)</center>
<br>
<center><iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4075.630712217298!2d151.19722297655477!3d-33.88299291979572!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6b12af41ce21dc09%3A0xe16dff70b1e29756!2sUTS%20Building%207%20Science%20and%20Transdisciplinary%20School!5e1!3m2!1sen!2sau!4v1784007431391!5m2!1sen!2sau" width="360" height="270" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe></center>

<br>

### <center>OWN 2026 is online!</center>

Join us on [Zoom](https://nus-sg.zoom.us/j/84880511692?pwd=uAygq9jOjwYcTKDTbqxmrNteEOl6rM.1)

**Meeting ID**: 848 8051 1692

**Passcode**: 340550

### <center>Speakers and Panelists</center>

{% assign speakers_and_panelists = site.speakers | concat: site.panelists %}
{% include people_grid.html people=speakers_and_panelists image_subdir="speakers" %}
<br>

### <center>NaviTrace Challenge</center>
We are accepting submissions to the NaviTrace Challenge for VLMs in navigation! Submissions will be spotlighted during a NaviTrace Challenge segment in our workshop. Please refer to the [NaviTrace Challenge](/open-world-navigation-26/challenge/) page for more details. 

**Deadline**: <span style="color:red">3rd July 2026</span>

🏆 **Challenge Prize**: FrodoBots' [EarthRover Mini+](https://shop.frodobots.com/products/miniplus?srsltid=AfmBOoqF-NQuBkDpGgqnbnBQzYI8uS_-mR034gpT1RSw2R2ugblIqLVv)

<p style="text-align: center;">
<em>Time to Challenge Deadline</em>:
</p>

<center>
<div id="countdown2" style="font-size: 1.5rem; font-weight: bold;"></div>
<script>
  // Countdown 2
  const countdownDate2 = new Date("2026-07-03T23:59:59-12:00").getTime();
  const countdownElement2 = document.getElementById("countdown2");

  const updateCountdown2 = () => {
    const now = new Date().getTime();
    const distance = countdownDate2 - now;

    if (distance < 0) {
      countdownElement2.innerHTML = "0d 0h 0m 0s";
      return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    countdownElement2.innerHTML =
      days + "d " + hours + "h " + minutes + "m " + seconds + "s";
  };

  updateCountdown2();
  setInterval(updateCountdown2, 1000);
</script>
</center>
<br>


### <center>Call for Videos</center>

We are accepting short videos related to the challenges or failure modes of robot navigation systems in the open world, which we will screen during the workshop. Please refer to the [Call for Videos](/open-world-navigation-26/callforvideos/) for more details.

**Deadline**: ~~14th June 2026~~ <span style="color:red">26th June 2026</span>

🏆 **Best Video Award**: FrodoBots' [EarthRover Mini+](https://shop.frodobots.com/products/miniplus?srsltid=AfmBOoqF-NQuBkDpGgqnbnBQzYI8uS_-mR034gpT1RSw2R2ugblIqLVv)

### <center>Call for Papers</center>

We are accepting paper submissions related to generalization and failure handling in robot navigation. Submitted papers should be accompanied by a brief video (30-40 seconds), highlighting limitations and failure modes of the proposed approach. Please refer to the [Call for Papers](/open-world-navigation-26/callforpapers/) for more details.

**Deadline**: ~~14th June 2026~~ <span style="color:red">26th June 2026</span>

🏆 **Best Paper Award**: FrodoBots' [EarthRover Mini+](https://shop.frodobots.com/products/miniplus?srsltid=AfmBOoqF-NQuBkDpGgqnbnBQzYI8uS_-mR034gpT1RSw2R2ugblIqLVv)

<!-- <p style="text-align: center;">
<em>Time to Paper Deadline</em>:
</p>

<center>
<div id="countdown1" style="font-size: 1.5rem; font-weight: bold;"></div>
<script>
  // Countdown 1
  const countdownDate1 = new Date("2026-06-19T23:59:59-12:00").getTime();

  const countdownElement1 = document.getElementById("countdown1");

  const updateCountdown1 = () => {
    const now = new Date().getTime();
    const distance = countdownDate1 - now;
  
    if (distance < 0) {
      countdownElement1.innerHTML = "0d 0h 0m 0s";
      return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);

    countdownElement1.innerHTML =
      days + "d " + hours + "h " + minutes + "m " + seconds + "s";
  };

  updateCountdown1();
  setInterval(updateCountdown1, 1000);
</script>
</center> -->


### <center>Organizers</center>

{% include people_grid.html people=site.organizers image_subdir="organizers" %}

<br>
### <center>Sponsors</center>

<center><img src="assets/img/bitrobot.jpeg" alt="drawing" width="400"/></center>

### <center>
