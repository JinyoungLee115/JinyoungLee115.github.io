---
layout: home
title: -
subtitle: -
---


<h3>Real-Time Neural Speech Enhancement based on Temporal Refinement Network and Channel-Wise Gating Methods</h3>
Sumbmitted to IEEE ACCESS<br><br>

<h4>Authors</h4>
Jinyoung Lee (jylee@dsp.yonsei.ac.kr) and Hong-Goo Kang<br><br>

<h4>Audio Samples</h4>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0lax{text-align:center;vertical-align:center}
.tg .tg-1wig{font-weight:bold;text-align:center;vertical-align:center}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1wig">Sample</th>
    <th class="tg-1wig">Clean</th>
    <th class="tg-1wig">Noisy</th>
    <th class="tg-1wig">DEMUCS</th>
    <th class="tg-1wig">Proposed</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">bus<br>17.5 dB</td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/clean/p232_065.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/noisy/p232_065.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/DEMUCS/p232_065_enhanced.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/proposed/p232_065_0.wav"></audio></td>
  </tr>
  <tr>
    <td class="tg-0lax">cafe<br>12.5 dB</td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/clean/p232_007.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/noisy/p232_007.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/DEMUCS/p232_007_enhanced.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/proposed/p232_007_0.wav"></audio></td>
  </tr>
  <tr>
    <td class="tg-0lax">living<br>7.5 dB</td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/clean/p232_013.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/noisy/p232_013.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/DEMUCS/p232_013_enhanced.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/proposed/p232_013_0.wav"></audio></td>
  </tr>
<!--   <tr>
    <td class="tg-0lax">living, 17.5 dB</td>    
    <td><audio controls style="width: 150px;"><source src="./assets/samples/clean/p232_053.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/noisy/p232_053.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/DEMUCS/p232_053_enhanced.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/proposed/p232_053_0.wav"></audio></td>
  </tr> -->
  <tr>
    <td class="tg-0lax">office<br>2.5 dB</td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/clean/p232_121.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/noisy/p232_121.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/DEMUCS/p232_121_enhanced.wav"></audio></td>
    <td><audio controls style="width: 150px;"><source src="./assets/samples/proposed/p232_121_0.wav"></audio></td>
  </tr>
</tbody>
</table>

<br>DEMUCS samples were obtained by 'dns48', a pretrained model from https://github.com/facebookresearch/denoiser.

