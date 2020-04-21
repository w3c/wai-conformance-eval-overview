---
title: Conformance Evaluation Overview
layout: default
permalink: /test-evaluate/conformance/
github:
  repository: w3c/wai-conformance-eval-overview
footer: >
  <p>Note about video description: The video on this page does not include synchronized audio description because the visuals only illustrate the audio and do not provide additional information. In this case, audio description would be more distracting than useful to most people, including people who cannot see the visuals. Description of visual information is integrated in the Text Transcript with Description of Visuals (“descriptive transcript”).</p>
   <p><strong>Date:</strong> Updated 28 April 2020.</p>
   <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>.</p>
   <p>Videos developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) with support from the <a href="https://www.w3.org/WAI/about/projects/wai-guide/">WAI-Guide</a> project funded by the European Commission (EC) under the Horizon 2020 program (Grant Agreement 822245). <a href="./acknowledgements/">Acknowledgements</a>.</p>
---

<p>Conformance evaluation determines how well web pages or applications meet accessibility standards. <acronym title="World Wide Web Consortium">W3C</acronym>'s Website Accessibility Conformance Evaluation Methodology (WCAG-EM) is an approach for determining conformance to Web Content Accessibility Guidelines (WCAG).</p>

{% comment %}
This abuses the video-card component and tries to make it work with an embedded YouTube player that is enhanced with the AblePlayer library. Remove and replace with regular video-card component in case of bugs.
{% endcomment %}
<div class="video-card" id="video-intro">
  {% include video-player.html
      yt-id="u-mOCGX8ckw"
      captions="https://media.w3.org/wai/evaluation-intros/conformance-evaluation-cc.vtt"
  %}
  <p><a href="#alternatives">Alternatives for Conformance Evaluation Overview Video</a></p>
</div>

<dl>
<dt><a href="{{ "/test-evaluate/conformance/wcag-em/" | relative_url }}">WCAG-EM Overview: Website Accessibility Conformance Evaluation Methodology</a></dt>
<dd>A short page with basic information to get you started. We suggest you read it before going to the <a href="https://www.w3.org/TR/WCAG-EM/">full WCAG-EM document <img src="https://www.w3.org/Icons/tr.png" alt="different format" /></a>.</dd>
<dt><a href="https://www.w3.org/WAI/eval/report-tool/#/">WCAG-EM Report Tool: Website Accessibility Evaluation Report Generator <img src="https://www.w3.org/Icons/tr.png" alt="different format" /></a></dt>
<dd> Helps you generate evaluation reports according to WCAG-EM. It does not do the checking for you. It helps you follow the steps of WCAG-EM and it generates a report from the input  you provide.</dd>
</dl>

<p>Related resources are described in: <a href="{{ "/test-evaluate/" | relative_url }}">Evaluating Web Accessibility Overview</a></p>

<hr>


{% include excol.html type="start" id="video-intro-transcript" %}

##  Alternatives for Conformance Evaluation Overview Video {#alternatives}

{% include excol.html type="middle" %}

_This video is also available on a W3C server: [Video: Conformance Evaluation Overview (file format: MP4, file size: 30MB)](http://media.w3.org/wai/evaluation-intros/conformance-evaluation.mp4)._

###  Text Transcript with Description of Visuals for Conformance Evaluation Overview Video {#transcript}

The videos have basic animation that illustrates what is said by an off-screen voice. People are represented by icon figures. 

<table aria-labelledby="transcript">
  <tbody><tr>
    <th align="left">Audio</th>
    <th align="left">Visual</th>
  </tr>
  <tr>
    <td>Web accessibility conformance evaluation. </td>
    <td>Web accessibility conformance evaluation.</td>
  </tr>
  <tr>
    <td>Conformance evaluation determines how well your content meets specific accessibility standards, such as the "W3C Web Content Accessibility Guidelines", or "WCAG" for short. </td>
    <td>Conformance evaluation. A progress bar is filled until meets the WCAG.</td>
  </tr>
  <tr>
    <td>Often you'll want to do conformance evaluation:
      <ul>
        <li> as a final check before releasing a product</li>
        <li> in order to provide information to potential purchasers of your product</li>
        <li> to regularly monitor the accessibility of your website</li>
        <li> before procuring a product</li>
      </ul></td>
    <td>Icons for each stage: open box with a check mark; round "i"; magnifying glass on a computer; and shopping trolley.</td>
  </tr>
  <tr>
    <td>(continued list)
      <ul>
        <li> and when getting started with implementing accessibility, to get a list of accessibility issues that you need to address.</li>
      </ul></td>
    <td>All icons are integrated in a skyrocket icon. A document with the list of accessibility issues.</td>
  </tr>
  <tr>
    <td>To do effective conformance evaluation, you need expertise in:
      <ul>
        <li> accessibility standards</li>
        <li> accessible web design and development</li>
        <li> assistive technologies</li>
        <li> and how people with disabilities use the Web.</li>
      </ul></td>
    <td>Icons are shown in turn: conformation evaluation words; award ribbon; paint brush and coding icon; assistive technologies icons; and finally people figures.</td>
  </tr>
  <tr>
    <td>You'll probably also want to use evaluation tools to be more efficient. </td>
    <td>A tool box with a gauge moving up.</td>
  </tr>
  <tr>
    <td>"WCAG-EM", the "Website Accessibility Conformance Evaluation Methodology", provides a structure for your evaluation process. </td>
    <td>WCAG-EM, Website Accessibility Conformance Evaluation Methodology. A magnifying glass with the word accessibility.</td>
  </tr>
  <tr>
    <td>It describes a process to:
      <ul>
        <li> define the scope of your evaluation</li>
        <li> explore your website assets</li>
        <li> select a representative sample of web pages from your website</li>
        <li> evaluate the selected sample</li>
        <li> and report your evaluation findings.</li>
      </ul></td>
    <td>Text boxes load one after the other: define scope; explore assets; select sample; evaluate sample; and report findings.</td>
  </tr>
  <tr>
    <td>WCAG-EM also recommends involving real users with disabilities during evaluation, to help you address the real-life experience of your website users. </td>
    <td>A person in front of a computer displaying a website. Passes and fails are marked.</td>
  </tr>
  <tr>
    <td>The open source WCAG-EM Report Tool helps you follow the methodology, record the outcomes, and download a report of your evaluation. </td>
    <td>WCAG-EM Report Tool. A progress bar shows the various stages of the evaluation methodology. A record document is displayed in the computer screen and downloaded.
</td>
  </tr>
  <tr>
    <td>Web accessibility: essential for some, useful for all. </td>
    <td>Icons around a computer: hand; eye; brain; ear; and mouth with sound waves.</td>
  </tr>
  <tr>
    <td>For information on web accessibility conformance evaluation, visit w3.o-r-g/W-A-I/evaluation. </td>
    <td>Conformance Evaluation, W3C and Web Accessibility Initiative (WAI) logos.</td>
  </tr>
</tbody>
</table>

{% include excol.html type="end" %}
