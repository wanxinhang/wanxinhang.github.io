<h1>🔥 News</h1>
<p><em>(Papers as first author are bolded.)</em></p>

<ul id="news-list">
  <li><em>2026.11</em>: &nbsp; Our ACM MM 2026 paper won the <font color="red" bgcolor="grey">Outstanding Paper Award</font> (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2026.11</em>: &nbsp; One paper has been accepted by IEEE-TPAMI (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</li>
  <li><em>2026.07</em>: &nbsp; One paper has been accepted by IEEE-TPAMI (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</li>
  <li><em>2026.07</em>: &nbsp; One paper is featured as a <font color="red" bgcolor="grey">ESI Highly Cited Paper</font>.</li>
  <li><em>2026.07</em>: &nbsp; One paper has been accepted by ACM MM 2027 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2026.06</em>: &nbsp; One paper has been accepted by UAI (<font color="red" bgcolor="grey">CAAI A</font>).</li>
  <li><em>2026.03</em>: &nbsp; One paper has been accepted by IEEE-TKDE (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</li>
  <li><em>2025.11</em>: &nbsp; One paper has been accepted by AAAI 2026 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2025.09</em>: &nbsp; One paper has been accepted by IEEE-TCSVT (<font color="red" bgcolor="grey">CCF B, SCI 1区</font>).</li>
  <li><em>2025.09</em>: &nbsp; Two papers have been accepted by Neurips 2025 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2025.08</em>: &nbsp; One paper has been accepted by IEEE-TKDE (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</li>
  <li><em>2025.08</em>: &nbsp; One paper has been accepted by IEEE-TPAMI (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</li>
  <li><em>2025.06</em>: &nbsp; <strong>One paper has been accepted by ICCV 2025 (<font color="red" bgcolor="grey">CCF A</font>)</strong>.</li>
  <li><em>2025.05</em>: &nbsp; <strong>My OMVCDR (IEEE TNNLS 2024) paper is featured as a <font color="red" bgcolor="grey">ESI Highly Cited Paper</font>.</strong></li>
  <li><em>2025.05</em>: &nbsp; One paper has been accepted by ICML 2025 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2025.02</em>: &nbsp; One paper has been accepted by CVPR 2025 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2024.12</em>: &nbsp; Two papers have been accepted by AAAI 2025 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2024.11</em>: &nbsp; I won China National Scholarship for Phd students.</li>
  <li><em>2024.11</em>: &nbsp; <strong>One paper has been accepted by IEEE-TNNLS (<font color="red" bgcolor="grey">CCF B, SCI 1区</font>).</strong></li>
  <li><em>2024.09</em>: &nbsp; One paper has been accepted by NDSS 2025 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2024.07</em>: &nbsp; One paper has been accepted by ACM MM 2024 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2024.05</em>: &nbsp; One paper has been accepted by IEEE-TKDE (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2024.05</em>: &nbsp; <strong>Two papers have been accepted by ICML 2024 (<font color="red" bgcolor="grey">CCF A</font>)</strong>.</li>
  <li><em>2024.03</em>: &nbsp; <strong>One paper has been accepted by IEEE-TIP (<font color="red" bgcolor="grey">CCF A, SCI 1区</font>).</strong></li>
  <li><em>2024.03</em>: &nbsp; <strong>One paper has been accepted by IEEE-TNNLS (<font color="red" bgcolor="grey">CCF B, SCI 1区</font>).</strong></li>
  <li><em>2023.07</em>: &nbsp; Two papers have been accepted by ACM MM 2023 (<font color="red" bgcolor="grey">CCF A</font>).</li>
  <li><em>2023.06</em>: &nbsp; One paper has been accepted by IEEE-TNNLS (<font color="red" bgcolor="grey">CCF B, SCI 1区</font>).</li>
  <li><em>2022.12</em>: &nbsp; <strong>One paper has been accepted by AAAI 2023 (<font color="red" bgcolor="grey">CCF A</font>)</strong>.</li>
  <li><em>2022.06</em>: &nbsp; <strong>One paper has been accepted by ACM MM 2022 (<font color="red" bgcolor="grey">CCF A</font>)</strong>.</li>
</ul>

<p style="text-align: center; margin-top: 8px;">
  <a href="javascript:void(0);" id="news-toggle" onclick="toggleNews()" style="cursor: pointer; font-size: 0.95em;">⬇ 展开更多</a>
</p>

<script>
(function () {
  var VISIBLE_COUNT = 8; // 只改这里就能控制默认显示几条
  var list = document.getElementById('news-list');
  var items = Array.prototype.slice.call(list.children);
  var btn = document.getElementById('news-toggle');
  var expanded = false;

  function render() {
    items.forEach(function (li, i) {
      // 默认：前 VISIBLE_COUNT 条显示；展开后全部显示
      li.style.display = (expanded || i < VISIBLE_COUNT) ? '' : 'none';
    });
    btn.innerHTML = expanded ? '⬆ 收起' : '⬇ 展开更多';
    // 如果新闻总数不超过可见条数，就隐藏按钮
    btn.parentNode.style.display = (items.length <= VISIBLE_COUNT) ? 'none' : '';
  }

  window.toggleNews = function () {
    expanded = !expanded;
    render();
  };

  render();
})();
</script>
