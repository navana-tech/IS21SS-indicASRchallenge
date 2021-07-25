
<br>
<br>
<div class="widewrapper pagetitle">
  <div class="" style="background-color:#617863;padding:5px">
    <h1 style="color:white;">Welcome!</h1>
  </div>
</div>
<br>


{% comment %} See instructions in the comments below for how to edit specific sections of this workshop template. {% endcomment %}

{% comment %}
HEADER

Edit the values in the block above to be appropriate for your workshop.
If the value is not 'true', 'false', 'null', or a number, please use
double quotation marks around the value, unless specified otherwise.
And run 'make workshop-check' *before* committing to make sure that changes are good.
{% endcomment %}


{% comment %}
8< ============= For a workshop delete from here =============
For a workshop please delete the following block until the next dashed-line
{% endcomment %}




{% comment %}
8< ============================= until here ==================
{% endcomment %}


{% comment %}
Check DC curriculum
{% endcomment %}



{% comment %}
Check SWC curriculum
{% endcomment %}

{% if site.carpentry == "swc" %}
{% unless site.curriculum == "swc-inflammation" or site.curriculum == "swc-gapminder" %}

{% endunless %}
{% endif %}

{% comment %}
EVENTBRITE

This block includes the Eventbrite registration widget if
'eventbrite' has been set in the header.  You can delete it if you
are not using Eventbrite, or leave it in, since it will not be
displayed if the 'eventbrite' field in the header is not set.
{% endcomment %}
{% if page.eventbrite %}
<strong>Some adblockers block the registration window. If you do not see the
  registration box below, please check your adblocker settings.</strong>
<iframe
  src="https://www.eventbrite.com/tickets-external?eid={{page.eventbrite}}&ref=etckt"
  frameborder="0"
  width="100%"
  height="280px"
  scrolling="auto">
</iframe>
{% endif %}
<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
</style>

<p style="font-size:16.5px;">
In the MUCS 2021 challenge, we would like to focus on building multilingual and code-switching ASR systems through two different sub-tasks related to a total of seven Indian languages with constraints on the data available for acoustic modeling and language modeling.</p>
<p></p>
<p style="font-size:16.5px;">
India is a country of language continuum, where every few kilometers the dialect/language changes. Various language families or genealogical types have been reported, in which the vast number of Indian languages can be classified, including Austro-Asiatic, Dravidian, Indo-Aryan, Tibeto-Burman and more recently, Tai-Kadai and Great Andamanese. However, there are no boundaries among these language families, rather languages across different language families share linguistic traits including retroflex sounds, SOV word order, absence of prepositions and many more resulting in acoustic and linguistic richness. According to the 2001 census, 29 Indian languages have more than a million speakers. Among these, 22 languages have been given the status of official languages by the Government of India. Most of these languages are low resource. Many of these languages do not have a written script and hence, speech technology solutions would greatly benefit such communities. Code-switching between an Indian language and (Indian) English has been a normal feature of everyday speech. Understanding code-switching patterns in different languages and developing accurate code-switching ASR remain a challenge due to the lack of large code-switched corpora. Thus, techniques that exploit unique properties and similarities among the Indian languages could be useful for building multilingual and code-switching ASR systems in these resource constrained settings.</p>
  <p> </p> 
  <p style="font-size:16.5px;">
  We will be providing a total of ~600 hours of data in seven Indian languages, namely, Hindi, Marathi, Odia, Bengali, Telugu, Tamil and Gujarati. This includes code-switched transcribed speech in two code-switched language pairs, Hindi-English and Bengali-English. Domains of the speech recordings vary across different languages.  </p>
  <p> </p> 
  <p style="font-size:16.5px;">
  For example, the Odia data comes from healthcare, agriculture and financial domains. The Hindi-English and Bengali-English data are drawn from a repository of technical lectures on a diverse range of topics in computer science. For more description on this, please refer to the <a href = "https://navana-tech.github.io/IS21SS-indicASRchallenge/data.html">Dataset section</a>. We will release a baseline system that participants can compare their systems against and use as a starting point.  During testing, we will release a held-out blind test set that the systems will be evaluated on.</p>
  <p> </p> 
  <h3> The MUCS 2021 challenge comprises two sub-tasks as described below </h3>
  <h4> <b> Sub-task1 </b> </h4>
  <p style="font-size:16.5px;">This sub-task involves building a multilingual ASR system in six languages, namely, Hindi, Marathi, Odia, Telugu, Tamil, and Gujarati. The blind test set will comprise recordings from a subset (or all) of these six languages.</p>

  <h4> <b> Sub-task2 </b> </h4>
  <p style="font-size:16.5px;">This sub-task involves building a code-switching ASR system separately for Hindi-English and Bengali-English code-switched pairs. The blind test set will comprise recordings from these two code-switched language pairs.</p>

  <p style="font-size:16.5px;"> Submissions to this session should show results on one or more of the above mentioned tasks. Submissions on any topic related to building multilingual code-switching ASR are welcome. This includes (but is not limited to):
  </p>
  <ul>
    <li style="font-size:16.5px;"> Acoustic modeling for multilingual ASR models </li>
    <li style="font-size:16.5px;"> Language modeling for multilingual ASR models </li> 
    <li style="font-size:16.5px;"> Multilingual ASR model for code-switching </li> 
    <li style="font-size:16.5px;"> Language modeling for code-switching </li> 
    <li style="font-size:16.5px;"> Linguistically informed models for code-switching </li> 
  </ul>
  <br>


<br>
<br>
  



