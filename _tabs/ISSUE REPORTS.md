---
layout: page
icon: fas fa-tag
order: 2
title: ArkEvolution Results
permalink: /ISSUE-REPORTS/
nav_title: Evoluation Results
---

<style>
  /* 1. 彻底干掉 Jekyll 主题自带的表格横向滚动层，限制其最大宽度不超过父容器 */
  .table-wrapper {
    overflow-x: hidden !important; 
    width: 100% !important;
    max-width: 100% !important;
  }

  /* 2. 启用 Fixed 固定布局，强行锁定表格宽度为容器的 100% */
  .post-content table, .table-wrapper table {
    table-layout: fixed !important;
    width: 100% !important;
    max-width: 100% !important;
    border-collapse: collapse !important;
    font-size: 13px !important; 
    font-family: "Times New Roman", Times, serif;
    background: #ffffff;
    margin: 0 !important; /* 防止多余外边距撑开页面 */
  }

  /* 3. 强制所有单元格允许换行，打破主题的 nowrap 限制 */
  .post-content th, .post-content td, .table-wrapper th, .table-wrapper td {
    white-space: normal !important;
    word-wrap: break-word !important; 
    word-break: break-word !important; 
    padding: 6px 4px !important; 
    text-align: center;
    vertical-align: middle;
    border: 1px solid #222222 !important;
    line-height: 1.3 !important;
  }

  .post-content th, .table-wrapper th {
    background: #666666 !important;
    color: #ffffff !important;
    font-style: italic;
    font-weight: 700;
  }

  .post-content td:nth-child(2) {
    font-weight: 700;
    font-style: italic;
    text-align: left;
  }

  .post-content td:nth-child(11) a {
    color: #005fff;
    font-style: italic;
    word-break: break-all !important; 
  }

  /* ========================================= */
  /* 4. 核心：精确分配 11 列的百分比宽度 (总和 100%) */
  /* ========================================= */
  th:nth-child(1), td:nth-child(1) { width: 4%; }   /* ID */
  th:nth-child(2), td:nth-child(2) { width: 10%; }  /* Package */
  th:nth-child(3), td:nth-child(3) { width: 11%; }  /* Version Upgrades */
  th:nth-child(4), td:nth-child(4) { width: 7%; }   /* Commits */
  th:nth-child(5), td:nth-child(5) { width: 6%; }   /* CPR */
  th:nth-child(6), td:nth-child(6) { width: 6%; }   /* TPR */
  th:nth-child(7), td:nth-child(7) { width: 13%; }  /* Modified by Ark */
  th:nth-child(8), td:nth-child(8) { width: 12%; }  /* Manually modified */
  th:nth-child(9), td:nth-child(9) { width: 12%; }  /* CI Check */
  th:nth-child(10), td:nth-child(10) { width: 8%; } /* PR status */
  th:nth-child(11), td:nth-child(11) { width: 11%; }/* PR Link */

</style>

| ID | Package | Version Upgrades | # Code Commits | CPR (%) | TPR (%) | # Modified Code Lines by ArkEvolution | # Manually modified code lines | OpenHarmony CI Check | PR status | PR Link |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | protobuf | 7.2.4 -> 8.0.0 | 36 | 94% | 83% | 160 | 14 | All reviews passed | Merged | [PR #90](https://gitcode.com/openharmony-tpc/protobuf/pull/90) |
| 2 | xmpp | 0.13.1 -> 0.14.0 | 7 | 91% | 87% | 159 | 17 | All reviews passed | Merged | [PR #2953](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2953) |
| 3 | xmpp | 0.13.1 -> 0.14.0 | 3 | 100% | 100% | 125 | 0 | All reviews passed | Merged | [PR #2954](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2954) |
| 4 | xmpp | 0.13.1 -> 0.14.0 | 4 | 100% | 100% | 120 | 0 | All reviews passed | Merged | [PR #2955](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2955) |
| 5 | xmpp | 0.13.1 -> 0.14.0 | 6 | 100% | 100% | 131 | 0 | All reviews passed | Merged | [PR #2956](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2956) |
| 6 | xmpp | 0.13.1 -> 0.14.0 | 7 | 100% | 100% | 104 | 0 | All reviews passed | Merged | [PR #2957](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2957) |
| 7 | xmpp | 0.13.1 -> 0.14.0 | 8 | 100% | 100% | 137 | 0 | All reviews passed | Merged | [PR #2958](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2958) |
| 8 | xmpp | 0.13.1 -> 0.14.0 | 5 | 95% | 92% | 151 | 13 | All reviews passed | Merged | [PR #2959](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2959) |
| 9 | arangojs_8.4.1 | 8.3.1 -> 8.5.0 | 10 | 90% | 87% | 540 | 28 | All reviews passed | Merged | [PR #29](https://gitcode.com/openharmony-sig/arangojs/pull/29) |
| 10 | arangojs_8.5.0 | 8.3.1 -> 8.5.0 | 8 | 93% | 91% | 582 | 31 | All reviews passed | Merged | [PR #30](https://gitcode.com/openharmony-sig/arangojs/pull/30) |
| 11 | htmlparser2 | 10.0.0 -> 10.0.1 | 203 | 100% | 100% | 113 | 0 | Submitted image | Merged | [PR #2960](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2960) |
| 12 | random-int | 3.0.0 -> 3.1.0 | 6 | 100% | 100% | 143 | 0 | All reviews passed | Merged | [PR #1](https://gitee.com/ArkTSCentralRepository/random-int/pulls/1) |
| 13 | sax | 1.3.4 -> 1.8.4 | 35 | 90% | 88% | 135 | 8 | Submitted image | Merged | [PR #2952](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2952) |
| 14 | axios | 1.3.4 -> 1.8.4 | 177 | 85% | 83% | 530 | 27 | All reviews passed | Merged | [PR #196](https://gitcode.com/openharmony-sig/ohos_axios/pull/196) |
| 15 | axios | 1.3.4 -> 1.8.4 | 76 | 87% | 85% | 310 | 21 | All reviews passed | Merged | [PR #197](https://gitcode.com/openharmony-sig/ohos_axios/pull/197) |
| 16 | ohos_jsonwebtoken | 9.0.1 -> 9.0.3 | 4 | 100% | 100% | 108 | 0 | All reviews passed | Merged | [PR #27](https://gitcode.com/openharmony-sig/ohos_jsonwebtoken/pull/27) |
