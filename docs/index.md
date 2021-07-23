---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "MUCS 2021 "        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: ""      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "in"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "in"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the
latitude: "45"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-1"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: ""    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: ""    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate:       # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate:         # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
# instructor:  # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper:      # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["is21ss.indicasrchallenge@gmail.com"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:  # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left {
  width: 100%;
}

.right {
  width: 25%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>


<!-- 
<div class="widewrapper pagetitle">
  <div style="background-color:#617863;padding:5px;">
    <h1 style="color:white;">Keynotes</h1>
  </div>
</div>
<br> -->


<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 12px;
  width: 100%;
  height: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
  font-size: 16.5px;
}
</style>

<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}

/* Style the close button */
.topright {
  float: right;
  cursor: pointer;
  font-size: 28px;
}

.topright:hover {color: red;}
</style>


<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'London')" id="defaultOpen">KEYNOTE</button>
  <button class="tablinks" onclick="openCity(event, 'Paris')">TENTATIVE PROGRAM</button>
  
</div>

<div id="London" class="tabcontent">
<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Anurag_Dwarakanath.PNG">Anurag Dwarakanath, Amazon</button>
<div class="content">
  <p><strong>Title:</strong> Spoken Language Understanding for the Indic Region.</p>
  <p><strong>Abstract:</strong> In this talk, we will touch upon some of the key challenges in building Spoken Language Understanding systems for the Indic region. We begin with an insight on the usage of code-mixed multi-lingual utterances where many Indic languages (beyond Hindi) are freely used. We show how such Indic language usage gets represented in Latin script in a transliterated form and current state of the art multi-lingual language models (such as XLM-R, mBERT) surprisingly do not build common representations of transliterated text and that in the original language. We then introduce research in Continual Language Learning as an emerging area to bridge this gap. The Indic region also sees wide variety of spoken language variations including grammatical errors and ambiguous utterances leading to noise in data. We present recent progress in the area of Robust Machine Learning that aims to build learning algorithms that are resilient to noise in data. </p>

<p><strong>Bio:</strong> Anurag Dwarakanath is an applied science manager in Alexa AI and leads a team of scientists building machine learning and statistical models for the Natural Language Understanding components of Alexa. His interests include multi-lingual natural language processing, robustness in deep learning and verification & validation of deep learning systems. Anurag holds a PhD from Indian Institute of Management Calcutta where he studied the application of Graph Theory in Wireless Sensor Networks. Anurag has over 20 publications and 15 patents. 
</p>
</div>
 <br>

<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/shinji_watanabe.jpg">Shinji Watanabe, Carnegie Mellon University</button>
<div class="content">
  <p><strong>Speakers:</strong> Shinji Watanabe and Pengcheng Guo</p>
  <p><strong>Title:</strong> Introduction of ESPnet, End-to-End Speech Processing Toolkit</p>

<p><strong>Abstract:</strong> An end-to-end neural approach has become a popular alternative to conventional modular approaches in various speech applications including speech recognition and synthesis.
One of the benefits of this end-to-end neural framework is that we can use a unified framework for different speech processing problems based on sequence-to-sequence modeling. This tutorial aims to introduce various end-to-end speech processing applications by focusing on the above unified framework within an open source toolkit named ESPnet (End-to-end speech processing toolkit https://github.com/espnet/espnet). We will explain the recent advance of ESPnet, including conformer: convolution-augmented transformer, and show an example of making an ESPnet recipe to build a state-of-the-art ASR system. </p>
<p><strong>Short bio:</strong></p>
<p><strong>Shinji Watanabe</strong></p>
<p>Shinji Watanabe is an Associate Professor at Carnegie Mellon University, Pittsburgh, PA. He received his B.S., M.S., and Ph.D. (Dr. Eng.) degrees from Waseda University, Tokyo, Japan. He was a research scientist at NTT Communication Science Laboratories, Kyoto, Japan, from 2001 to 2011, a visiting scholar in Georgia institute of technology, Atlanta, GA in 2009, and a senior principal research scientist at Mitsubishi Electric Research Laboratories (MERL), Cambridge, MA USA from 2012 to 2017. Prior to the move to Carnegie Mellon University, he was an associate research professor at Johns Hopkins University, Baltimore, MD USA from 2017 to 2020. His research interests include automatic speech recognition, speech enhancement, spoken language understanding, and machine learning for speech and language processing. He has been published more than 200 papers in peer-reviewed journals and conferences and received several awards, including the best paper award from the IEEE ASRU in 2019. He served as an Associate Editor of the IEEE Transactions on Audio Speech and Language Processing. He was/has been a member of several technical committees, including the APSIPA Speech, Language, and Audio Technical Committee (SLA), IEEE Signal Processing Society Speech and Language Technical Committee (SLTC), and Machine Learning for Signal Processing Technical Committee (MLSP).</p>
<p><strong>Pengcheng Guo</strong></p>
<p>Pengcheng Guo is a Ph.D. candidate at Northwestern Polytechnical University, Xi'an, China.
His supervisors are Prof. Lei Xie and Prof. Shinji Watanabe. From Jul. 2017 to Jul. 2018, he was a research assistant at Nanyang Technology University, Singapore, collaborating with Prof. Eng Siong Chng and Prof. Haizhou Li. From Apr. 2019 to Nov. 2019, he was a research intern at ByteDance AI Lab, Beijing, China, collaborating with Dr. Yuxuan Wang (the author of Tacotron). From Jan.2020 to Jan. 2021, he joined Shinji Watanabe’s team as a visiting scholar at Johns Hopkins University, Baltimore, US. His research interests include automatic speech recognition, domain adaptation, and adversarial training. He is the main developer of ESPnet and has contributed to a lot of projects, including the Conformer architecture, various ASR benchmark recipes, etc.</p>

</div>
<br>

<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Sri_Garimella.jpg">Sri Garimella, Amazon</button>
<div class="content">
  <p><strong>Title:</strong> Overview of Speech Recognition Technology in Conversational Agents</p>
  <p><strong>Abstract:</strong> From the early days of modern Automatic Speech Recognition (ASR) research in the 1990s, one of the driving visions of the field has been a computer-based assistant that could accomplish tasks for the user, simply by being spoken to. Today, we are close to achieving that vision, with a whole array of speech-enabled AI agents eager to help users. Amazon’s Alexa pioneered the AI assistant concept for smart speaker devices enabled by far-field ASR. It currently supports billions of customer interactions per week, on over 100 million devices across multiple languages. This talk will give an overview of the interplay between underlying speech technologies, including wakeword detection, endpointing, speaker identification, and speech recognition that enable Alexa. We highlight successes and challenges in developing large-scale ASR, and dive into the unique data aspects of large-scale deployments like Alexa, where a continuous stream of unlabeled data enables successful applications of semi-supervised learning. Finally, we highlight problems that remain to be solved before the promise of a fully natural, conversational assistant is fully realized.</p>

<p><strong>Bio:</strong> Sri Garimella is a senior manager of Applied Science, Alexa ASR in India. His team developed the ASR technology for launching Alexa in Indian English and Hindi languages. Sri obtained PhD from the Department of Electrical and Computer Engineering, Center for Language and Speech Processing at the Johns Hopkins University, Baltimore, USA in 2012. And Master of Engineering in Signal Processing from the Indian Institute of Science, Bangalore, India in 2006.</p>
</div>
<br>

<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Samuel_Thomas.jpg">Samuel Thomas, IBM T.J. Watson Research Center, New York</button>
<div class="content">
  <p><strong>Title:</strong> What next after ASR in Indian Languages? We speak in order to be understood!</p>
  <p><strong>Abstract:</strong> The MUCS 2021 challenge has focused on building multilingual and code-switching ASR systems for Indian languages in low resource settings. Within this challenge, teams have successfully tackled important problems and have demonstrated significant improvements on various languages. Where do these gains lead us next? If we speak in order to be understood, we advocate that the next frontier in this space is spoken language understanding (SLU). In this talk we will review recent work in end-to-end spoken language understanding, where the speech input is directly processed into intent without going through an intermediate text transcript. The lessons learnt in building ASR systems in low resource settings are extremely useful for this task too, as very often there is very limited SLU training data. We will share insights on training E2E SLU systems and the challenges ahead and how they can be applied for Indic languages.</p>

<p><strong>Brief Bio:</strong> Samuel Thomas received his B.Tech degree in Computer Engineering from the Cochin University of Science and Technology, India (2000) and M.S degree in Computer Science and Engineering from the Indian Institute of Technology Madras, India (2006) before earning his Doctor of Philosophy degree from the Johns Hopkins University, Baltimore in 2012. Since graduation, he has been at the IBM T.J. Watson Research Center, New York with the Speech Technologies Group. In the past, he has worked on several speech research projects and workshops with the Center for Language and Speech Processing (CLSP) at JHU, the Idiap Research Institute, Switzerland and the TeNeT group, IIT Madras. His research interests include speech processing and machine learning for speech recognition, spoken language understanding, speech synthesis and speaker recognition.</p>
</div>
<br>


<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/Mahadev_Prasanna.jfif">S. R. Mahadeva Prasanna, IIT Dharwad</button>
<div class="content">
  <p><strong>Title: </strong>Speech Processing: Handcrafted features to Deep Representations</p>
  <p><strong>Abstract: </strong>With the advent of deep learning to the speech processing field for about a decade, a lot of attempts have been made towards learning the representations from spectrographic representation of speech. These representations are based on nonlinear processing and
seem to capture more information from speech. The other mostly practised approach is handcrafted features extracted using signal processing and linked to speech production and/or perception. These approaches are mostly based on linear processing and are mathematically tractable.  This talk will take through the journey of speech processing from earliest explorations of handcrafted features to the latest deep representations. </p>

<p><strong>Brief:</strong> Dr. S. R. M. Prasanna is Dean (Faculty Welfare, Research and Development) and Professor, Dept of Electrical Engineering at IIT Dharwad since July 2017. He was faculty member at the Dept of Electronics and Electrical Engineering at IIT Guwahati from August 2004 to July 2017. He was also Dean (Research and Development) from July 2015 to July 2017 at IIT Guwahati. He
obtained his PhD in CSE from IIT Madras in 2004, MTech in Industrial Electronics from NITK Surathkal in 1997 and BE in Electronics from SSIT Tumakuru (then with Bangalore University) in 1994. He has guided 20 PhD Theses and 12 ongoing in the areas of Speech and Handwriting processing. He has published over 250 research articles in reputed Indian and International journals and conferences. He has executed large volume funded projects and also provided consultancy to many public sector and private limited companies
in the areas of speech processing.</p>
</div>
<br>

<button class="collapsible"><img style="height: 120px; width:auto;padding:5px;"  src="./assets/img/persons/s_umesh.jpg">S Umesh, IIT Madras</button>
<div class="content">
  <p><strong>Title:</strong> Automatic Speech Recognition using Models from GMM-HMM  to Transformers to wav2vec2.0</p>
  <p><strong>Abstract:</strong> In this talk, I will give an overview of various models used in Automatic Speech Recognition. After a brief overview of conventional GMM-HMM models and the role of lexicon and language models, I will talk about the recent progress based on deep-learning methods. This will include DNN-HMM and CTC based approaches. This will be followed by the sequence-to-sequence approaches including Attention-Based Encoder Decoder as well as transformers. Finally, I will talk about self-supervised approaches that are inspired by BERT, GPT and contrastive predictive coding including methods like MockingJay, Wav2vec and HuBERT.</p>
</div>
<br>


</div>

<div id="Paris" class="tabcontent">
<img style="height: auto; width:auto;padding:5px;"  src="./assets/img/tentative_program.PNG">
</div>



<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>


