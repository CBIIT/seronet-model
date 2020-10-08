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
<svg width="1374pt" height="1028pt"
 viewBox="0.00 0.00 1373.50 1028.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1024)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1024 1369.5,-1024 1369.5,4 -4,4"/>
<!-- assay_result -->
<g id="node1" class="node">
<title>assay_result</title>
<path fill="none" stroke="#000000" d="M789,-432.5C789,-432.5 1031,-432.5 1031,-432.5 1037,-432.5 1043,-438.5 1043,-444.5 1043,-444.5 1043,-512.5 1043,-512.5 1043,-518.5 1037,-524.5 1031,-524.5 1031,-524.5 789,-524.5 789,-524.5 783,-524.5 777,-518.5 777,-512.5 777,-512.5 777,-444.5 777,-444.5 777,-438.5 783,-432.5 789,-432.5"/>
<text text-anchor="middle" x="830" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay_result</text>
<polyline fill="none" stroke="#000000" points="883,-432.5 883,-524.5 "/>
<text text-anchor="middle" x="893.5" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="904,-432.5 904,-524.5 "/>
<text text-anchor="middle" x="963" y="-509.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="904,-501.5 1022,-501.5 "/>
<text text-anchor="middle" x="963" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">readout_type</text>
<polyline fill="none" stroke="#000000" points="904,-478.5 1022,-478.5 "/>
<text text-anchor="middle" x="963" y="-463.3" font-family="Times,serif" font-size="14.00" fill="#000000">readout_value</text>
<polyline fill="none" stroke="#000000" points="904,-455.5 1022,-455.5 "/>
<text text-anchor="middle" x="963" y="-440.3" font-family="Times,serif" font-size="14.00" fill="#000000">type</text>
<polyline fill="none" stroke="#000000" points="1022,-432.5 1022,-524.5 "/>
<text text-anchor="middle" x="1032.5" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop -->
<g id="node2" class="node">
<title>sop</title>
<path fill="none" stroke="#000000" d="M992,-904.5C992,-904.5 1162,-904.5 1162,-904.5 1168,-904.5 1174,-910.5 1174,-916.5 1174,-916.5 1174,-1007.5 1174,-1007.5 1174,-1013.5 1168,-1019.5 1162,-1019.5 1162,-1019.5 992,-1019.5 992,-1019.5 986,-1019.5 980,-1013.5 980,-1007.5 980,-1007.5 980,-916.5 980,-916.5 980,-910.5 986,-904.5 992,-904.5"/>
<text text-anchor="middle" x="1000.5" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000">sop</text>
<polyline fill="none" stroke="#000000" points="1021,-904.5 1021,-1019.5 "/>
<text text-anchor="middle" x="1031.5" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1042,-904.5 1042,-1019.5 "/>
<text text-anchor="middle" x="1097.5" y="-1004.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1042,-996.5 1153,-996.5 "/>
<text text-anchor="middle" x="1097.5" y="-981.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1042,-973.5 1153,-973.5 "/>
<text text-anchor="middle" x="1097.5" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000">process_type</text>
<polyline fill="none" stroke="#000000" points="1042,-950.5 1153,-950.5 "/>
<text text-anchor="middle" x="1097.5" y="-935.3" font-family="Times,serif" font-size="14.00" fill="#000000">url</text>
<polyline fill="none" stroke="#000000" points="1042,-927.5 1153,-927.5 "/>
<text text-anchor="middle" x="1097.5" y="-912.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="1153,-904.5 1153,-1019.5 "/>
<text text-anchor="middle" x="1163.5" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_run -->
<g id="node5" class="node">
<title>assay_run</title>
<path fill="none" stroke="#000000" d="M958,-668.5C958,-668.5 1196,-668.5 1196,-668.5 1202,-668.5 1208,-674.5 1208,-680.5 1208,-680.5 1208,-771.5 1208,-771.5 1208,-777.5 1202,-783.5 1196,-783.5 1196,-783.5 958,-783.5 958,-783.5 952,-783.5 946,-777.5 946,-771.5 946,-771.5 946,-680.5 946,-680.5 946,-674.5 952,-668.5 958,-668.5"/>
<text text-anchor="middle" x="990.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_run</text>
<polyline fill="none" stroke="#000000" points="1035,-668.5 1035,-783.5 "/>
<text text-anchor="middle" x="1045.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1056,-668.5 1056,-783.5 "/>
<text text-anchor="middle" x="1121.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_performed</text>
<polyline fill="none" stroke="#000000" points="1056,-760.5 1187,-760.5 "/>
<text text-anchor="middle" x="1121.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1056,-737.5 1187,-737.5 "/>
<text text-anchor="middle" x="1121.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_clia</text>
<polyline fill="none" stroke="#000000" points="1056,-714.5 1187,-714.5 "/>
<text text-anchor="middle" x="1121.5" y="-699.3" font-family="Times,serif" font-size="14.00" fill="#000000">operator</text>
<polyline fill="none" stroke="#000000" points="1056,-691.5 1187,-691.5 "/>
<text text-anchor="middle" x="1121.5" y="-676.3" font-family="Times,serif" font-size="14.00" fill="#000000">variances</text>
<polyline fill="none" stroke="#000000" points="1187,-668.5 1187,-783.5 "/>
<text text-anchor="middle" x="1197.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;assay_run -->
<g id="edge18" class="edge">
<title>sop&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M1077,-904.2679C1077,-870.8582 1077,-828.6373 1077,-793.6717"/>
<polygon fill="#000000" stroke="#000000" points="1080.5001,-793.5446 1077,-783.5446 1073.5001,-793.5446 1080.5001,-793.5446"/>
<text text-anchor="middle" x="1124" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- biospecimen -->
<g id="node12" class="node">
<title>biospecimen</title>
<path fill="none" stroke="#000000" d="M12,-599.5C12,-599.5 378,-599.5 378,-599.5 384,-599.5 390,-605.5 390,-611.5 390,-611.5 390,-840.5 390,-840.5 390,-846.5 384,-852.5 378,-852.5 378,-852.5 12,-852.5 12,-852.5 6,-852.5 0,-846.5 0,-840.5 0,-840.5 0,-611.5 0,-611.5 0,-605.5 6,-599.5 12,-599.5"/>
<text text-anchor="middle" x="53.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen</text>
<polyline fill="none" stroke="#000000" points="107,-599.5 107,-852.5 "/>
<text text-anchor="middle" x="117.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="128,-599.5 128,-852.5 "/>
<text text-anchor="middle" x="248.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_last_aliquotted</text>
<polyline fill="none" stroke="#000000" points="128,-829.5 369,-829.5 "/>
<text text-anchor="middle" x="248.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_collection</text>
<polyline fill="none" stroke="#000000" points="128,-806.5 369,-806.5 "/>
<text text-anchor="middle" x="248.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_processing</text>
<polyline fill="none" stroke="#000000" points="128,-783.5 369,-783.5 "/>
<text text-anchor="middle" x="248.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_swab_collection</text>
<polyline fill="none" stroke="#000000" points="128,-760.5 369,-760.5 "/>
<text text-anchor="middle" x="248.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_onset</text>
<polyline fill="none" stroke="#000000" points="128,-737.5 369,-737.5 "/>
<text text-anchor="middle" x="248.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_resolution</text>
<polyline fill="none" stroke="#000000" points="128,-714.5 369,-714.5 "/>
<text text-anchor="middle" x="248.5" y="-699.3" font-family="Times,serif" font-size="14.00" fill="#000000">freeze_thaw_cycle</text>
<polyline fill="none" stroke="#000000" points="128,-691.5 369,-691.5 "/>
<text text-anchor="middle" x="248.5" y="-676.3" font-family="Times,serif" font-size="14.00" fill="#000000">group</text>
<polyline fill="none" stroke="#000000" points="128,-668.5 369,-668.5 "/>
<text text-anchor="middle" x="248.5" y="-653.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="128,-645.5 369,-645.5 "/>
<text text-anchor="middle" x="248.5" y="-630.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="128,-622.5 369,-622.5 "/>
<text text-anchor="middle" x="248.5" y="-607.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="369,-599.5 369,-852.5 "/>
<text text-anchor="middle" x="379.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;biospecimen -->
<g id="edge5" class="edge">
<title>sop&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M979.5262,-927.5578C951.5569,-918.7391 920.8241,-910.0493 892,-904 826.5773,-890.2699 659.5057,-877.7549 593,-871 509.9635,-862.5662 483.0104,-879.3309 399.7134,-853.0039"/>
<polygon fill="#000000" stroke="#000000" points="400.6949,-849.6425 390.1022,-849.8578 398.5172,-856.2951 400.6949,-849.6425"/>
<text text-anchor="middle" x="805" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
<!-- assay -->
<g id="node14" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M1108.5,-409.5C1108.5,-409.5 1297.5,-409.5 1297.5,-409.5 1303.5,-409.5 1309.5,-415.5 1309.5,-421.5 1309.5,-421.5 1309.5,-535.5 1309.5,-535.5 1309.5,-541.5 1303.5,-547.5 1297.5,-547.5 1297.5,-547.5 1108.5,-547.5 1108.5,-547.5 1102.5,-547.5 1096.5,-541.5 1096.5,-535.5 1096.5,-535.5 1096.5,-421.5 1096.5,-421.5 1096.5,-415.5 1102.5,-409.5 1108.5,-409.5"/>
<text text-anchor="middle" x="1124.5" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
<polyline fill="none" stroke="#000000" points="1152.5,-409.5 1152.5,-547.5 "/>
<text text-anchor="middle" x="1163" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1173.5,-409.5 1173.5,-547.5 "/>
<text text-anchor="middle" x="1231" y="-532.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="1173.5,-524.5 1288.5,-524.5 "/>
<text text-anchor="middle" x="1231" y="-509.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="1173.5,-501.5 1288.5,-501.5 "/>
<text text-anchor="middle" x="1231" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_type</text>
<polyline fill="none" stroke="#000000" points="1173.5,-478.5 1288.5,-478.5 "/>
<text text-anchor="middle" x="1231" y="-463.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1173.5,-455.5 1288.5,-455.5 "/>
<text text-anchor="middle" x="1231" y="-440.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer</text>
<polyline fill="none" stroke="#000000" points="1173.5,-432.5 1288.5,-432.5 "/>
<text text-anchor="middle" x="1231" y="-417.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="1288.5,-409.5 1288.5,-547.5 "/>
<text text-anchor="middle" x="1299" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;assay -->
<g id="edge9" class="edge">
<title>sop&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M1174.1576,-905.4833C1191.4563,-890.7259 1207.096,-873.1881 1217,-853 1262.8245,-759.5927 1245.9377,-636.7536 1226.8048,-557.6984"/>
<polygon fill="#000000" stroke="#000000" points="1230.1532,-556.66 1224.3422,-547.8009 1223.3603,-558.3501 1230.1532,-556.66"/>
<text text-anchor="middle" x="1276.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- demographic -->
<g id="node3" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M420,-680C420,-680 628,-680 628,-680 634,-680 640,-686 640,-692 640,-692 640,-760 640,-760 640,-766 634,-772 628,-772 628,-772 420,-772 420,-772 414,-772 408,-766 408,-760 408,-760 408,-692 408,-692 408,-686 414,-680 420,-680"/>
<text text-anchor="middle" x="463" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="518,-680 518,-772 "/>
<text text-anchor="middle" x="528.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="539,-680 539,-772 "/>
<text text-anchor="middle" x="579" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">age</text>
<polyline fill="none" stroke="#000000" points="539,-749 619,-749 "/>
<text text-anchor="middle" x="579" y="-733.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="539,-726 619,-726 "/>
<text text-anchor="middle" x="579" y="-710.8" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="539,-703 619,-703 "/>
<text text-anchor="middle" x="579" y="-687.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="619,-680 619,-772 "/>
<text text-anchor="middle" x="629.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant -->
<g id="node11" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M452,-460.5C452,-460.5 596,-460.5 596,-460.5 602,-460.5 608,-466.5 608,-472.5 608,-472.5 608,-484.5 608,-484.5 608,-490.5 602,-496.5 596,-496.5 596,-496.5 452,-496.5 452,-496.5 446,-496.5 440,-490.5 440,-484.5 440,-484.5 440,-472.5 440,-472.5 440,-466.5 446,-460.5 452,-460.5"/>
<text text-anchor="middle" x="488" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="536,-460.5 536,-496.5 "/>
<text text-anchor="middle" x="546.5" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="557,-460.5 557,-496.5 "/>
<text text-anchor="middle" x="572" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="587,-460.5 587,-496.5 "/>
<text text-anchor="middle" x="597.5" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;participant -->
<g id="edge16" class="edge">
<title>demographic&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M524,-679.7375C524,-628.8974 524,-548.8606 524,-506.6765"/>
<polygon fill="#000000" stroke="#000000" points="527.5001,-506.5649 524,-496.565 520.5001,-506.565 527.5001,-506.5649"/>
<text text-anchor="middle" x="574.5" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M670,-691.5C670,-691.5 916,-691.5 916,-691.5 922,-691.5 928,-697.5 928,-703.5 928,-703.5 928,-748.5 928,-748.5 928,-754.5 922,-760.5 916,-760.5 916,-760.5 670,-760.5 670,-760.5 664,-760.5 658,-754.5 658,-748.5 658,-748.5 658,-703.5 658,-703.5 658,-697.5 664,-691.5 670,-691.5"/>
<text text-anchor="middle" x="700" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="742,-691.5 742,-760.5 "/>
<text text-anchor="middle" x="752.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="763,-691.5 763,-760.5 "/>
<text text-anchor="middle" x="835" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="763,-737.5 907,-737.5 "/>
<text text-anchor="middle" x="835" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease</text>
<polyline fill="none" stroke="#000000" points="763,-714.5 907,-714.5 "/>
<text text-anchor="middle" x="835" y="-699.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_comorbidity</text>
<polyline fill="none" stroke="#000000" points="907,-691.5 907,-760.5 "/>
<text text-anchor="middle" x="917.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;assay_result -->
<g id="edge6" class="edge">
<title>diagnosis&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M793.6706,-691.3072C795.6243,-657.5366 802.1582,-605.6511 823,-566 829.3361,-553.9458 837.8901,-542.4826 847.1699,-532.0603"/>
<polygon fill="#000000" stroke="#000000" points="849.7985,-534.3731 854.0339,-524.6616 844.6668,-529.6122 849.7985,-534.3731"/>
<text text-anchor="middle" x="903" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_supporting_result</text>
</g>
<!-- diagnosis&#45;&gt;participant -->
<g id="edge15" class="edge">
<title>diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M759.1964,-691.4885C726.5504,-658.5294 675.3744,-607.8277 629,-566 604.7333,-544.1124 576.1882,-520.4514 554.991,-503.2593"/>
<polygon fill="#000000" stroke="#000000" points="556.9431,-500.3369 546.9652,-496.7742 552.5436,-505.7816 556.9431,-500.3369"/>
<text text-anchor="middle" x="692.5" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- assay_run&#45;&gt;assay_result -->
<g id="edge8" class="edge">
<title>assay_run&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M1046.1357,-668.3089C1028.7641,-637.2298 1005.9914,-598.6698 983,-566 975.1207,-554.8038 966.1668,-543.2668 957.2951,-532.3913"/>
<polygon fill="#000000" stroke="#000000" points="959.9316,-530.0871 950.8662,-524.6035 954.5333,-534.5435 959.9316,-530.0871"/>
<text text-anchor="middle" x="1052" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_assay_result</text>
</g>
<!-- assay_run&#45;&gt;assay -->
<g id="edge10" class="edge">
<title>assay_run&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M1106.3824,-668.2846C1123.2759,-635.101 1144.7302,-592.9585 1163.1287,-556.8187"/>
<polygon fill="#000000" stroke="#000000" points="1166.3179,-558.2686 1167.7357,-547.7691 1160.0798,-555.0928 1166.3179,-558.2686"/>
<text text-anchor="middle" x="1184.5" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- center -->
<g id="node6" class="node">
<title>center</title>
<path fill="none" stroke="#000000" d="M315.5,-.5C315.5,-.5 570.5,-.5 570.5,-.5 576.5,-.5 582.5,-6.5 582.5,-12.5 582.5,-12.5 582.5,-103.5 582.5,-103.5 582.5,-109.5 576.5,-115.5 570.5,-115.5 570.5,-115.5 315.5,-115.5 315.5,-115.5 309.5,-115.5 303.5,-109.5 303.5,-103.5 303.5,-103.5 303.5,-12.5 303.5,-12.5 303.5,-6.5 309.5,-.5 315.5,-.5"/>
<text text-anchor="middle" x="335" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">center</text>
<polyline fill="none" stroke="#000000" points="366.5,-.5 366.5,-115.5 "/>
<text text-anchor="middle" x="377" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="387.5,-.5 387.5,-115.5 "/>
<text text-anchor="middle" x="474.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">center_type</text>
<polyline fill="none" stroke="#000000" points="387.5,-92.5 561.5,-92.5 "/>
<text text-anchor="middle" x="474.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="387.5,-69.5 561.5,-69.5 "/>
<text text-anchor="middle" x="474.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="387.5,-46.5 561.5,-46.5 "/>
<text text-anchor="middle" x="474.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">principal_investigator</text>
<polyline fill="none" stroke="#000000" points="387.5,-23.5 561.5,-23.5 "/>
<text text-anchor="middle" x="474.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="561.5,-.5 561.5,-115.5 "/>
<text text-anchor="middle" x="572" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- workflow -->
<g id="node7" class="node">
<title>workflow</title>
<path fill="none" stroke="#000000" d="M1204.5,-939C1204.5,-939 1353.5,-939 1353.5,-939 1359.5,-939 1365.5,-945 1365.5,-951 1365.5,-951 1365.5,-973 1365.5,-973 1365.5,-979 1359.5,-985 1353.5,-985 1353.5,-985 1204.5,-985 1204.5,-985 1198.5,-985 1192.5,-979 1192.5,-973 1192.5,-973 1192.5,-951 1192.5,-951 1192.5,-945 1198.5,-939 1204.5,-939"/>
<text text-anchor="middle" x="1234" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000">workflow</text>
<polyline fill="none" stroke="#000000" points="1275.5,-939 1275.5,-985 "/>
<text text-anchor="middle" x="1286" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1296.5,-939 1296.5,-985 "/>
<text text-anchor="middle" x="1320.5" y="-969.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1296.5,-962 1344.5,-962 "/>
<text text-anchor="middle" x="1320.5" y="-946.8" font-family="Times,serif" font-size="14.00" fill="#000000">type</text>
<polyline fill="none" stroke="#000000" points="1344.5,-939 1344.5,-985 "/>
<text text-anchor="middle" x="1355" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M233.5,-288.5C233.5,-288.5 418.5,-288.5 418.5,-288.5 424.5,-288.5 430.5,-294.5 430.5,-300.5 430.5,-300.5 430.5,-345.5 430.5,-345.5 430.5,-351.5 424.5,-357.5 418.5,-357.5 418.5,-357.5 233.5,-357.5 233.5,-357.5 227.5,-357.5 221.5,-351.5 221.5,-345.5 221.5,-345.5 221.5,-300.5 221.5,-300.5 221.5,-294.5 227.5,-288.5 233.5,-288.5"/>
<text text-anchor="middle" x="249.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="277.5,-288.5 277.5,-357.5 "/>
<text text-anchor="middle" x="288" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="298.5,-288.5 298.5,-357.5 "/>
<text text-anchor="middle" x="354" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="298.5,-334.5 409.5,-334.5 "/>
<text text-anchor="middle" x="354" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="298.5,-311.5 409.5,-311.5 "/>
<text text-anchor="middle" x="354" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="409.5,-288.5 409.5,-357.5 "/>
<text text-anchor="middle" x="420" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;center -->
<g id="edge1" class="edge">
<title>study&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M287.8363,-288.0886C274.8061,-273.6951 261.8112,-255.9488 255,-237 244.4762,-207.7229 239.469,-193.9572 255,-167 265.116,-149.4416 279.2628,-134.4528 295.3038,-121.7284"/>
<polygon fill="#000000" stroke="#000000" points="297.4583,-124.4872 303.3212,-115.6624 293.2348,-118.9049 297.4583,-124.4872"/>
<text text-anchor="middle" x="289" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- project -->
<g id="node9" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M344.5,-167.5C344.5,-167.5 541.5,-167.5 541.5,-167.5 547.5,-167.5 553.5,-173.5 553.5,-179.5 553.5,-179.5 553.5,-224.5 553.5,-224.5 553.5,-230.5 547.5,-236.5 541.5,-236.5 541.5,-236.5 344.5,-236.5 344.5,-236.5 338.5,-236.5 332.5,-230.5 332.5,-224.5 332.5,-224.5 332.5,-179.5 332.5,-179.5 332.5,-173.5 338.5,-167.5 344.5,-167.5"/>
<text text-anchor="middle" x="366.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="400.5,-167.5 400.5,-236.5 "/>
<text text-anchor="middle" x="411" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="421.5,-167.5 421.5,-236.5 "/>
<text text-anchor="middle" x="477" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="421.5,-213.5 532.5,-213.5 "/>
<text text-anchor="middle" x="477" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="421.5,-190.5 532.5,-190.5 "/>
<text text-anchor="middle" x="477" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="532.5,-167.5 532.5,-236.5 "/>
<text text-anchor="middle" x="543" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;project -->
<g id="edge3" class="edge">
<title>study&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M351.3649,-288.3276C360.0073,-277.2806 370.0173,-265.2689 380,-255 383.7984,-251.0927 387.8627,-247.1738 392.0295,-243.3332"/>
<polygon fill="#000000" stroke="#000000" points="394.5071,-245.8123 399.605,-236.5245 389.8279,-240.606 394.5071,-245.8123"/>
<text text-anchor="middle" x="416.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_project</text>
</g>
<!-- project&#45;&gt;center -->
<g id="edge2" class="edge">
<title>project&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M443,-167.1416C443,-154.6834 443,-140.1822 443,-125.8971"/>
<polygon fill="#000000" stroke="#000000" points="446.5001,-125.5658 443,-115.5658 439.5001,-125.5658 446.5001,-125.5658"/>
<text text-anchor="middle" x="477" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- cohort -->
<g id="node10" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M622.5,-288.5C622.5,-288.5 801.5,-288.5 801.5,-288.5 807.5,-288.5 813.5,-294.5 813.5,-300.5 813.5,-300.5 813.5,-345.5 813.5,-345.5 813.5,-351.5 807.5,-357.5 801.5,-357.5 801.5,-357.5 622.5,-357.5 622.5,-357.5 616.5,-357.5 610.5,-351.5 610.5,-345.5 610.5,-345.5 610.5,-300.5 610.5,-300.5 610.5,-294.5 616.5,-288.5 622.5,-288.5"/>
<text text-anchor="middle" x="642" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="673.5,-288.5 673.5,-357.5 "/>
<text text-anchor="middle" x="684" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="694.5,-288.5 694.5,-357.5 "/>
<text text-anchor="middle" x="743.5" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">description</text>
<polyline fill="none" stroke="#000000" points="694.5,-334.5 792.5,-334.5 "/>
<text text-anchor="middle" x="743.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="694.5,-311.5 792.5,-311.5 "/>
<text text-anchor="middle" x="743.5" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="792.5,-288.5 792.5,-357.5 "/>
<text text-anchor="middle" x="803" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;center -->
<g id="edge7" class="edge">
<title>participant&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M532.753,-460.2113C555.2557,-410.4169 610.0888,-269.3095 562,-167 554.408,-150.8479 543.2257,-135.9849 530.7101,-122.7697"/>
<polygon fill="#000000" stroke="#000000" points="533.1495,-120.2588 523.6341,-115.5997 528.1672,-125.1758 533.1495,-120.2588"/>
<text text-anchor="middle" x="621.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_at</text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge13" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M476.8812,-460.3847C443.0156,-445.5961 397.8905,-422.0729 366,-391 358.7162,-383.9029 352.2926,-375.2023 346.843,-366.4255"/>
<polygon fill="#000000" stroke="#000000" points="349.7955,-364.5409 341.7224,-357.6797 343.7547,-368.0778 349.7955,-364.5409"/>
<text text-anchor="middle" x="409.5" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- participant&#45;&gt;project -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M516.8458,-460.3227C507.7828,-436.9011 492.0196,-394.8132 481,-358 469.8559,-320.7707 459.5799,-277.8257 452.5316,-246.4312"/>
<polygon fill="#000000" stroke="#000000" points="455.9473,-245.6674 450.3596,-236.6659 449.1143,-247.1873 455.9473,-245.6674"/>
<text text-anchor="middle" x="524.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- participant&#45;&gt;cohort -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M545.9339,-460.3578C574.2379,-436.9469 624.3274,-395.5164 662.1155,-364.2608"/>
<polygon fill="#000000" stroke="#000000" points="664.5052,-366.8264 669.9801,-357.7558 660.0436,-361.4324 664.5052,-366.8264"/>
<text text-anchor="middle" x="679" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cohort</text>
</g>
<!-- biospecimen&#45;&gt;participant -->
<g id="edge14" class="edge">
<title>biospecimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M363.3552,-599.3498C412.4884,-562.3879 461.1628,-525.7712 491.8326,-502.6989"/>
<polygon fill="#000000" stroke="#000000" points="494.1039,-505.3701 499.991,-496.5614 489.8957,-499.7762 494.1039,-505.3701"/>
<text text-anchor="middle" x="449.5" y="-569.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- aliquot -->
<g id="node13" class="node">
<title>aliquot</title>
<path fill="none" stroke="#000000" d="M669.5,-927.5C669.5,-927.5 870.5,-927.5 870.5,-927.5 876.5,-927.5 882.5,-933.5 882.5,-939.5 882.5,-939.5 882.5,-984.5 882.5,-984.5 882.5,-990.5 876.5,-996.5 870.5,-996.5 870.5,-996.5 669.5,-996.5 669.5,-996.5 663.5,-996.5 657.5,-990.5 657.5,-984.5 657.5,-984.5 657.5,-939.5 657.5,-939.5 657.5,-933.5 663.5,-927.5 669.5,-927.5"/>
<text text-anchor="middle" x="690.5" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot</text>
<polyline fill="none" stroke="#000000" points="723.5,-927.5 723.5,-996.5 "/>
<text text-anchor="middle" x="734" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="744.5,-927.5 744.5,-996.5 "/>
<text text-anchor="middle" x="803" y="-981.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_type</text>
<polyline fill="none" stroke="#000000" points="744.5,-973.5 861.5,-973.5 "/>
<text text-anchor="middle" x="803" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="744.5,-950.5 861.5,-950.5 "/>
<text text-anchor="middle" x="803" y="-935.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="861.5,-927.5 861.5,-996.5 "/>
<text text-anchor="middle" x="872" y="-958.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- aliquot&#45;&gt;assay_run -->
<g id="edge17" class="edge">
<title>aliquot&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M827.9666,-927.3317C860.8246,-906.9081 902.1967,-879.8722 937,-853 961.7367,-833.9003 987.4436,-811.4355 1009.9755,-790.7525"/>
<polygon fill="#000000" stroke="#000000" points="1012.5169,-793.1697 1017.489,-783.814 1007.7679,-788.0271 1012.5169,-793.1697"/>
<text text-anchor="middle" x="957" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- aliquot&#45;&gt;biospecimen -->
<g id="edge4" class="edge">
<title>aliquot&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M657.416,-937.8551C584.7589,-920.2061 488.9288,-893.0221 399.3617,-853.0272"/>
<polygon fill="#000000" stroke="#000000" points="400.7104,-849.7959 390.1569,-848.8611 397.824,-856.1731 400.7104,-849.7959"/>
<text text-anchor="middle" x="533" y="-874.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
</g>
</svg>
</div>
