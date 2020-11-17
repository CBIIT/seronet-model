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
<svg width="3269pt" height="1143pt"
 viewBox="0.00 0.00 3269.00 1143.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 1139)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-1139 3265,-1139 3265,4 -4,4"/>
<!-- serology -->
<g id="node1" class="node">
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
<!-- participant -->
<g id="node13" class="node">
<title>participant</title>
<path fill="none" stroke="#000000" d="M916,-472C916,-472 1060,-472 1060,-472 1066,-472 1072,-478 1072,-484 1072,-484 1072,-496 1072,-496 1072,-502 1066,-508 1060,-508 1060,-508 916,-508 916,-508 910,-508 904,-502 904,-496 904,-496 904,-484 904,-484 904,-478 910,-472 916,-472"/>
<text text-anchor="middle" x="952" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">participant</text>
<polyline fill="none" stroke="#000000" points="1000,-472 1000,-508 "/>
<text text-anchor="middle" x="1010.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1021,-472 1021,-508 "/>
<text text-anchor="middle" x="1036" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1051,-472 1051,-508 "/>
<text text-anchor="middle" x="1061.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- serology&#45;&gt;participant -->
<g id="edge7" class="edge">
<title>serology&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M174.7385,-748.6703C202.1335,-708.6145 247.1287,-652.4897 301,-622 401.2301,-565.2725 730.0043,-520.1499 893.6847,-500.5718"/>
<polygon fill="#000000" stroke="#000000" points="894.2281,-504.0319 903.745,-499.3757 893.4017,-497.0808 894.2281,-504.0319"/>
<text text-anchor="middle" x="430.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M697.5,-288.5C697.5,-288.5 882.5,-288.5 882.5,-288.5 888.5,-288.5 894.5,-294.5 894.5,-300.5 894.5,-300.5 894.5,-345.5 894.5,-345.5 894.5,-351.5 888.5,-357.5 882.5,-357.5 882.5,-357.5 697.5,-357.5 697.5,-357.5 691.5,-357.5 685.5,-351.5 685.5,-345.5 685.5,-345.5 685.5,-300.5 685.5,-300.5 685.5,-294.5 691.5,-288.5 697.5,-288.5"/>
<text text-anchor="middle" x="713.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="741.5,-288.5 741.5,-357.5 "/>
<text text-anchor="middle" x="752" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="762.5,-288.5 762.5,-357.5 "/>
<text text-anchor="middle" x="818" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="762.5,-334.5 873.5,-334.5 "/>
<text text-anchor="middle" x="818" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="762.5,-311.5 873.5,-311.5 "/>
<text text-anchor="middle" x="818" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="873.5,-288.5 873.5,-357.5 "/>
<text text-anchor="middle" x="884" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- center -->
<g id="node6" class="node">
<title>center</title>
<path fill="none" stroke="#000000" d="M779.5,-.5C779.5,-.5 1034.5,-.5 1034.5,-.5 1040.5,-.5 1046.5,-6.5 1046.5,-12.5 1046.5,-12.5 1046.5,-103.5 1046.5,-103.5 1046.5,-109.5 1040.5,-115.5 1034.5,-115.5 1034.5,-115.5 779.5,-115.5 779.5,-115.5 773.5,-115.5 767.5,-109.5 767.5,-103.5 767.5,-103.5 767.5,-12.5 767.5,-12.5 767.5,-6.5 773.5,-.5 779.5,-.5"/>
<text text-anchor="middle" x="799" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">center</text>
<polyline fill="none" stroke="#000000" points="830.5,-.5 830.5,-115.5 "/>
<text text-anchor="middle" x="841" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="851.5,-.5 851.5,-115.5 "/>
<text text-anchor="middle" x="938.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">center_type</text>
<polyline fill="none" stroke="#000000" points="851.5,-92.5 1025.5,-92.5 "/>
<text text-anchor="middle" x="938.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="851.5,-69.5 1025.5,-69.5 "/>
<text text-anchor="middle" x="938.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="851.5,-46.5 1025.5,-46.5 "/>
<text text-anchor="middle" x="938.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">principal_investigator</text>
<polyline fill="none" stroke="#000000" points="851.5,-23.5 1025.5,-23.5 "/>
<text text-anchor="middle" x="938.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1025.5,-.5 1025.5,-115.5 "/>
<text text-anchor="middle" x="1036" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;center -->
<g id="edge14" class="edge">
<title>study&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M752.7356,-288.414C739.7642,-273.9358 726.7715,-256.0459 720,-237 709.5781,-207.6864 704.5003,-193.9752 720,-167 730.0555,-149.4998 744.1232,-134.5448 760.0768,-121.8374"/>
<polygon fill="#000000" stroke="#000000" points="762.2061,-124.6153 768.0508,-115.7785 757.971,-119.0417 762.2061,-124.6153"/>
<text text-anchor="middle" x="754" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- project -->
<g id="node7" class="node">
<title>project</title>
<path fill="none" stroke="#000000" d="M808.5,-167.5C808.5,-167.5 1005.5,-167.5 1005.5,-167.5 1011.5,-167.5 1017.5,-173.5 1017.5,-179.5 1017.5,-179.5 1017.5,-224.5 1017.5,-224.5 1017.5,-230.5 1011.5,-236.5 1005.5,-236.5 1005.5,-236.5 808.5,-236.5 808.5,-236.5 802.5,-236.5 796.5,-230.5 796.5,-224.5 796.5,-224.5 796.5,-179.5 796.5,-179.5 796.5,-173.5 802.5,-167.5 808.5,-167.5"/>
<text text-anchor="middle" x="830.5" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">project</text>
<polyline fill="none" stroke="#000000" points="864.5,-167.5 864.5,-236.5 "/>
<text text-anchor="middle" x="875" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="885.5,-167.5 885.5,-236.5 "/>
<text text-anchor="middle" x="941" y="-221.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="885.5,-213.5 996.5,-213.5 "/>
<text text-anchor="middle" x="941" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000">irb_approved</text>
<polyline fill="none" stroke="#000000" points="885.5,-190.5 996.5,-190.5 "/>
<text text-anchor="middle" x="941" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">protocol</text>
<polyline fill="none" stroke="#000000" points="996.5,-167.5 996.5,-236.5 "/>
<text text-anchor="middle" x="1007" y="-198.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;project -->
<g id="edge10" class="edge">
<title>study&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M815.3649,-288.3276C824.0073,-277.2806 834.0173,-265.2689 844,-255 847.7984,-251.0927 851.8627,-247.1738 856.0295,-243.3332"/>
<polygon fill="#000000" stroke="#000000" points="858.5071,-245.8123 863.605,-236.5245 853.8279,-240.606 858.5071,-245.8123"/>
<text text-anchor="middle" x="880.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_project</text>
</g>
<!-- comorbidity -->
<g id="node3" class="node">
<title>comorbidity</title>
<path fill="none" stroke="#000000" d="M1000.5,-772C1000.5,-772 1265.5,-772 1265.5,-772 1271.5,-772 1277.5,-778 1277.5,-784 1277.5,-784 1277.5,-806 1277.5,-806 1277.5,-812 1271.5,-818 1265.5,-818 1265.5,-818 1000.5,-818 1000.5,-818 994.5,-818 988.5,-812 988.5,-806 988.5,-806 988.5,-784 988.5,-784 988.5,-778 994.5,-772 1000.5,-772"/>
<text text-anchor="middle" x="1040" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">comorbidity</text>
<polyline fill="none" stroke="#000000" points="1091.5,-772 1091.5,-818 "/>
<text text-anchor="middle" x="1102" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1112.5,-772 1112.5,-818 "/>
<text text-anchor="middle" x="1184.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1112.5,-795 1256.5,-795 "/>
<text text-anchor="middle" x="1184.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">disease</text>
<polyline fill="none" stroke="#000000" points="1256.5,-772 1256.5,-818 "/>
<text text-anchor="middle" x="1267" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- comorbidity&#45;&gt;participant -->
<g id="edge4" class="edge">
<title>comorbidity&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1123.5166,-771.8497C1107.6106,-733.4232 1074.1322,-654.2384 1042,-589 1029.7527,-564.1342 1014.5359,-536.4926 1003.3799,-516.7506"/>
<polygon fill="#000000" stroke="#000000" points="1006.3958,-514.9737 998.413,-508.0077 1000.3094,-518.4315 1006.3958,-514.9737"/>
<text text-anchor="middle" x="1097.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- vaccination -->
<g id="node4" class="node">
<title>vaccination</title>
<path fill="none" stroke="#000000" d="M1307,-772C1307,-772 1583,-772 1583,-772 1589,-772 1595,-778 1595,-784 1595,-784 1595,-806 1595,-806 1595,-812 1589,-818 1583,-818 1583,-818 1307,-818 1307,-818 1301,-818 1295,-812 1295,-806 1295,-806 1295,-784 1295,-784 1295,-778 1301,-772 1307,-772"/>
<text text-anchor="middle" x="1344.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">vaccination</text>
<polyline fill="none" stroke="#000000" points="1394,-772 1394,-818 "/>
<text text-anchor="middle" x="1404.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1415,-772 1415,-818 "/>
<text text-anchor="middle" x="1494.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_vaccination</text>
<polyline fill="none" stroke="#000000" points="1415,-795 1574,-795 "/>
<text text-anchor="middle" x="1494.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">infectious_agent</text>
<polyline fill="none" stroke="#000000" points="1574,-772 1574,-818 "/>
<text text-anchor="middle" x="1584.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- vaccination&#45;&gt;participant -->
<g id="edge5" class="edge">
<title>vaccination&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1428.744,-771.715C1402.509,-735.5616 1347.6083,-665.5634 1287,-622 1215.3442,-570.4961 1120.4053,-532.8548 1056.9155,-511.2404"/>
<polygon fill="#000000" stroke="#000000" points="1057.9879,-507.9084 1047.3939,-508.0386 1055.7568,-514.5434 1057.9879,-507.9084"/>
<text text-anchor="middle" x="1307.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- aliquot -->
<g id="node5" class="node">
<title>aliquot</title>
<path fill="none" stroke="#000000" d="M945.5,-1042.5C945.5,-1042.5 1146.5,-1042.5 1146.5,-1042.5 1152.5,-1042.5 1158.5,-1048.5 1158.5,-1054.5 1158.5,-1054.5 1158.5,-1099.5 1158.5,-1099.5 1158.5,-1105.5 1152.5,-1111.5 1146.5,-1111.5 1146.5,-1111.5 945.5,-1111.5 945.5,-1111.5 939.5,-1111.5 933.5,-1105.5 933.5,-1099.5 933.5,-1099.5 933.5,-1054.5 933.5,-1054.5 933.5,-1048.5 939.5,-1042.5 945.5,-1042.5"/>
<text text-anchor="middle" x="966.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot</text>
<polyline fill="none" stroke="#000000" points="999.5,-1042.5 999.5,-1111.5 "/>
<text text-anchor="middle" x="1010" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1020.5,-1042.5 1020.5,-1111.5 "/>
<text text-anchor="middle" x="1079" y="-1096.3" font-family="Times,serif" font-size="14.00" fill="#000000">aliquot_type</text>
<polyline fill="none" stroke="#000000" points="1020.5,-1088.5 1137.5,-1088.5 "/>
<text text-anchor="middle" x="1079" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1020.5,-1065.5 1137.5,-1065.5 "/>
<text text-anchor="middle" x="1079" y="-1050.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="1137.5,-1042.5 1137.5,-1111.5 "/>
<text text-anchor="middle" x="1148" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_run -->
<g id="node14" class="node">
<title>assay_run</title>
<path fill="none" stroke="#000000" d="M2033,-737.5C2033,-737.5 2271,-737.5 2271,-737.5 2277,-737.5 2283,-743.5 2283,-749.5 2283,-749.5 2283,-840.5 2283,-840.5 2283,-846.5 2277,-852.5 2271,-852.5 2271,-852.5 2033,-852.5 2033,-852.5 2027,-852.5 2021,-846.5 2021,-840.5 2021,-840.5 2021,-749.5 2021,-749.5 2021,-743.5 2027,-737.5 2033,-737.5"/>
<text text-anchor="middle" x="2065.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_run</text>
<polyline fill="none" stroke="#000000" points="2110,-737.5 2110,-852.5 "/>
<text text-anchor="middle" x="2120.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2131,-737.5 2131,-852.5 "/>
<text text-anchor="middle" x="2196.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_performed</text>
<polyline fill="none" stroke="#000000" points="2131,-829.5 2262,-829.5 "/>
<text text-anchor="middle" x="2196.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2131,-806.5 2262,-806.5 "/>
<text text-anchor="middle" x="2196.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">is_clia</text>
<polyline fill="none" stroke="#000000" points="2131,-783.5 2262,-783.5 "/>
<text text-anchor="middle" x="2196.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">operator</text>
<polyline fill="none" stroke="#000000" points="2131,-760.5 2262,-760.5 "/>
<text text-anchor="middle" x="2196.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">variances</text>
<polyline fill="none" stroke="#000000" points="2262,-737.5 2262,-852.5 "/>
<text text-anchor="middle" x="2272.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- aliquot&#45;&gt;assay_run -->
<g id="edge16" class="edge">
<title>aliquot&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M1158.7871,-1060.0863C1296.5831,-1039.9336 1536.9496,-1006.4298 1744,-986 1803.4013,-980.1388 1959.0212,-995.4974 2012,-968 2057.1132,-944.5851 2092.8305,-899.5518 2116.8957,-861.3012"/>
<polygon fill="#000000" stroke="#000000" points="2119.8968,-863.1026 2122.155,-852.7512 2113.9345,-859.435 2119.8968,-863.1026"/>
<text text-anchor="middle" x="1791" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- biospecimen -->
<g id="node17" class="node">
<title>biospecimen</title>
<path fill="none" stroke="#000000" d="M322,-622.5C322,-622.5 688,-622.5 688,-622.5 694,-622.5 700,-628.5 700,-634.5 700,-634.5 700,-955.5 700,-955.5 700,-961.5 694,-967.5 688,-967.5 688,-967.5 322,-967.5 322,-967.5 316,-967.5 310,-961.5 310,-955.5 310,-955.5 310,-634.5 310,-634.5 310,-628.5 316,-622.5 322,-622.5"/>
<text text-anchor="middle" x="363.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen</text>
<polyline fill="none" stroke="#000000" points="417,-622.5 417,-967.5 "/>
<text text-anchor="middle" x="427.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="438,-622.5 438,-967.5 "/>
<text text-anchor="middle" x="558.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_group</text>
<polyline fill="none" stroke="#000000" points="438,-944.5 679,-944.5 "/>
<text text-anchor="middle" x="558.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">biospecimen_type</text>
<polyline fill="none" stroke="#000000" points="438,-921.5 679,-921.5 "/>
<text text-anchor="middle" x="558.5" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_last_aliquotted</text>
<polyline fill="none" stroke="#000000" points="438,-898.5 679,-898.5 "/>
<text text-anchor="middle" x="558.5" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">datetime_of_collection</text>
<polyline fill="none" stroke="#000000" points="438,-875.5 679,-875.5 "/>
<text text-anchor="middle" x="558.5" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">datetime_of_processing</text>
<polyline fill="none" stroke="#000000" points="438,-852.5 679,-852.5 "/>
<text text-anchor="middle" x="558.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_onset</text>
<polyline fill="none" stroke="#000000" points="438,-829.5 679,-829.5 "/>
<text text-anchor="middle" x="558.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">days_post_symptom_resolution</text>
<polyline fill="none" stroke="#000000" points="438,-806.5 679,-806.5 "/>
<text text-anchor="middle" x="558.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">freeze_thaw_cycle</text>
<polyline fill="none" stroke="#000000" points="438,-783.5 679,-783.5 "/>
<text text-anchor="middle" x="558.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="438,-760.5 679,-760.5 "/>
<text text-anchor="middle" x="558.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_concentration_pbmc</text>
<polyline fill="none" stroke="#000000" points="438,-737.5 679,-737.5 "/>
<text text-anchor="middle" x="558.5" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">initial_volume</text>
<polyline fill="none" stroke="#000000" points="438,-714.5 679,-714.5 "/>
<text text-anchor="middle" x="558.5" y="-699.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_live_pbmc</text>
<polyline fill="none" stroke="#000000" points="438,-691.5 679,-691.5 "/>
<text text-anchor="middle" x="558.5" y="-676.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_total_pbmc</text>
<polyline fill="none" stroke="#000000" points="438,-668.5 679,-668.5 "/>
<text text-anchor="middle" x="558.5" y="-653.3" font-family="Times,serif" font-size="14.00" fill="#000000">percent_viable_pbmc</text>
<polyline fill="none" stroke="#000000" points="438,-645.5 679,-645.5 "/>
<text text-anchor="middle" x="558.5" y="-630.3" font-family="Times,serif" font-size="14.00" fill="#000000">rt_serum_clotting</text>
<polyline fill="none" stroke="#000000" points="679,-622.5 679,-967.5 "/>
<text text-anchor="middle" x="689.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- aliquot&#45;&gt;biospecimen -->
<g id="edge21" class="edge">
<title>aliquot&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M933.3724,-1052.3454C865.6432,-1034.7082 779.2433,-1007.1151 709,-968 708.9081,-967.9488 708.8162,-967.8976 708.7243,-967.8463"/>
<polygon fill="#000000" stroke="#000000" points="710.6032,-964.8892 700.1869,-962.9522 707.1218,-970.9621 710.6032,-964.8892"/>
<text text-anchor="middle" x="825" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
<!-- project&#45;&gt;center -->
<g id="edge13" class="edge">
<title>project&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M907,-167.1416C907,-154.6834 907,-140.1822 907,-125.8971"/>
<polygon fill="#000000" stroke="#000000" points="910.5001,-125.5658 907,-115.5658 903.5001,-125.5658 910.5001,-125.5658"/>
<text text-anchor="middle" x="941" y="-137.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_center</text>
</g>
<!-- assay -->
<g id="node8" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M2179.5,-409.5C2179.5,-409.5 2368.5,-409.5 2368.5,-409.5 2374.5,-409.5 2380.5,-415.5 2380.5,-421.5 2380.5,-421.5 2380.5,-558.5 2380.5,-558.5 2380.5,-564.5 2374.5,-570.5 2368.5,-570.5 2368.5,-570.5 2179.5,-570.5 2179.5,-570.5 2173.5,-570.5 2167.5,-564.5 2167.5,-558.5 2167.5,-558.5 2167.5,-421.5 2167.5,-421.5 2167.5,-415.5 2173.5,-409.5 2179.5,-409.5"/>
<text text-anchor="middle" x="2195.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
<polyline fill="none" stroke="#000000" points="2223.5,-409.5 2223.5,-570.5 "/>
<text text-anchor="middle" x="2234" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2244.5,-409.5 2244.5,-570.5 "/>
<text text-anchor="middle" x="2302" y="-555.3" font-family="Times,serif" font-size="14.00" fill="#000000">antibody</text>
<polyline fill="none" stroke="#000000" points="2244.5,-547.5 2359.5,-547.5 "/>
<text text-anchor="middle" x="2302" y="-532.3" font-family="Times,serif" font-size="14.00" fill="#000000">antigen</text>
<polyline fill="none" stroke="#000000" points="2244.5,-524.5 2359.5,-524.5 "/>
<text text-anchor="middle" x="2302" y="-509.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_target</text>
<polyline fill="none" stroke="#000000" points="2244.5,-501.5 2359.5,-501.5 "/>
<text text-anchor="middle" x="2302" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_type</text>
<polyline fill="none" stroke="#000000" points="2244.5,-478.5 2359.5,-478.5 "/>
<text text-anchor="middle" x="2302" y="-463.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2244.5,-455.5 2359.5,-455.5 "/>
<text text-anchor="middle" x="2302" y="-440.3" font-family="Times,serif" font-size="14.00" fill="#000000">manufacturer</text>
<polyline fill="none" stroke="#000000" points="2244.5,-432.5 2359.5,-432.5 "/>
<text text-anchor="middle" x="2302" y="-417.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="2359.5,-409.5 2359.5,-570.5 "/>
<text text-anchor="middle" x="2370" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop -->
<g id="node9" class="node">
<title>sop</title>
<path fill="none" stroke="#000000" d="M2067,-1019.5C2067,-1019.5 2237,-1019.5 2237,-1019.5 2243,-1019.5 2249,-1025.5 2249,-1031.5 2249,-1031.5 2249,-1122.5 2249,-1122.5 2249,-1128.5 2243,-1134.5 2237,-1134.5 2237,-1134.5 2067,-1134.5 2067,-1134.5 2061,-1134.5 2055,-1128.5 2055,-1122.5 2055,-1122.5 2055,-1031.5 2055,-1031.5 2055,-1025.5 2061,-1019.5 2067,-1019.5"/>
<text text-anchor="middle" x="2075.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">sop</text>
<polyline fill="none" stroke="#000000" points="2096,-1019.5 2096,-1134.5 "/>
<text text-anchor="middle" x="2106.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2117,-1019.5 2117,-1134.5 "/>
<text text-anchor="middle" x="2172.5" y="-1119.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2117,-1111.5 2228,-1111.5 "/>
<text text-anchor="middle" x="2172.5" y="-1096.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="2117,-1088.5 2228,-1088.5 "/>
<text text-anchor="middle" x="2172.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">process_type</text>
<polyline fill="none" stroke="#000000" points="2117,-1065.5 2228,-1065.5 "/>
<text text-anchor="middle" x="2172.5" y="-1050.3" font-family="Times,serif" font-size="14.00" fill="#000000">url</text>
<polyline fill="none" stroke="#000000" points="2117,-1042.5 2228,-1042.5 "/>
<text text-anchor="middle" x="2172.5" y="-1027.3" font-family="Times,serif" font-size="14.00" fill="#000000">version</text>
<polyline fill="none" stroke="#000000" points="2228,-1019.5 2228,-1134.5 "/>
<text text-anchor="middle" x="2238.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sop&#45;&gt;assay -->
<g id="edge2" class="edge">
<title>sop&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2249.1013,-1020.4557C2266.4039,-1005.7001 2282.0593,-988.1701 2292,-968 2352.843,-844.5475 2327.364,-680.6034 2301.8307,-580.3354"/>
<polygon fill="#000000" stroke="#000000" points="2305.1863,-579.3321 2299.2829,-570.5344 2298.4114,-581.0933 2305.1863,-579.3321"/>
<text text-anchor="middle" x="2359.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- sop&#45;&gt;assay_run -->
<g id="edge15" class="edge">
<title>sop&#45;&gt;assay_run</title>
<path fill="none" stroke="#000000" d="M2152,-1019.2526C2152,-973.9155 2152,-910.6872 2152,-862.9217"/>
<polygon fill="#000000" stroke="#000000" points="2155.5001,-862.6701 2152,-852.6702 2148.5001,-862.6702 2155.5001,-862.6701"/>
<text text-anchor="middle" x="2199" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay_run</text>
</g>
<!-- sop&#45;&gt;biospecimen -->
<g id="edge20" class="edge">
<title>sop&#45;&gt;biospecimen</title>
<path fill="none" stroke="#000000" d="M2054.8529,-1041.5772C1993.5642,-1021.0595 1912.2294,-997.1436 1838,-986 1778.0247,-976.9963 833.6276,-989.2134 710.002,-966.9286"/>
<polygon fill="#000000" stroke="#000000" points="710.7865,-963.5172 700.2381,-964.5082 709.1022,-970.3115 710.7865,-963.5172"/>
<text text-anchor="middle" x="1964" y="-989.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_biospecimen</text>
</g>
<!-- cov2_diagnosis -->
<g id="node10" class="node">
<title>cov2_diagnosis</title>
<path fill="none" stroke="#000000" d="M1625.5,-749C1625.5,-749 1990.5,-749 1990.5,-749 1996.5,-749 2002.5,-755 2002.5,-761 2002.5,-761 2002.5,-829 2002.5,-829 2002.5,-835 1996.5,-841 1990.5,-841 1990.5,-841 1625.5,-841 1625.5,-841 1619.5,-841 1613.5,-835 1613.5,-829 1613.5,-829 1613.5,-761 1613.5,-761 1613.5,-755 1619.5,-749 1625.5,-749"/>
<text text-anchor="middle" x="1676" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">cov2_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1738.5,-749 1738.5,-841 "/>
<text text-anchor="middle" x="1749" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1759.5,-749 1759.5,-841 "/>
<text text-anchor="middle" x="1870.5" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1759.5,-818 1981.5,-818 "/>
<text text-anchor="middle" x="1870.5" y="-802.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_symptom_onset</text>
<polyline fill="none" stroke="#000000" points="1759.5,-795 1981.5,-795 "/>
<text text-anchor="middle" x="1870.5" y="-779.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_symptom_resolution</text>
<polyline fill="none" stroke="#000000" points="1759.5,-772 1981.5,-772 "/>
<text text-anchor="middle" x="1870.5" y="-756.8" font-family="Times,serif" font-size="14.00" fill="#000000">year_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1981.5,-749 1981.5,-841 "/>
<text text-anchor="middle" x="1992" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay_result -->
<g id="node11" class="node">
<title>assay_result</title>
<path fill="none" stroke="#000000" d="M1782,-444C1782,-444 2016,-444 2016,-444 2022,-444 2028,-450 2028,-456 2028,-456 2028,-524 2028,-524 2028,-530 2022,-536 2016,-536 2016,-536 1782,-536 1782,-536 1776,-536 1770,-530 1770,-524 1770,-524 1770,-456 1770,-456 1770,-450 1776,-444 1782,-444"/>
<text text-anchor="middle" x="1823" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_result</text>
<polyline fill="none" stroke="#000000" points="1876,-444 1876,-536 "/>
<text text-anchor="middle" x="1886.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1897,-444 1897,-536 "/>
<text text-anchor="middle" x="1952" y="-520.8" font-family="Times,serif" font-size="14.00" fill="#000000">cutoff</text>
<polyline fill="none" stroke="#000000" points="1897,-513 2007,-513 "/>
<text text-anchor="middle" x="1952" y="-497.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1897,-490 2007,-490 "/>
<text text-anchor="middle" x="1952" y="-474.8" font-family="Times,serif" font-size="14.00" fill="#000000">output_type</text>
<polyline fill="none" stroke="#000000" points="1897,-467 2007,-467 "/>
<text text-anchor="middle" x="1952" y="-451.8" font-family="Times,serif" font-size="14.00" fill="#000000">output_value</text>
<polyline fill="none" stroke="#000000" points="2007,-444 2007,-536 "/>
<text text-anchor="middle" x="2017.5" y="-486.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cov2_diagnosis&#45;&gt;assay_result -->
<g id="edge19" class="edge">
<title>cov2_diagnosis&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M1821.8209,-748.6771C1838.0365,-694.3283 1864.9088,-604.2616 1882.2824,-546.0315"/>
<polygon fill="#000000" stroke="#000000" points="1885.6931,-546.8415 1885.1984,-536.2582 1878.9853,-544.8401 1885.6931,-546.8415"/>
<text text-anchor="middle" x="1946" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_supporting_result</text>
</g>
<!-- cov2_diagnosis&#45;&gt;participant -->
<g id="edge8" class="edge">
<title>cov2_diagnosis&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M1766.463,-748.7518C1728.167,-709.0336 1667.751,-653.3653 1604,-622 1432.3017,-537.5251 1207.5748,-506.8615 1082.4961,-495.9129"/>
<polygon fill="#000000" stroke="#000000" points="1082.4478,-492.3962 1072.187,-495.0355 1081.8541,-499.371 1082.4478,-492.3962"/>
<text text-anchor="middle" x="1607.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- cohort -->
<g id="node12" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1086.5,-288.5C1086.5,-288.5 1265.5,-288.5 1265.5,-288.5 1271.5,-288.5 1277.5,-294.5 1277.5,-300.5 1277.5,-300.5 1277.5,-345.5 1277.5,-345.5 1277.5,-351.5 1271.5,-357.5 1265.5,-357.5 1265.5,-357.5 1086.5,-357.5 1086.5,-357.5 1080.5,-357.5 1074.5,-351.5 1074.5,-345.5 1074.5,-345.5 1074.5,-300.5 1074.5,-300.5 1074.5,-294.5 1080.5,-288.5 1086.5,-288.5"/>
<text text-anchor="middle" x="1106" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1137.5,-288.5 1137.5,-357.5 "/>
<text text-anchor="middle" x="1148" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1158.5,-288.5 1158.5,-357.5 "/>
<text text-anchor="middle" x="1207.5" y="-342.3" font-family="Times,serif" font-size="14.00" fill="#000000">description</text>
<polyline fill="none" stroke="#000000" points="1158.5,-334.5 1256.5,-334.5 "/>
<text text-anchor="middle" x="1207.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="1158.5,-311.5 1256.5,-311.5 "/>
<text text-anchor="middle" x="1207.5" y="-296.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1256.5,-288.5 1256.5,-357.5 "/>
<text text-anchor="middle" x="1267" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- participant&#45;&gt;study -->
<g id="edge11" class="edge">
<title>participant&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M948.2802,-471.8933C913.8951,-454.7489 864.414,-426.3917 830,-391 822.982,-383.7826 816.6965,-375.1042 811.3016,-366.3986"/>
<polygon fill="#000000" stroke="#000000" points="814.2947,-364.5838 806.2092,-357.7372 808.2604,-368.1316 814.2947,-364.5838"/>
<text text-anchor="middle" x="873.5" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- participant&#45;&gt;center -->
<g id="edge9" class="edge">
<title>participant&#45;&gt;center</title>
<path fill="none" stroke="#000000" d="M996.6815,-471.7848C1019.6399,-420.8466 1076.8794,-273.6839 1027,-167 1019.4566,-150.866 1008.3101,-136.048 995.8027,-122.8813"/>
<polygon fill="#000000" stroke="#000000" points="998.2521,-120.3806 988.7283,-115.7385 993.2785,-125.3065 998.2521,-120.3806"/>
<text text-anchor="middle" x="1086.5" y="-258.8" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_at</text>
</g>
<!-- participant&#45;&gt;project -->
<g id="edge12" class="edge">
<title>participant&#45;&gt;project</title>
<path fill="none" stroke="#000000" d="M981.5748,-471.7705C972.7543,-446.428 956.6634,-399.0351 945,-358 934.3752,-320.6191 924.053,-277.6876 916.8548,-246.3369"/>
<polygon fill="#000000" stroke="#000000" points="920.2671,-245.5581 914.631,-236.5867 913.4423,-247.1147 920.2671,-245.5581"/>
<text text-anchor="middle" x="988.5" y="-319.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrolled_for</text>
</g>
<!-- participant&#45;&gt;cohort -->
<g id="edge17" class="edge">
<title>participant&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1008.4772,-471.8102C1037.2949,-446.2114 1090.6231,-398.8401 1129.3891,-364.4043"/>
<polygon fill="#000000" stroke="#000000" points="1131.7847,-366.9579 1136.9366,-357.6999 1127.1359,-361.7244 1131.7847,-366.9579"/>
<text text-anchor="middle" x="1149" y="-379.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_cohort</text>
</g>
<!-- assay_run&#45;&gt;assay -->
<g id="edge1" class="edge">
<title>assay_run&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2175.0907,-737.2733C2192.8446,-692.8885 2217.6966,-630.7585 2238.0474,-579.8814"/>
<polygon fill="#000000" stroke="#000000" points="2241.328,-581.104 2241.7923,-570.5193 2234.8286,-578.5042 2241.328,-581.104"/>
<text text-anchor="middle" x="2261.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- assay_run&#45;&gt;assay_result -->
<g id="edge18" class="edge">
<title>assay_run&#45;&gt;assay_result</title>
<path fill="none" stroke="#000000" d="M2125.5028,-737.2958C2103.7278,-693.6494 2070.016,-633.79 2030,-589 2014.9297,-572.1318 1996.6163,-556.2093 1978.5181,-542.2668"/>
<polygon fill="#000000" stroke="#000000" points="1980.3186,-539.2404 1970.2302,-536.0038 1976.0983,-544.8252 1980.3186,-539.2404"/>
<text text-anchor="middle" x="2103" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">has_assay_result</text>
</g>
<!-- workflow -->
<g id="node15" class="node">
<title>workflow</title>
<path fill="none" stroke="#000000" d="M2279.5,-1054C2279.5,-1054 2502.5,-1054 2502.5,-1054 2508.5,-1054 2514.5,-1060 2514.5,-1066 2514.5,-1066 2514.5,-1088 2514.5,-1088 2514.5,-1094 2508.5,-1100 2502.5,-1100 2502.5,-1100 2279.5,-1100 2279.5,-1100 2273.5,-1100 2267.5,-1094 2267.5,-1088 2267.5,-1088 2267.5,-1066 2267.5,-1066 2267.5,-1060 2273.5,-1054 2279.5,-1054"/>
<text text-anchor="middle" x="2309" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">workflow</text>
<polyline fill="none" stroke="#000000" points="2350.5,-1054 2350.5,-1100 "/>
<text text-anchor="middle" x="2361" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2371.5,-1054 2371.5,-1100 "/>
<text text-anchor="middle" x="2432.5" y="-1084.8" font-family="Times,serif" font-size="14.00" fill="#000000">id</text>
<polyline fill="none" stroke="#000000" points="2371.5,-1077 2493.5,-1077 "/>
<text text-anchor="middle" x="2432.5" y="-1061.8" font-family="Times,serif" font-size="14.00" fill="#000000">workflow_type</text>
<polyline fill="none" stroke="#000000" points="2493.5,-1054 2493.5,-1100 "/>
<text text-anchor="middle" x="2504" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- clinical_course -->
<g id="node16" class="node">
<title>clinical_course</title>
<path fill="none" stroke="#000000" d="M2545,-1054C2545,-1054 2943,-1054 2943,-1054 2949,-1054 2955,-1060 2955,-1066 2955,-1066 2955,-1088 2955,-1088 2955,-1094 2949,-1100 2943,-1100 2943,-1100 2545,-1100 2545,-1100 2539,-1100 2533,-1094 2533,-1088 2533,-1088 2533,-1066 2533,-1066 2533,-1060 2539,-1054 2545,-1054"/>
<text text-anchor="middle" x="2595" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_course</text>
<polyline fill="none" stroke="#000000" points="2657,-1054 2657,-1100 "/>
<text text-anchor="middle" x="2667.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2678,-1054 2678,-1100 "/>
<text text-anchor="middle" x="2806" y="-1084.8" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_findings_and_procedures</text>
<polyline fill="none" stroke="#000000" points="2678,-1077 2934,-1077 "/>
<text text-anchor="middle" x="2806" y="-1061.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_assessment</text>
<polyline fill="none" stroke="#000000" points="2934,-1054 2934,-1100 "/>
<text text-anchor="middle" x="2944.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- biospecimen&#45;&gt;participant -->
<g id="edge3" class="edge">
<title>biospecimen&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M700.2103,-627.7713C703.142,-625.8122 706.0728,-623.8871 709,-622 781.4189,-575.3123 872.9371,-535.1971 930.9898,-511.8176"/>
<polygon fill="#000000" stroke="#000000" points="932.3783,-515.0319 940.365,-508.0703 929.7802,-508.5319 932.3783,-515.0319"/>
<text text-anchor="middle" x="809.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- demographic -->
<g id="node18" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M730,-714.5C730,-714.5 958,-714.5 958,-714.5 964,-714.5 970,-720.5 970,-726.5 970,-726.5 970,-863.5 970,-863.5 970,-869.5 964,-875.5 958,-875.5 958,-875.5 730,-875.5 730,-875.5 724,-875.5 718,-869.5 718,-863.5 718,-863.5 718,-726.5 718,-726.5 718,-720.5 724,-714.5 730,-714.5"/>
<text text-anchor="middle" x="773" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="828,-714.5 828,-875.5 "/>
<text text-anchor="middle" x="838.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="849,-714.5 849,-875.5 "/>
<text text-anchor="middle" x="899" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">abo_type</text>
<polyline fill="none" stroke="#000000" points="849,-852.5 949,-852.5 "/>
<text text-anchor="middle" x="899" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">age</text>
<polyline fill="none" stroke="#000000" points="849,-829.5 949,-829.5 "/>
<text text-anchor="middle" x="899" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="849,-806.5 949,-806.5 "/>
<text text-anchor="middle" x="899" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">gender</text>
<polyline fill="none" stroke="#000000" points="849,-783.5 949,-783.5 "/>
<text text-anchor="middle" x="899" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="849,-760.5 949,-760.5 "/>
<text text-anchor="middle" x="899" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">rh_type</text>
<polyline fill="none" stroke="#000000" points="849,-737.5 949,-737.5 "/>
<text text-anchor="middle" x="899" y="-722.3" font-family="Times,serif" font-size="14.00" fill="#000000">vital_status</text>
<polyline fill="none" stroke="#000000" points="949,-714.5 949,-875.5 "/>
<text text-anchor="middle" x="959.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;participant -->
<g id="edge6" class="edge">
<title>demographic&#45;&gt;participant</title>
<path fill="none" stroke="#000000" d="M882.0227,-714.4659C912.7772,-649.3261 954.2633,-561.4563 975.027,-517.4775"/>
<polygon fill="#000000" stroke="#000000" points="978.2645,-518.8182 979.3689,-508.2811 971.9345,-515.8296 978.2645,-518.8182"/>
<text text-anchor="middle" x="987.5" y="-592.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_participant</text>
</g>
<!-- assay_metrics -->
<g id="node19" class="node">
<title>assay_metrics</title>
<path fill="none" stroke="#000000" d="M2985,-1042.5C2985,-1042.5 3249,-1042.5 3249,-1042.5 3255,-1042.5 3261,-1048.5 3261,-1054.5 3261,-1054.5 3261,-1099.5 3261,-1099.5 3261,-1105.5 3255,-1111.5 3249,-1111.5 3249,-1111.5 2985,-1111.5 2985,-1111.5 2979,-1111.5 2973,-1105.5 2973,-1099.5 2973,-1099.5 2973,-1054.5 2973,-1054.5 2973,-1048.5 2979,-1042.5 2985,-1042.5"/>
<text text-anchor="middle" x="3032.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">assay_metrics</text>
<polyline fill="none" stroke="#000000" points="3092,-1042.5 3092,-1111.5 "/>
<text text-anchor="middle" x="3102.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3113,-1042.5 3113,-1111.5 "/>
<text text-anchor="middle" x="3176.5" y="-1096.3" font-family="Times,serif" font-size="14.00" fill="#000000">metrics_source</text>
<polyline fill="none" stroke="#000000" points="3113,-1088.5 3240,-1088.5 "/>
<text text-anchor="middle" x="3176.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000">sensitivity</text>
<polyline fill="none" stroke="#000000" points="3113,-1065.5 3240,-1065.5 "/>
<text text-anchor="middle" x="3176.5" y="-1050.3" font-family="Times,serif" font-size="14.00" fill="#000000">specificity</text>
<polyline fill="none" stroke="#000000" points="3240,-1042.5 3240,-1111.5 "/>
<text text-anchor="middle" x="3250.5" y="-1073.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
</g>
</svg>
</div>
