<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

# SeroNet Data Model (SSNCC)
[View model on GitHub Pages](https://cbiit.github.io/seronet-model)


Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<p>
<a href="./model-desc/seronet-model.svg">SVG file (in view above)</a>
<p>
<a href="./model-desc">Additional model files</a>
<div id='graph' style='display:off;'>
<svg width="2962pt" height="1143pt"
 viewBox="0.00 0.00 2962.00 1143.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1139)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1139 2958,-1139 2958,4 -4,4"/>
<!-- participant -->
<g id="node1" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M851,-472C851,-472 995,-472 995,-472 1001,-472 1007,-478 1007,-484 1007,-484 1007,-496 1007,-496 1007,-502 1001,-508 995,-508 995,-508 851,-508 851,-508 845,-508 839,-502 839,-496 839,-496 839,-484 839,-484 839,-478 845,-472 851,-472"/>
<text text-anchor="middle" x="887" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="935,-472 935,-508 "/>
<text text-anchor="middle" x="945.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="956,-472 956,-508 "/>
<text text-anchor="middle" x="971" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="986,-472 986,-508 "/>
<text text-anchor="middle" x="996.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- project -->
<g id="node6" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M861.5,-167.5C861.5,-167.5 1058.5,-167.5 1058.5,-167.5 1064.5,-167.5 1070.5,-173.5 1070.5,-179.5 1070.5,-179.5 1070.5,-224.5 1070.5,-224.5 1070.5,-230.5 1064.5,-236.5 1058.5,-236.5 1058.5,-236.5 861.5,-236.5 861.5,-236.5 855.5,-236.5 849.5,-230.5 849.5,-224.5 849.5,-224.5 849.5,-179.5 849.5,-179.5 849.5,-173.5 855.5,-167.5 861.5,-167.5"/>
<text text-anchor="middle" x="883.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="917.5,-167.5 917.5,-236.5 "/>
<text text-anchor="middle" x="928" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="938.5,-167.5 938.5,-236.5 "/>
<text text-anchor="middle" x="994" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="938.5,-213.5 1049.5,-213.5 "/>
<text text-anchor="middle" x="994" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="938.5,-190.5 1049.5,-190.5 "/>
<text text-anchor="middle" x="994" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="1049.5,-167.5 1049.5,-236.5 "/>
<text text-anchor="middle" x="1060" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;project -->
<g id="edge4" class="edge">
<title>participant&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M919.3629,-471.8508C912.871,-436.0914 901.3619,-354.2439 917,-288 920.4277,-273.4799 926.7032,-258.6161 933.4201,-245.4185"/>
<polygon fill="#000000" stroke="#000000" points="936.5182,-247.047 938.1113,-236.5726 930.334,-243.7674 936.5182,-247.047"/>
<text text-anchor="middle" x="960.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- center -->
<g id="node9" class="node">
<title>center</title>
<path fill="none" stroke="#000000" d="M832.5,-.5C832.5,-.5 1087.5,-.5 1087.5,-.5 1093.5,-.5 1099.5,-6.5 1099.5,-12.5 1099.5,-12.5 1099.5,-103.5 1099.5,-103.5 1099.5,-109.5 1093.5,-115.5 1087.5,-115.5 1087.5,-115.5 832.5,-115.5 832.5,-115.5 826.5,-115.5 820.5,-109.5 820.5,-103.5 820.5,-103.5 820.5,-12.5 820.5,-12.5 820.5,-6.5 826.5,-.5 832.5,-.5"/>
<text text-anchor="middle" x="852" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">center</text>
<polyline fill="none" stroke="#000000" points="883.5,-.5 883.5,-115.5 "/>
<text text-anchor="middle" x="894" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="904.5,-.5 904.5,-115.5 "/>
<text text-anchor="middle" x="991.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">center_type</text>
<polyline fill="none" stroke="#000000" points="904.5,-92.5 1078.5,-92.5 "/>
<text text-anchor="middle" x="991.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="904.5,-69.5 1078.5,-69.5 "/>
<text text-anchor="middle" x="991.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="904.5,-46.5 1078.5,-46.5 "/>
<text text-anchor="middle" x="991.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">principal_investigator</text>
<polyline fill="none" stroke="#000000" points="904.5,-23.5 1078.5,-23.5 "/>
<text text-anchor="middle" x="991.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1078.5,-.5 1078.5,-115.5 "/>
<text text-anchor="middle" x="1089" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;center -->
<g id="edge6" class="edge">
<title>participant&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M910.0573,-471.6894C876.0206,-421.1105 790.0342,-276.0135 841,-167 848.5587,-150.8323 859.7243,-135.9614 872.2336,-122.7432"/>
<polygon fill="#000000" stroke="#000000" points="874.7764,-125.1493 879.307,-115.5721 869.7928,-120.2336 874.7764,-125.1493"/>
<text text-anchor="middle" x="866.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_at</text>
</g>
<!-- study -->
<g id="node11" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1024.5,-288.5C1024.5,-288.5 1209.5,-288.5 1209.5,-288.5 1215.5,-288.5 1221.5,-294.5 1221.5,-300.5 1221.5,-300.5 1221.5,-345.5 1221.5,-345.5 1221.5,-351.5 1215.5,-357.5 1209.5,-357.5 1209.5,-357.5 1024.5,-357.5 1024.5,-357.5 1018.5,-357.5 1012.5,-351.5 1012.5,-345.5 1012.5,-345.5 1012.5,-300.5 1012.5,-300.5 1012.5,-294.5 1018.5,-288.5 1024.5,-288.5"/>
<text text-anchor="middle" x="1040.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1068.5,-288.5 1068.5,-357.5 "/>
<text text-anchor="middle" x="1079" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1089.5,-288.5 1089.5,-357.5 "/>
<text text-anchor="middle" x="1145" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1089.5,-334.5 1200.5,-334.5 "/>
<text text-anchor="middle" x="1145" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="1089.5,-311.5 1200.5,-311.5 "/>
<text text-anchor="middle" x="1145" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="1200.5,-288.5 1200.5,-357.5 "/>
<text text-anchor="middle" x="1211" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge3" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M944.1307,-471.8102C973.8682,-446.2114 1028.8983,-398.8401 1068.9016,-364.4043"/>
<polygon fill="#000000" stroke="#000000" points="1071.3945,-366.8765 1076.6899,-357.6999 1066.8277,-361.5714 1071.3945,-366.8765"/>
<text text-anchor="middle" x="1097.5" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- cohort -->
<g id="node16" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1251.5,-288.5C1251.5,-288.5 1430.5,-288.5 1430.5,-288.5 1436.5,-288.5 1442.5,-294.5 1442.5,-300.5 1442.5,-300.5 1442.5,-345.5 1442.5,-345.5 1442.5,-351.5 1436.5,-357.5 1430.5,-357.5 1430.5,-357.5 1251.5,-357.5 1251.5,-357.5 1245.5,-357.5 1239.5,-351.5 1239.5,-345.5 1239.5,-345.5 1239.5,-300.5 1239.5,-300.5 1239.5,-294.5 1245.5,-288.5 1251.5,-288.5"/>
<text text-anchor="middle" x="1271" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1302.5,-288.5 1302.5,-357.5 "/>
<text text-anchor="middle" x="1313" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1323.5,-288.5 1323.5,-357.5 "/>
<text text-anchor="middle" x="1372.5" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">description</text>
<polyline fill="none" stroke="#000000" points="1323.5,-334.5 1421.5,-334.5 "/>
<text text-anchor="middle" x="1372.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1323.5,-311.5 1421.5,-311.5 "/>
<text text-anchor="middle" x="1372.5" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1421.5,-288.5 1421.5,-357.5 "/>
<text text-anchor="middle" x="1432" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;cohort -->
<g id="edge22" class="edge">
<title>participant&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M968.1305,-471.9694C1034.0219,-445.6443 1158.1488,-396.053 1245.0199,-361.3461"/>
<polygon fill="#000000" stroke="#000000" points="1246.3751,-364.5737 1254.3629,-357.6134 1243.778,-358.0733 1246.3751,-364.5737"/>
<text text-anchor="middle" x="1239" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cohort</text>
</g>
<!-- workflow -->
<g id="node2" class="node">
<title>workflow</title>
<path fill="none" stroke="#000000" d="M2278.5,-1054C2278.5,-1054 2501.5,-1054 2501.5,-1054 2507.5,-1054 2513.5,-1060 2513.5,-1066 2513.5,-1066 2513.5,-1088 2513.5,-1088 2513.5,-1094 2507.5,-1100 2501.5,-1100 2501.5,-1100 2278.5,-1100 2278.5,-1100 2272.5,-1100 2266.5,-1094 2266.5,-1088 2266.5,-1088 2266.5,-1066 2266.5,-1066 2266.5,-1060 2272.5,-1054 2278.5,-1054"/>
<text text-anchor="middle" x="2308" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">workflow</text>
<polyline fill="none" stroke="#000000" points="2349.5,-1054 2349.5,-1100 "/>
<text text-anchor="middle" x="2360" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2370.5,-1054 2370.5,-1100 "/>
<text text-anchor="middle" x="2431.5" y="-1084.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2370.5,-1077 2492.5,-1077 "/>
<text text-anchor="middle" x="2431.5" y="-1061.8" font-family="Times,serif" font-size="14.00" fill="#000000">workflow_type</text>
<polyline fill="none" stroke="#000000" points="2492.5,-1054 2492.5,-1100 "/>
<text text-anchor="middle" x="2503" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic -->
<g id="node3" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M640,-714.5C640,-714.5 868,-714.5 868,-714.5 874,-714.5 880,-720.5 880,-726.5 880,-726.5 880,-863.5 880,-863.5 880,-869.5 874,-875.5 868,-875.5 868,-875.5 640,-875.5 640,-875.5 634,-875.5 628,-869.5 628,-863.5 628,-863.5 628,-726.5 628,-726.5 628,-720.5 634,-714.5 640,-714.5"/>
<text text-anchor="middle" x="683" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="738,-714.5 738,-875.5 "/>
<text text-anchor="middle" x="748.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="759,-714.5 759,-875.5 "/>
<text text-anchor="middle" x="809" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">abo_type</text>
<polyline fill="none" stroke="#000000" points="759,-852.5 859,-852.5 "/>
<text text-anchor="middle" x="809" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">age</text>
<polyline fill="none" stroke="#000000" points="759,-829.5 859,-829.5 "/>
<text text-anchor="middle" x="809" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="759,-806.5 859,-806.5 "/>
<text text-anchor="middle" x="809" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="759,-783.5 859,-783.5 "/>
<text text-anchor="middle" x="809" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="759,-760.5 859,-760.5 "/>
<text text-anchor="middle" x="809" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">rh_type</text>
<polyline fill="none" stroke="#000000" points="759,-737.5 859,-737.5 "/>
<text text-anchor="middle" x="809" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="859,-714.5 859,-875.5 "/>
<text text-anchor="middle" x="869.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>demographic&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M798.6238,-714.4659C834.7935,-649.1893 883.6108,-561.087 907.928,-517.2009"/>
<polygon fill="#000000" stroke="#000000" points="911.0852,-518.7244 912.8705,-508.2811 904.9623,-515.3317 911.0852,-518.7244"/>
<text text-anchor="middle" x="913.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- clinical_course -->
<g id="node4" class="node">
<title>clinical_course</title>
<path fill="none" stroke="#000000" d="M2544,-1054C2544,-1054 2942,-1054 2942,-1054 2948,-1054 2954,-1060 2954,-1066 2954,-1066 2954,-1088 2954,-1088 2954,-1094 2948,-1100 2942,-1100 2942,-1100 2544,-1100 2544,-1100 2538,-1100 2532,-1094 2532,-1088 2532,-1088 2532,-1066 2532,-1066 2532,-1060 2538,-1054 2544,-1054"/>
<text text-anchor="middle" x="2594" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_course</text>
<polyline fill="none" stroke="#000000" points="2656,-1054 2656,-1100 "/>
<text text-anchor="middle" x="2666.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2677,-1054 2677,-1100 "/>
<text text-anchor="middle" x="2805" y="-1084.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_findings_and_procedures</text>
<polyline fill="none" stroke="#000000" points="2677,-1077 2933,-1077 "/>
<text text-anchor="middle" x="2805" y="-1061.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_assessment</text>
<polyline fill="none" stroke="#000000" points="2933,-1054 2933,-1100 "/>
<text text-anchor="middle" x="2943.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_run -->
<g id="node5" class="node">
<title>assay_run</title>
<path fill="none" stroke="#000000" d="M2032,-737.5C2032,-737.5 2270,-737.5 2270,-737.5 2276,-737.5 2282,-743.5 2282,-749.5 2282,-749.5 2282,-840.5 2282,-840.5 2282,-846.5 2276,-852.5 2270,-852.5 2270,-852.5 2032,-852.5 2032,-852.5 2026,-852.5 2020,-846.5 2020,-840.5 2020,-840.5 2020,-749.5 2020,-749.5 2020,-743.5 2026,-737.5 2032,-737.5"/>
<text text-anchor="middle" x="2064.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_run</text>
<polyline fill="none" stroke="#000000" points="2109,-737.5 2109,-852.5 "/>
<text text-anchor="middle" x="2119.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2130,-737.5 2130,-852.5 "/>
<text text-anchor="middle" x="2195.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_performed</text>
<polyline fill="none" stroke="#000000" points="2130,-829.5 2261,-829.5 "/>
<text text-anchor="middle" x="2195.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2130,-806.5 2261,-806.5 "/>
<text text-anchor="middle" x="2195.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_clia</text>
<polyline fill="none" stroke="#000000" points="2130,-783.5 2261,-783.5 "/>
<text text-anchor="middle" x="2195.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">operator</text>
<polyline fill="none" stroke="#000000" points="2130,-760.5 2261,-760.5 "/>
<text text-anchor="middle" x="2195.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">variances</text>
<polyline fill="none" stroke="#000000" points="2261,-737.5 2261,-852.5 "/>
<text text-anchor="middle" x="2271.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_result -->
<g id="node10" class="node">
<title>assay_result</title>
<path fill="none" stroke="#000000" d="M1920,-444C1920,-444 2154,-444 2154,-444 2160,-444 2166,-450 2166,-456 2166,-456 2166,-524 2166,-524 2166,-530 2160,-536 2154,-536 2154,-536 1920,-536 1920,-536 1914,-536 1908,-530 1908,-524 1908,-524 1908,-456 1908,-456 1908,-450 1914,-444 1920,-444"/>
<text text-anchor="middle" x="1961" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_result</text>
<polyline fill="none" stroke="#000000" points="2014,-444 2014,-536 "/>
<text text-anchor="middle" x="2024.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2035,-444 2035,-536 "/>
<text text-anchor="middle" x="2090" y="-520.8" font-family="Times,serif" font-size="14.00" fill="#000000">cutoff</text>
<polyline fill="none" stroke="#000000" points="2035,-513 2145,-513 "/>
<text text-anchor="middle" x="2090" y="-497.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2035,-490 2145,-490 "/>
<text text-anchor="middle" x="2090" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">output_type</text>
<polyline fill="none" stroke="#000000" points="2035,-467 2145,-467 "/>
<text text-anchor="middle" x="2090" y="-451.8" font-family="Times,serif" font-size="14.00" fill="#000000">output_value</text>
<polyline fill="none" stroke="#000000" points="2145,-444 2145,-536 "/>
<text text-anchor="middle" x="2155.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_run&#45;&gt;assay_result -->
<g id="edge21" class="edge">
<title>assay_run&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M2144.12,-737.2122C2137.6594,-694.8705 2125.7789,-636.7067 2105,-589 2098.3805,-573.8021 2089.3144,-558.4961 2079.9598,-544.6147"/>
<polygon fill="#000000" stroke="#000000" points="2082.6849,-542.4019 2074.1171,-536.1694 2076.9282,-546.3845 2082.6849,-542.4019"/>
<text text-anchor="middle" x="2170" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_assay_result</text>
</g>
<!-- assay -->
<g id="node17" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M2349.5,-409.5C2349.5,-409.5 2538.5,-409.5 2538.5,-409.5 2544.5,-409.5 2550.5,-415.5 2550.5,-421.5 2550.5,-421.5 2550.5,-558.5 2550.5,-558.5 2550.5,-564.5 2544.5,-570.5 2538.5,-570.5 2538.5,-570.5 2349.5,-570.5 2349.5,-570.5 2343.5,-570.5 2337.5,-564.5 2337.5,-558.5 2337.5,-558.5 2337.5,-421.5 2337.5,-421.5 2337.5,-415.5 2343.5,-409.5 2349.5,-409.5"/>
<text text-anchor="middle" x="2365.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
<polyline fill="none" stroke="#000000" points="2393.5,-409.5 2393.5,-570.5 "/>
<text text-anchor="middle" x="2404" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2414.5,-409.5 2414.5,-570.5 "/>
<text text-anchor="middle" x="2472" y="-555.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody</text>
<polyline fill="none" stroke="#000000" points="2414.5,-547.5 2529.5,-547.5 "/>
<text text-anchor="middle" x="2472" y="-532.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2414.5,-524.5 2529.5,-524.5 "/>
<text text-anchor="middle" x="2472" y="-509.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_target</text>
<polyline fill="none" stroke="#000000" points="2414.5,-501.5 2529.5,-501.5 "/>
<text text-anchor="middle" x="2472" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_type</text>
<polyline fill="none" stroke="#000000" points="2414.5,-478.5 2529.5,-478.5 "/>
<text text-anchor="middle" x="2472" y="-463.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2414.5,-455.5 2529.5,-455.5 "/>
<text text-anchor="middle" x="2472" y="-440.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer</text>
<polyline fill="none" stroke="#000000" points="2414.5,-432.5 2529.5,-432.5 "/>
<text text-anchor="middle" x="2472" y="-417.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="2529.5,-409.5 2529.5,-570.5 "/>
<text text-anchor="middle" x="2540" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_run&#45;&gt;assay -->
<g id="edge19" class="edge">
<title>assay_run&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2193.6516,-737.1412C2220.217,-702.4592 2255.9122,-658.2105 2291,-622 2305.4761,-607.0606 2321.4548,-591.96 2337.4633,-577.5744"/>
<polygon fill="#000000" stroke="#000000" points="2340.1815,-579.8401 2345.318,-570.5736 2335.524,-574.6144 2340.1815,-579.8401"/>
<text text-anchor="middle" x="2352.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- project&#45;&gt;center -->
<g id="edge16" class="edge">
<title>project&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M960,-167.1416C960,-154.6834 960,-140.1822 960,-125.8971"/>
<polygon fill="#000000" stroke="#000000" points="963.5001,-125.5658 960,-115.5658 956.5001,-125.5658 963.5001,-125.5658"/>
<text text-anchor="middle" x="994" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- sop -->
<g id="node7" class="node">
<title>sop</title>
<path fill="none" stroke="#000000" d="M2066,-1019.5C2066,-1019.5 2236,-1019.5 2236,-1019.5 2242,-1019.5 2248,-1025.5 2248,-1031.5 2248,-1031.5 2248,-1122.5 2248,-1122.5 2248,-1128.5 2242,-1134.5 2236,-1134.5 2236,-1134.5 2066,-1134.5 2066,-1134.5 2060,-1134.5 2054,-1128.5 2054,-1122.5 2054,-1122.5 2054,-1031.5 2054,-1031.5 2054,-1025.5 2060,-1019.5 2066,-1019.5"/>
<text text-anchor="middle" x="2074.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">sop</text>
<polyline fill="none" stroke="#000000" points="2095,-1019.5 2095,-1134.5 "/>
<text text-anchor="middle" x="2105.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2116,-1019.5 2116,-1134.5 "/>
<text text-anchor="middle" x="2171.5" y="-1119.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2116,-1111.5 2227,-1111.5 "/>
<text text-anchor="middle" x="2171.5" y="-1096.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="2116,-1088.5 2227,-1088.5 "/>
<text text-anchor="middle" x="2171.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">process_type</text>
<polyline fill="none" stroke="#000000" points="2116,-1065.5 2227,-1065.5 "/>
<text text-anchor="middle" x="2171.5" y="-1050.3" font-family="Times,serif" font-size="14.00" fill="#000000">url</text>
<polyline fill="none" stroke="#000000" points="2116,-1042.5 2227,-1042.5 "/>
<text text-anchor="middle" x="2171.5" y="-1027.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="2227,-1019.5 2227,-1134.5 "/>
<text text-anchor="middle" x="2237.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;assay_run -->
<g id="edge1" class="edge">
<title>sop&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M2151,-1019.2526C2151,-973.9155 2151,-910.6872 2151,-862.9217"/>
<polygon fill="#000000" stroke="#000000" points="2154.5001,-862.6701 2151,-852.6702 2147.5001,-862.6702 2154.5001,-862.6701"/>
<text text-anchor="middle" x="2198" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- sop&#45;&gt;assay -->
<g id="edge18" class="edge">
<title>sop&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2248.0428,-1022.5977C2251.3694,-1021.3117 2254.6939,-1020.1067 2258,-1019 2330.241,-994.8175 2547.3,-1025.7362 2597,-968 2697.3235,-851.4547 2661.032,-761.8124 2597,-622 2587.8159,-601.9467 2573.9147,-583.7816 2558.1673,-567.7869"/>
<polygon fill="#000000" stroke="#000000" points="2560.4083,-565.0829 2550.8124,-560.5917 2555.5131,-570.0867 2560.4083,-565.0829"/>
<text text-anchor="middle" x="2689.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- biospecimen -->
<g id="node18" class="node">
<title>biospecimen</title>
<path fill="none" stroke="#000000" d="M910,-622.5C910,-622.5 1276,-622.5 1276,-622.5 1282,-622.5 1288,-628.5 1288,-634.5 1288,-634.5 1288,-955.5 1288,-955.5 1288,-961.5 1282,-967.5 1276,-967.5 1276,-967.5 910,-967.5 910,-967.5 904,-967.5 898,-961.5 898,-955.5 898,-955.5 898,-634.5 898,-634.5 898,-628.5 904,-622.5 910,-622.5"/>
<text text-anchor="middle" x="951.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen</text>
<polyline fill="none" stroke="#000000" points="1005,-622.5 1005,-967.5 "/>
<text text-anchor="middle" x="1015.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1026,-622.5 1026,-967.5 "/>
<text text-anchor="middle" x="1146.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_group</text>
<polyline fill="none" stroke="#000000" points="1026,-944.5 1267,-944.5 "/>
<text text-anchor="middle" x="1146.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="1026,-921.5 1267,-921.5 "/>
<text text-anchor="middle" x="1146.5" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_last_aliquotted</text>
<polyline fill="none" stroke="#000000" points="1026,-898.5 1267,-898.5 "/>
<text text-anchor="middle" x="1146.5" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">datetime_of_collection</text>
<polyline fill="none" stroke="#000000" points="1026,-875.5 1267,-875.5 "/>
<text text-anchor="middle" x="1146.5" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">datetime_of_processing</text>
<polyline fill="none" stroke="#000000" points="1026,-852.5 1267,-852.5 "/>
<text text-anchor="middle" x="1146.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_onset</text>
<polyline fill="none" stroke="#000000" points="1026,-829.5 1267,-829.5 "/>
<text text-anchor="middle" x="1146.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_resolution</text>
<polyline fill="none" stroke="#000000" points="1026,-806.5 1267,-806.5 "/>
<text text-anchor="middle" x="1146.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">freeze_thaw_cycle</text>
<polyline fill="none" stroke="#000000" points="1026,-783.5 1267,-783.5 "/>
<text text-anchor="middle" x="1146.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1026,-760.5 1267,-760.5 "/>
<text text-anchor="middle" x="1146.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_concentration_pbmc</text>
<polyline fill="none" stroke="#000000" points="1026,-737.5 1267,-737.5 "/>
<text text-anchor="middle" x="1146.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="1026,-714.5 1267,-714.5 "/>
<text text-anchor="middle" x="1146.5" y="-699.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_live_pbmc</text>
<polyline fill="none" stroke="#000000" points="1026,-691.5 1267,-691.5 "/>
<text text-anchor="middle" x="1146.5" y="-676.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_total_pbmc</text>
<polyline fill="none" stroke="#000000" points="1026,-668.5 1267,-668.5 "/>
<text text-anchor="middle" x="1146.5" y="-653.3" font-family="Times,serif" font-size="14.00" fill="#000000">percent_viable_pbmc</text>
<polyline fill="none" stroke="#000000" points="1026,-645.5 1267,-645.5 "/>
<text text-anchor="middle" x="1146.5" y="-630.3" font-family="Times,serif" font-size="14.00" fill="#000000">rt_serum_clotting</text>
<polyline fill="none" stroke="#000000" points="1267,-622.5 1267,-967.5 "/>
<text text-anchor="middle" x="1277.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;biospecimen -->
<g id="edge7" class="edge">
<title>sop&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M2053.7976,-1031.876C2010.7106,-1014.0989 1958.8102,-995.6506 1910,-986 1845.6342,-973.2738 1395.8593,-990.9976 1297.9673,-967.3722"/>
<polygon fill="#000000" stroke="#000000" points="1298.8437,-963.981 1288.2593,-964.4523 1296.8275,-970.6843 1298.8437,-963.981"/>
<text text-anchor="middle" x="2020" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
<!-- assay_metrics -->
<g id="node8" class="node">
<title>assay_metrics</title>
<path fill="none" stroke="#000000" d="M2312,-760.5C2312,-760.5 2576,-760.5 2576,-760.5 2582,-760.5 2588,-766.5 2588,-772.5 2588,-772.5 2588,-817.5 2588,-817.5 2588,-823.5 2582,-829.5 2576,-829.5 2576,-829.5 2312,-829.5 2312,-829.5 2306,-829.5 2300,-823.5 2300,-817.5 2300,-817.5 2300,-772.5 2300,-772.5 2300,-766.5 2306,-760.5 2312,-760.5"/>
<text text-anchor="middle" x="2359.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_metrics</text>
<polyline fill="none" stroke="#000000" points="2419,-760.5 2419,-829.5 "/>
<text text-anchor="middle" x="2429.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2440,-760.5 2440,-829.5 "/>
<text text-anchor="middle" x="2503.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">metrics_source</text>
<polyline fill="none" stroke="#000000" points="2440,-806.5 2567,-806.5 "/>
<text text-anchor="middle" x="2503.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="2440,-783.5 2567,-783.5 "/>
<text text-anchor="middle" x="2503.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">specificity</text>
<polyline fill="none" stroke="#000000" points="2567,-760.5 2567,-829.5 "/>
<text text-anchor="middle" x="2577.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_metrics&#45;&gt;assay -->
<g id="edge20" class="edge">
<title>assay_metrics&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2444,-760.3096C2444,-716.9905 2444,-641.2442 2444,-580.9353"/>
<polygon fill="#000000" stroke="#000000" points="2447.5001,-580.6327 2444,-570.6328 2440.5001,-580.6328 2447.5001,-580.6327"/>
<text text-anchor="middle" x="2474.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- study&#45;&gt;project -->
<g id="edge5" class="edge">
<title>study&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M1051.6365,-288.4699C1042.4121,-282.711 1033.2661,-276.4858 1025,-270 1015.2633,-262.3602 1005.5953,-253.2848 996.8085,-244.2932"/>
<polygon fill="#000000" stroke="#000000" points="999.0882,-241.6123 989.6527,-236.7932 994.0236,-246.4445 999.0882,-241.6123"/>
<text text-anchor="middle" x="1061.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_project</text>
</g>
<!-- study&#45;&gt;center -->
<g id="edge17" class="edge">
<title>study&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M1114.678,-288.2559C1111.1509,-255.1021 1102.2809,-204.7554 1080,-167 1070.6464,-151.1501 1058.2417,-136.2856 1044.955,-122.9372"/>
<polygon fill="#000000" stroke="#000000" points="1047.1046,-120.1454 1037.4965,-115.6807 1042.2233,-125.1627 1047.1046,-120.1454"/>
<text text-anchor="middle" x="1139" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- comorbidity -->
<g id="node12" class="node">
<title>comorbidity</title>
<path fill="none" stroke="#000000" d="M1317.5,-772C1317.5,-772 1582.5,-772 1582.5,-772 1588.5,-772 1594.5,-778 1594.5,-784 1594.5,-784 1594.5,-806 1594.5,-806 1594.5,-812 1588.5,-818 1582.5,-818 1582.5,-818 1317.5,-818 1317.5,-818 1311.5,-818 1305.5,-812 1305.5,-806 1305.5,-806 1305.5,-784 1305.5,-784 1305.5,-778 1311.5,-772 1317.5,-772"/>
<text text-anchor="middle" x="1357" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1408.5,-772 1408.5,-818 "/>
<text text-anchor="middle" x="1419" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1429.5,-772 1429.5,-818 "/>
<text text-anchor="middle" x="1501.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1429.5,-795 1573.5,-795 "/>
<text text-anchor="middle" x="1501.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease</text>
<polyline fill="none" stroke="#000000" points="1573.5,-772 1573.5,-818 "/>
<text text-anchor="middle" x="1584" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- comorbidity&#45;&gt;participant -->
<g id="edge12" class="edge">
<title>comorbidity&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1435.2181,-771.7274C1410.7382,-734.9511 1358.3469,-663.3406 1297,-622 1211.0288,-564.0654 1096.8174,-528.6187 1017.3203,-509.2476"/>
<polygon fill="#000000" stroke="#000000" points="1017.8559,-505.7769 1007.3155,-506.8498 1016.2244,-512.5841 1017.8559,-505.7769"/>
<text text-anchor="middle" x="1310.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- aliquot -->
<g id="node13" class="node">
<title>aliquot</title>
<path fill="none" stroke="#000000" d="M1311.5,-1042.5C1311.5,-1042.5 1512.5,-1042.5 1512.5,-1042.5 1518.5,-1042.5 1524.5,-1048.5 1524.5,-1054.5 1524.5,-1054.5 1524.5,-1099.5 1524.5,-1099.5 1524.5,-1105.5 1518.5,-1111.5 1512.5,-1111.5 1512.5,-1111.5 1311.5,-1111.5 1311.5,-1111.5 1305.5,-1111.5 1299.5,-1105.5 1299.5,-1099.5 1299.5,-1099.5 1299.5,-1054.5 1299.5,-1054.5 1299.5,-1048.5 1305.5,-1042.5 1311.5,-1042.5"/>
<text text-anchor="middle" x="1332.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot</text>
<polyline fill="none" stroke="#000000" points="1365.5,-1042.5 1365.5,-1111.5 "/>
<text text-anchor="middle" x="1376" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1386.5,-1042.5 1386.5,-1111.5 "/>
<text text-anchor="middle" x="1445" y="-1096.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_type</text>
<polyline fill="none" stroke="#000000" points="1386.5,-1088.5 1503.5,-1088.5 "/>
<text text-anchor="middle" x="1445" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1386.5,-1065.5 1503.5,-1065.5 "/>
<text text-anchor="middle" x="1445" y="-1050.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="1503.5,-1042.5 1503.5,-1111.5 "/>
<text text-anchor="middle" x="1514" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- aliquot&#45;&gt;assay_run -->
<g id="edge2" class="edge">
<title>aliquot&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M1524.8699,-1047.4537C1605.4738,-1027.368 1716.7577,-1001.6898 1816,-986 1858.9837,-979.2044 1972.6285,-988.5282 2011,-968 2055.6588,-944.1081 2091.2901,-899.3235 2115.4295,-861.3071"/>
<polygon fill="#000000" stroke="#000000" points="2118.4044,-863.151 2120.7083,-852.8097 2112.4583,-859.4572 2118.4044,-863.151"/>
<text text-anchor="middle" x="1863" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- aliquot&#45;&gt;biospecimen -->
<g id="edge8" class="edge">
<title>aliquot&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M1372.8843,-1042.4213C1352.2666,-1024.1949 1325.2327,-1000.2966 1296.0965,-974.5399"/>
<polygon fill="#000000" stroke="#000000" points="1298.0486,-971.594 1288.2382,-967.593 1293.4123,-976.8386 1298.0486,-971.594"/>
<text text-anchor="middle" x="1373" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
<!-- cov2_diagnosis -->
<g id="node14" class="node">
<title>cov2_diagnosis</title>
<path fill="none" stroke="#000000" d="M1624.5,-749C1624.5,-749 1989.5,-749 1989.5,-749 1995.5,-749 2001.5,-755 2001.5,-761 2001.5,-761 2001.5,-829 2001.5,-829 2001.5,-835 1995.5,-841 1989.5,-841 1989.5,-841 1624.5,-841 1624.5,-841 1618.5,-841 1612.5,-835 1612.5,-829 1612.5,-829 1612.5,-761 1612.5,-761 1612.5,-755 1618.5,-749 1624.5,-749"/>
<text text-anchor="middle" x="1675" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">cov2_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1737.5,-749 1737.5,-841 "/>
<text text-anchor="middle" x="1748" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1758.5,-749 1758.5,-841 "/>
<text text-anchor="middle" x="1869.5" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1758.5,-818 1980.5,-818 "/>
<text text-anchor="middle" x="1869.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_symptom_onset</text>
<polyline fill="none" stroke="#000000" points="1758.5,-795 1980.5,-795 "/>
<text text-anchor="middle" x="1869.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_symptom_resolution</text>
<polyline fill="none" stroke="#000000" points="1758.5,-772 1980.5,-772 "/>
<text text-anchor="middle" x="1869.5" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1980.5,-749 1980.5,-841 "/>
<text text-anchor="middle" x="1991" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cov2_diagnosis&#45;&gt;participant -->
<g id="edge10" class="edge">
<title>cov2_diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1766.2314,-748.8331C1728.2708,-708.8856 1668.0448,-652.8282 1604,-622 1501.3662,-572.5969 1178.578,-524.131 1017.0288,-502.1917"/>
<polygon fill="#000000" stroke="#000000" points="1017.4761,-498.7204 1007.0972,-500.8488 1016.538,-505.6573 1017.4761,-498.7204"/>
<text text-anchor="middle" x="1601.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cov2_diagnosis&#45;&gt;assay_result -->
<g id="edge9" class="edge">
<title>cov2_diagnosis&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M1833.6115,-748.6614C1859.0748,-705.7261 1899.6269,-640.8624 1941,-589 1953.3327,-573.5406 1967.7014,-557.7506 1981.5083,-543.4527"/>
<polygon fill="#000000" stroke="#000000" points="1984.1836,-545.7227 1988.6635,-536.1216 1979.1741,-540.8334 1984.1836,-545.7227"/>
<text text-anchor="middle" x="2021" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_supporting_result</text>
</g>
<!-- serology -->
<g id="node15" class="node">
<title>serology</title>
<path fill="none" stroke="#000000" d="M12,-749C12,-749 280,-749 280,-749 286,-749 292,-755 292,-761 292,-761 292,-829 292,-829 292,-835 286,-841 280,-841 280,-841 12,-841 12,-841 6,-841 0,-835 0,-829 0,-829 0,-761 0,-761 0,-755 6,-749 12,-749"/>
<text text-anchor="middle" x="38.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">serology</text>
<polyline fill="none" stroke="#000000" points="77,-749 77,-841 "/>
<text text-anchor="middle" x="87.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="98,-749 98,-841 "/>
<text text-anchor="middle" x="184.5" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_serology_test</text>
<polyline fill="none" stroke="#000000" points="98,-818 271,-818 "/>
<text text-anchor="middle" x="184.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_current_infection</text>
<polyline fill="none" stroke="#000000" points="98,-795 271,-795 "/>
<text text-anchor="middle" x="184.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">infectious_agent</text>
<polyline fill="none" stroke="#000000" points="98,-772 271,-772 "/>
<text text-anchor="middle" x="184.5" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">serology_result</text>
<polyline fill="none" stroke="#000000" points="271,-749 271,-841 "/>
<text text-anchor="middle" x="281.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- serology&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>serology&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M174.8811,-748.9195C202.371,-709.0294 247.4253,-653.0078 301,-622 389.8433,-570.5795 677.8699,-524.2056 828.7896,-502.6836"/>
<polygon fill="#000000" stroke="#000000" points="829.5619,-506.1092 838.9714,-501.2397 828.579,-499.1785 829.5619,-506.1092"/>
<text text-anchor="middle" x="422.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- biospecimen&#45;&gt;participant -->
<g id="edge13" class="edge">
<title>biospecimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M996.8228,-622.4468C973.7734,-581.0934 951.8398,-541.742 937.9613,-516.8423"/>
<polygon fill="#000000" stroke="#000000" points="940.9768,-515.0635 933.051,-508.0327 934.8625,-518.4716 940.9768,-515.0635"/>
<text text-anchor="middle" x="1032.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- vaccination -->
<g id="node19" class="node">
<title>vaccination</title>
<path fill="none" stroke="#000000" d="M322,-772C322,-772 598,-772 598,-772 604,-772 610,-778 610,-784 610,-784 610,-806 610,-806 610,-812 604,-818 598,-818 598,-818 322,-818 322,-818 316,-818 310,-812 310,-806 310,-806 310,-784 310,-784 310,-778 316,-772 322,-772"/>
<text text-anchor="middle" x="359.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">vaccination</text>
<polyline fill="none" stroke="#000000" points="409,-772 409,-818 "/>
<text text-anchor="middle" x="419.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="430,-772 430,-818 "/>
<text text-anchor="middle" x="509.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_vaccination</text>
<polyline fill="none" stroke="#000000" points="430,-795 589,-795 "/>
<text text-anchor="middle" x="509.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">infectious_agent</text>
<polyline fill="none" stroke="#000000" points="589,-772 589,-818 "/>
<text text-anchor="middle" x="599.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- vaccination&#45;&gt;participant -->
<g id="edge11" class="edge">
<title>vaccination&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M476.1455,-771.9728C502.4633,-735.8555 557.8496,-665.5261 619,-622 691.6774,-570.2691 787.8268,-532.7818 852.3605,-511.2597"/>
<polygon fill="#000000" stroke="#000000" points="853.638,-514.524 862.0415,-508.0717 851.4485,-507.8752 853.638,-514.524"/>
<text text-anchor="middle" x="714.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
</g>
</svg>
</div>
