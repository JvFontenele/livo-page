<script setup>
import { ref } from "vue";
const foguete = ref(true);
function desligarLoading() {
  foguete.value = false;
}
setInterval(desligarLoading, 3000);
const fundo = ref(true);
function limparLoading() {
  fundo.value = false;
}
setInterval(limparLoading, 5500);


</script>
<template>
  <div v-if="fundo" :class="foguete ? 'fundo scene' : ' fundo scene limpar'">
    <svg
      id="ceu"
      class=""
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      width="591.86mm"
      height="441.073mm"
      viewBox="0 0 2097.1428 1562.8572"
    >
      <g transform="translate(662.857 224.78)">
        <ellipse
          id="a"
          cx="-223.571"
          cy="440.934"
          rx="2.143"
          ry="2.857"
          fill="#fff"
          fill-opacity=".903"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(325.17 -286.62)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(522.893 130.324)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(529.1 123.66)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(176.665 391.77)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(276.026 428.313)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-139.458 -203.887)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-61.896 -175.592)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-269.32 -200.014)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-21.573 -259.105)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-32.688 -203.965)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(337.885 -339.35)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(376.753 -382.86)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(377.68 -461.26)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(590.58 -521.348)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(961.978 -432.823)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1074.645 -348.408)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(965.5 -357.084)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(909.277 -405.422)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1159.568 -52.93)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1332.777 -55.188)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1099.923 607.58)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1102.906 524.723)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1170.34 586.95)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1061.796 577.478)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1053.26 584.495)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(981.2 608.736)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1052.273 505.1)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1130.426 601.618)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(996.413 550.48)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(123.392 759.928)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(53.736 685.683)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-11.538 833.27)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(14.487 809.297)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-60.687 641.29)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-16.47 712.696)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-111.336 509.3)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-226.166 651.667)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-296.79 -482.29)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-284.178 -522.598)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-286.14 -361.03)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-315.723 -539.19)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-256.885 -473.05)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-281.654 -641.284)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(142.58 -607.46)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(2.556 -506.104)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(139.227 -439.76)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(161.003 -546.336)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(320.215 -636.64)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(248.22 -584.967)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(315.363 -617.41)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(426.49 -469.39)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(326.138 -566.187)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(548.258 -546.43)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(468.51 -533.79)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(545.936 -483.38)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(714.176 -548.748)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1120.943 -491.71)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1076.835 -361.477)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1105.036 -518.525)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1052.577 -429.993)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1088.297 -576.584)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(966.81 -412.152)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1107.748 -522.608)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1242.255 -472.512)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1056.614 -514.95)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1053.1 -531.696)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1020.946 -467.78)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1097.897 -435.764)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1412.376 -470.422)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1301.614 -632.734)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1392.75 -508.152)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1568.647 -249.108)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1507.938 -106.978)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1602.067 -168.098)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1401.825 -141.68)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1591.803 67.433)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1566.47 -69.366)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1511.725 -129.465)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1603.073 -1.417)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1401.768 37.65)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1560.198 17.946)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1427.56 -77.608)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1530.096 -32.916)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1540.543 141.864)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1535.824 67.62)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1318.133 433.966)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1450.634 500.332)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1456.163 395.217)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1380.927 558.12)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1311.995 471.716)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1526.874 484.085)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1529.872 597.075)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1564.556 539.89)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1548.292 742.352)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1124.955 801.813)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1068.963 792.532)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(718.417 830.956)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(719.028 840.427)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(712.255 762.492)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(602.057 724.775)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(589.436 853.834)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(289.133 630.968)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(281.198 593.568)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(379.006 620.84)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(282.797 166.698)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(205.897 307.814)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(265.21 211.918)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(114.72 178.476)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-189.4 160.605)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-86.22 37.16)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-144.166 143.668)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-89.997 97.11)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-106.213 131.298)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-162.515 141.686)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-82.88 158.31)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-237.457 143.606)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-160.454 224.11)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-242.174 428.327)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-334.082 502.24)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-284.75 391.59)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-406.647 651.012)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-305.06 730.338)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-414.743 845.43)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(317.35 307.862)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(438.84 342.48)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(356.192 175.873)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(508.497 419.97)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(593.63 308.846)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(401.11 174.66)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(602.195 309.908)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(803.656 246.04)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(589.878 314.39)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(737.753 357.915)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1005.437 552.882)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1013.64 688.73)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(976.023 270.828)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1006.457 304.973)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1150.742 162.676)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1092.694 151.233)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1014.497 261.455)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(971.296 189.29)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(993.9 122.812)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(968.61 .4)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(435.5 -55.862)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(618.28 -71.372)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(442.085 -123.33)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(563.68 -146.422)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(302.833 -44.896)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-44.295 -89.76)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-279.393 -33.253)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(3.013 331.893)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-5.92 220.253)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-362.933 167.368)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-370.785 152.53)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-402.572 216.72)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-207.988 161.782)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(420.474 588.35)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(529.76 615.51)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(803.103 617.673)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(951.156 641.72)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(876.14 590.948)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(997.556 571.008)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1016.874 774.64)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1383.768 734.134)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1156.73 283.417)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1147.993 204.697)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(877.142 224.113)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(873.965 -154.32)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(958.42 -217.94)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(877.06 -246.197)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(925.984 -167.27)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(912.004 -196.103)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(697.347 -630.083)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1347.187 -517.303)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1464.975 -573.796)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1430.163 -592.785)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1456.376 -595.193)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1511.752 -565.6)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1558.05 -537.378)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1485.287 -623.16)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1510.644 -289.82)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1530.04 -348.356)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1327.144 49.584)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1474.744 23.79)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1420.108 118.524)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(622.365 207.372)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-209.373 689.22)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(513.663 758.3)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1569.79 856.31)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(-338.673 -208.832)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(823.85 -290.13)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(710.975 18.242)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(639.494 -274.74)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1261.567 -171.09)"
        />
        <use
          xlink:href="#a"
          width="100%"
          height="100%"
          transform="translate(1343.705 -207.584)"
        />
      </g>
    </svg>
    <section class="rocket">
      <img cal src="../assets/loading/foquete2.png" alt="Foguete." />
    </section>
  </div>
</template>

<style scoped>
.limpar  {
  display: none;
  animation-name: sumir;
  animation-duration: 4s;
}
.fundo {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #531b69;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  z-index: 9999;
}


#ceu {
  height: 200%;
  animation: movement 0.7s linear infinite;
  z-index: -1;
  position: absolute;
  top: -100vw;
}

@keyframes movement {
  from {
    transform: translate(0px, 0%);
  }
  to {
    transform: translate(0px, 50vw);
  }
}

@media screen and (min-width: 800px) {
  #ceu {
    height: 200%;
    animation: movement 0.7s linear infinite;
    z-index: -1;
    position: absolute;
    top: -70vw;
  }

  @keyframes movement {
    from {
      transform: translate(0px, 0%);
    }
    to {
      transform: translate(0px, 50vw);
    }
  }
}

/* -- Scene -- */

.rocket {
  position: absolute;
  z-index: 1000;

  animation: animate 0.2s ease infinite;
}

.rocket img {
  width: 150px;
  height: 150px;
  position: relative;
  left: 30px;
  top: -80px;
  z-index: 10px;
}

.rocket::before {
  content: "";
  position: absolute;
  bottom: -98px;
  left: 70%;
  transform: translateX(-50%);
  width: 15px;
  height: 200px;
  background: linear-gradient(#00d0ff, transparent);
}
.rocket::after {
  content: "";
  position: absolute;
  bottom: -98px;
  left: 92%;
  transform: translateX(-50%);
  width: 10px;
  height: 200px;
  background: linear-gradient(#00d0ff, transparent);
  filter: blur(20px);
}

/* -- Scene Rocket -- */

/* -- Waves -- */

#wave-1 {
  position: absolute;
  left: 0;
  top: -300px;
  width: 100%;
  transform: rotate(180deg);
}

#wave-2 {
  position: absolute;
  left: 0;
  bottom: -300px;
  width: 100%;
}

#wave-1 svg path,
#wave-2 svg path {
  animation: animateWave 7s linear infinite;
}

#wave-1 svg path:nth-child(2),
#wave-2 svg path:nth-child(2) {
  animation-delay: 1s;
}
#wave-1 svg path:nth-child(3),
#wave-2 svg path:nth-child(3) {
  animation-delay: 3s;
}
#wave-1 svg path:nth-child(4),
#wave-2 svg path:nth-child(4) {
  animation-play-state: paused;
}

/* -- Waves -- */

/* -- Keyframes -- */

@keyframes animateStars {
  0% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(200vh);
  }
}

@keyframes animateStars_2 {
  0% {
    opacity: 0;
    transform: translateY(0);
  }
  10%,
  90% {
    opacity: 1;
  }

  100% {
    opacity: 0;
    transform: translateY(1000px);
  }
}

@keyframes animate {
  0%,
  100% {
    transform: translateY(-2);
  }

  50% {
    transform: translateY(2px);
  }
}

@keyframes animateBg {
  0% {
    background-position: 0% 0%;
  }
  100% {
    background-position: 0% 100%;
  }
}

@keyframes animateWave {
  0% {
    d: path(
      "M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 300 L0 300"
    );
  }

  25% {
    d: path(
      "M0,100 C220,100,440,292,660,292 C880,292,1100,100,1320,100 L1320 300 L0 300"
    );
  }

  50% {
    d: path(
      "M0,192 C220,290,440,290,660,192 C880,100,1100,100,1320,192 L1320 300 L0 300"
    );
  }

  75% {
    d: path(
      "M0,292 C220,292,440,100,660,100 C880,100,1100,292,1320,292 L1320 300 L0 300"
    );
  }

  100% {
    d: path(
      "M0,192 C220,100,440,100,660,192 C880,290,1100,290,1320,192 L1320 300 L0 300"
    );
  }
}

/* -- Keyframes -- */

@keyframes sumir {
 
  
  100% {
    top: -120%;
    opacity: 0.1;
  }

}
</style>
