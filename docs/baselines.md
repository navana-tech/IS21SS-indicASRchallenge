<br>
<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Baselines</h1>
  </div>
</div>
<br>

<h1>Blind Test Set</h1>

<h3>Subtask1</h3>

<p style="font-size:16.5px;">The baseline WERs for Subtask1 blind set are as follows:</p>

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>Language</th>
      <th>(% WER)</th>
    </tr>
    <tr>
      <td>Hindi</td>
      <td>37.20</td>
    </tr>
    <tr>
      <td>Marathi</td>
      <td>29.04</td>
    </tr>
    <tr>
      <td>Odiya</td>
      <td>38.46</td>
    </tr>
    <tr>
      <td>Tamil</td>
      <td>34.09</td>
    </tr>
    <tr>
      <td>Telugu</td>
      <td>31.44</td>
    </tr>
    <tr>
      <td>Gujarati</td>
      <td>26.15</td>
    </tr>
    <tr>
      <td>Average</td>
      <td>32.73</td>
    </tr>
  </tbody>
</table>

<h3>Subtask2</h3>


<p style="font-size:16.5px;">The baseline WERs for Subtask2 blind set are as follows:</p>

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>Language</th>
      <th>(% WER)</th>
      <th>(% Transliterated WER)</th>
    </tr>
    <tr>
      <td>Hindi - English</td>
      <td>25.53</td>
      <td>23.80</td>
    </tr>
    <tr>
      <td>Bengali - English</td>
      <td>32.81</td>
      <td>31.70</td>
    </tr>
    <tr>
      <td>Average</td>
      <td>29.17</td>
      <td>27.75</td>
    </tr>
  </tbody>
</table>


<hr>


<h1>Test Set</h1>



<p style="font-size:16.5px;">Baselines are built using Kaldi (Hybrid) and ESPNet (End-to-End). Please go to the <a href="https://github.com/navana-tech/baseline_recipe_is21s_indic_asr_challenge"><strong><span style="color:red">link</span></strong></a> for instructions on how to replicate the baselines.</p>


<p style="font-size:16.5px;">The Word Error Rates of the baseline systems for Sub-task 1 are below:</p>


<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  <thead>
  <tr>
      <th></th>
      <th style="text-align:center;" colspan="2">Hybrid - Kaldi Based System</th>
      <th rowspan="2"></th>
    </tr>
  </thead>
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>Language</th>
      <th>GMM-HMM (% WER)</th>
      <th>TDNN (% WER)</th>
      <th></th>
    </tr>
    <tr>
      <td>Hindi</td>
      <td>69.03</td>
      <td>40.41</td>
      <td></td>
    </tr>
    <tr>
      <td>Marathi</td>
      <td>33.22</td>
      <td>22.44</td>
      <td></td>
    </tr>
    <tr>
      <td>Odiya</td>
      <td>55.78</td>
      <td>39.06</td>
      <td></td>
    </tr>
    <tr>
      <td>Tamil</td>
      <td>48.81</td>
      <td>33.35</td>
      <td></td>
    </tr>
    <tr>
      <td>Telugu</td>
      <td>47.27</td>
      <td>30.62</td>
      <td></td>
    </tr>
    <tr>
      <td>Gujarati</td>
      <td>28.33</td>
      <td>19.27</td>
      <td></td>
    </tr>
    <tr>
      <td>Average</td>
      <td>46.88</td>
      <td>30.73</td>
      <td></td>
    </tr>
  </tbody>
</table>

<p style="font-size:16.5px;">The Word Error Rates of the baseline systems for Sub-task 2 are below:</p>


<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  <thead>
  <tr>
      <th></th>
      <th style="text-align:center;" colspan="2">Hybrid - Kaldi Based System</th>
      <th rowspan="2">End-to-End ESPnet Based System</th>
    </tr>
  </thead>
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>Language</th>
      <th>GMM-HMM (% WER)</th>
      <th>TDNN (% WER)</th>
      <th>(% WER)</th>
    </tr>
    <tr>
      <td>Hindi - English</td>
      <td>44.30</td>
      <td>36.94</td>
      <td>27.7</td>
    </tr>
    <tr>
      <td>Bengali - English</td>
      <td>39.19</td>
      <td>34.31</td>
      <td>37.2</td>
    </tr>
    <tr>
      <td>Average</td>
      <td>41.75</td>
      <td>35.63</td>
      <td>32.45</td>
    </tr>
  </tbody>
</table>