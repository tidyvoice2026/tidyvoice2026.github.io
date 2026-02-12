---
layout: page
title: Challenge Results
---

<style>
/* Leaderboard table styles */
.leaderboard-wrapper {
  overflow-x: auto;
  margin: 1.5rem -1rem;
  padding: 0 1rem;
}

.leaderboard-table {
  width: 100%;
  min-width: 680px;
  border-collapse: collapse;
  font-size: 0.82rem;
  line-height: 1.4;
  text-align: center;
}

.leaderboard-table thead th {
  background-color: #2c3e50;
  color: #fff;
  font-weight: 600;
  padding: 0.6rem 0.5rem;
  border: 1px solid #243342;
  text-align: center;
  white-space: nowrap;
  font-family: "PT Sans", Helvetica, Arial, sans-serif;
}

.leaderboard-table thead th.task-header {
  background-color: #34495e;
}

.leaderboard-table tbody td {
  padding: 0.45rem 0.5rem;
  border: 1px solid #dfe6e9;
  text-align: center;
  font-variant-numeric: tabular-nums;
}

.leaderboard-table tbody tr:nth-child(even) td {
  background-color: #f8f9fa;
}

.leaderboard-table tbody tr:nth-child(odd) td {
  background-color: #fff;
}

.leaderboard-table tbody tr:hover td {
  background-color: #ebf5fb;
}

/* Medal rows */
.leaderboard-table tbody tr.rank-1 td {
  background-color: #fff9e6;
  font-weight: 600;
}
.leaderboard-table tbody tr.rank-1:hover td {
  background-color: #fff3cc;
}

.leaderboard-table tbody tr.rank-2 td {
  background-color: #f5f5f5;
  font-weight: 600;
}
.leaderboard-table tbody tr.rank-2:hover td {
  background-color: #ececec;
}

.leaderboard-table tbody tr.rank-3 td {
  background-color: #fef5ed;
  font-weight: 600;
}
.leaderboard-table tbody tr.rank-3:hover td {
  background-color: #fde8d4;
}

/* Baseline row */
.leaderboard-table tbody tr.baseline-row td {
  background-color: #eaf2f8;
  font-style: italic;
  border-top: 2px solid #2c3e50;
  border-bottom: 2px solid #2c3e50;
}
.leaderboard-table tbody tr.baseline-row:hover td {
  background-color: #d5e5f2;
}

.team-cell {
  font-weight: 600;
  text-align: left !important;
  padding-left: 0.7rem !important;
}

.medal {
  margin-right: 0.2rem;
}

/* Info box styling */
.info-box {
  background-color: #f0f7fb;
  border-left: 4px solid #3498db;
  padding: 1rem 1.2rem;
  margin: 1.2rem 0;
  border-radius: 0 4px 4px 0;
  font-size: 0.92rem;
}

.info-box p {
  margin: 0.3rem 0;
  text-align: left;
}

.info-box p:last-child {
  margin-bottom: 0;
}

.call-box {
  background-color: #fef9e7;
  border-left: 4px solid #f1c40f;
  padding: 1rem 1.2rem;
  margin: 1.2rem 0;
  border-radius: 0 4px 4px 0;
  font-size: 0.92rem;
}

.call-box p {
  margin: 0.3rem 0;
  text-align: left;
}

.section-label {
  display: inline-block;
  background-color: #2c3e50;
  color: #fff;
  padding: 0.3rem 0.8rem;
  border-radius: 3px;
  font-family: "PT Sans", Helvetica, Arial, sans-serif;
  font-size: 0.85rem;
  font-weight: 600;
  letter-spacing: 0.03rem;
  margin-bottom: 0.8rem;
}
</style>


We are pleased to announce the official results of the **TidyVoice 2026 Challenge**. We sincerely thank all **42 participating teams** for their outstanding contributions to advancing cross-lingual speaker verification.

<div class="info-box">
  <p><strong>Deeper Analysis:</strong> We have prepared a detailed deeper analysis for each team. You can download it from the corresponding link in the <em>"Deeper Analysis"</em> column of the leaderboard below. You are free to use this analysis in your paper if you wish.</p>
  <p><strong>Ground Truth Release:</strong> The ground truth labels for speaker identity and language will be released in <strong>March 2026</strong>, after the <a href="https://tidylang2026.github.io/" target="_blank">Language Recognition Challenge at <strong>Odyssey 2026</strong></a>, which uses the same dataset. After that, the dataset will serve as a public benchmark for both Automatic Speaker Verification (ASV) and Language Identification (LID).</p>
</div>

<div class="call-box">
  <p><strong>Call for System Descriptions:</strong> All participating teams are welcome and encouraged to submit a paper describing their systems and approaches to the <a href="https://interspeech2026.org/en-AU/pages/calls/submit-a-paper" target="_blank"><strong>Interspeech 2026</strong></a> platform. The final acceptance decision for each paper will be made by the reviewers through the official review process.</p>
  <p>During the submission process, in the <em>"Subject Areas"</em> section, please select: <strong>"14.15 TidyVoice Challenge: Cross-Lingual Speaker Verification"</strong>.</p>
  <p><strong>Submission deadline: 25 February 2026.</strong></p>
  <p>If your paper is publicly available (e.g., on arXiv), we would be happy to link it here for the community. Please share the link with us at: <a href="mailto:aref.farhadipour@uzh.ch"><strong>aref.farhadipour@uzh.ch</strong></a></p>
</div>

---

<span class="section-label">OFFICIAL LEADERBOARD</span>

<div class="leaderboard-wrapper">
<table class="leaderboard-table">
  <thead>
    <tr>
      <th rowspan="2">Team</th>
      <th colspan="2" class="task-header">Task 1</th>
      <th colspan="2" class="task-header">Task 2</th>
      <th rowspan="2">Deeper Analysis</th>
      <th rowspan="2">Paper</th>
    </tr>
    <tr>
      <th class="task-header">EER (%)</th>
      <th class="task-header">minDCF</th>
      <th class="task-header">EER (%)</th>
      <th class="task-header">minDCF</th>
    </tr>
  </thead>
  <tbody>
    <tr class="rank-1">
      <td class="team-cell">T01</td>
      <td>1.39</td>
      <td>0.097</td>
      <td>1.95</td>
      <td>0.058</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_163517.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr class="rank-2">
      <td class="team-cell">T02</td>
      <td>2.21</td>
      <td>0.180</td>
      <td>2.99</td>
      <td>0.205</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_214436.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr class="rank-3">
      <td class="team-cell">T03</td>
      <td>2.43</td>
      <td>0.175</td>
      <td>2.84</td>
      <td>0.189</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_211520.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T04</td>
      <td>2.46</td>
      <td>0.206</td>
      <td>4.45</td>
      <td>0.288</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_092311.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T05</td>
      <td>2.52</td>
      <td>0.189</td>
      <td>3.43</td>
      <td>0.224</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_102449.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T06</td>
      <td>2.53</td>
      <td>0.190</td>
      <td>3.40</td>
      <td>0.196</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_105104.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T07</td>
      <td>2.61</td>
      <td>0.195</td>
      <td>3.39</td>
      <td>0.220</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_195117.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T08</td>
      <td>2.74</td>
      <td>0.253</td>
      <td>2.86</td>
      <td>0.281</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_183017.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T09</td>
      <td>3.56</td>
      <td>0.272</td>
      <td>5.57</td>
      <td>0.367</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_005501.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T10</td>
      <td>3.64</td>
      <td>0.236</td>
      <td>9.16</td>
      <td>0.359</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_seewo.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T11</td>
      <td>3.70</td>
      <td>0.278</td>
      <td>6.41</td>
      <td>0.329</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_021449.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T12</td>
      <td>3.92</td>
      <td>0.296</td>
      <td>5.59</td>
      <td>0.391</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissionzi.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T13</td>
      <td>4.29</td>
      <td>0.285</td>
      <td>5.82</td>
      <td>0.332</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_033010_finalFus.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T14</td>
      <td>4.34</td>
      <td>0.290</td>
      <td>6.13</td>
      <td>0.347</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissionaban.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T15</td>
      <td>4.39</td>
      <td>0.299</td>
      <td>5.13</td>
      <td>0.360</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_021653_fuse3_no.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T16</td>
      <td>4.75</td>
      <td>0.306</td>
      <td>6.30</td>
      <td>0.390</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260205_063955.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T17</td>
      <td>4.81</td>
      <td>0.350</td>
      <td>7.01</td>
      <td>0.422</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_145139.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T18</td>
      <td>5.07</td>
      <td>0.363</td>
      <td>9.89</td>
      <td>0.440</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/cohort.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T19</td>
      <td>5.10</td>
      <td>0.335</td>
      <td>7.74</td>
      <td>0.567</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_143033.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T20</td>
      <td>5.49</td>
      <td>0.434</td>
      <td>7.24</td>
      <td>0.421</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_102942.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T21</td>
      <td>5.50</td>
      <td>0.349</td>
      <td>7.24</td>
      <td>0.448</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_135343.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T22</td>
      <td>5.94</td>
      <td>0.384</td>
      <td>8.84</td>
      <td>0.545</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260202_210941.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T23</td>
      <td>6.12</td>
      <td>0.410</td>
      <td>9.47</td>
      <td>0.624</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_225240.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T24</td>
      <td>6.64</td>
      <td>0.502</td>
      <td>6.30</td>
      <td>0.445</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_FT.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T25</td>
      <td>6.68</td>
      <td>0.498</td>
      <td>6.03</td>
      <td>0.423</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260203_153037.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T26</td>
      <td>7.02</td>
      <td>0.524</td>
      <td>9.84</td>
      <td>0.525</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_135415.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T27</td>
      <td>8.35</td>
      <td>0.402</td>
      <td>9.79</td>
      <td>0.566</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissionhhggee.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T28</td>
      <td>8.40</td>
      <td>0.649</td>
      <td>12.15</td>
      <td>0.630</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_021938.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T29</td>
      <td>8.96</td>
      <td>0.544</td>
      <td>10.62</td>
      <td>0.525</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_114304.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T30</td>
      <td>9.06</td>
      <td>0.658</td>
      <td>11.60</td>
      <td>0.607</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260207_150740.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr class="baseline-row">
      <td class="team-cell">Baseline</td>
      <td>9.06</td>
      <td>0.658</td>
      <td>11.60</td>
      <td>0.607</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260126_180524.zip" target="_blank">Download</a></td>
      <td><a href="https://arxiv.org/pdf/2601.21960" target="_blank">Evaluation Plan</a></td>
    </tr>
    <tr>
      <td class="team-cell">T31</td>
      <td>9.18</td>
      <td>0.573</td>
      <td>10.71</td>
      <td>0.539</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_064143.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T32</td>
      <td>9.27</td>
      <td>0.512</td>
      <td>11.28</td>
      <td>0.508</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_115835.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T33</td>
      <td>10.47</td>
      <td>0.508</td>
      <td>11.06</td>
      <td>0.729</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_074337_vfinal_w.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T34</td>
      <td>10.54</td>
      <td>0.728</td>
      <td>11.18</td>
      <td>0.710</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissionsqz.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T35</td>
      <td>12.43</td>
      <td>0.702</td>
      <td>13.68</td>
      <td>0.765</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissionara.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T36</td>
      <td>13.99</td>
      <td>0.860</td>
      <td>15.22</td>
      <td>0.865</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260211_150510.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T37</td>
      <td>15.03</td>
      <td>0.731</td>
      <td>18.41</td>
      <td>0.717</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/result.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T38</td>
      <td>15.05</td>
      <td>0.700</td>
      <td>19.24</td>
      <td>0.804</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260210_235110.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T39</td>
      <td>15.51</td>
      <td>0.674</td>
      <td>17.93</td>
      <td>0.739</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260206_095830.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T40</td>
      <td>20.15</td>
      <td>0.993</td>
      <td>20.91</td>
      <td>0.970</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submissioniro.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T41</td>
      <td>21.25</td>
      <td>0.999</td>
      <td>22.36</td>
      <td>0.996</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260203_222238.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
    <tr>
      <td class="team-cell">T42</td>
      <td>21.44</td>
      <td>0.987</td>
      <td>23.03</td>
      <td>0.974</td>
      <td><a href="https://github.com/tidyvoice2026/Tidyvoice2026-challenge-result/raw/main/Results-Tidyvoice2026/submission_20260209_225900.zip" target="_blank">Download</a></td>
      <td>—</td>
    </tr>
  </tbody>
</table>
</div>

<p style="text-align: center; font-size: 0.82rem; color: #7a7a7a; margin-top: 0.5rem;">
  Teams are ranked by Task 1 EER (%). The <em>Baseline</em> row shows the official baseline system performance.
</p>

---

### Citation

If you use the TidyVoice dataset in your work, please cite the following:

<div style="background-color: #f6f8fa; border: 1px solid #d0d7de; border-radius: 6px; padding: 16px; margin: 15px 0; font-family: Menlo, Monaco, 'Courier New', monospace; font-size: 0.75rem; line-height: 1.5; overflow-x: auto; white-space: pre;">@misc{farhadipour2026tidyvoicecuratedmultilingualdataset,
      title={TidyVoice: A Curated Multilingual Dataset for Speaker Verification Derived from Common Voice},
      author={Aref Farhadipour and Jan Marquenie and Srikanth Madikeri and Eleanor Chodroff},
      year={2026},
      eprint={2601.16358},
      archivePrefix={arXiv},
      primaryClass={eess.AS},
      url={<a href="https://arxiv.org/abs/2601.16358" target="_blank">https://arxiv.org/abs/2601.16358</a>},
}</div>
