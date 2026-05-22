---
layout: page
icon: fas fa-tag
order: 2
title: ArkEvolution Results
permalink: /ISSUE-REPORTS/
nav_title: Evoluation Results
---

<style>
  #core-wrapper {
    flex: 0 0 100%;
    max-width: 100%;
    width: 100%;
  }

  #panel-wrapper {
    display: none;
  }

  .post-content {
    max-width: none;
  }

  /* 彻底禁用横向滚动条，交由浏览器压缩列宽 */
  .post-content .table-wrapper {
    width: 100%;
    padding-bottom: 0.5rem;
  }

  .post-content table {
    border-collapse: collapse !important;
    border-spacing: 0 !important;
    color: #111111;
    font-family: "Times New Roman", Times, serif;
    /* 改为 auto，让浏览器根据内容长短自动分配列宽 */
    table-layout: auto !important; 
    width: 100% !important;
    /* 字体微调为 0.95rem，保证清晰可读的同时节省总宽度 */
    font-size: 0.95rem; 
    background: #ffffff;
  }

  .post-content th,
  .post-content td {
    border: 1px solid #222222 !important;
    /* 减小内边距 (padding)，去掉不必要的空白区域 */
    padding: 0.25rem 0.35rem; 
    text-align: center;
    white-space: normal;
    /* 强制长单词和 URL 链接直接换行，防止单独一列撑破屏幕 */
    word-break: break-all; 
    vertical-align: middle;
  }

  .post-content th {
    background: #666666 !important;
    color: #ffffff;
    font-size: 1rem;
    font-style: italic;
    font-weight: 700;
    line-height: 1.35;
  }

  .post-content tbody tr {
    background: #ffffff !important;
  }

  .post-content tbody tr:nth-child(even),
  .post-content tbody tr:nth-child(odd) {
    background: #ffffff !important;
  }

  .post-content td:nth-child(2) {
    font-weight: 700;
    font-style: italic;
    text-align: left;
  }

  .post-content td:nth-child(11) a {
    color: #005fff;
    font-style: italic;
  }

  /* 强制压缩第 7 列和第 8 列的宽度，逼迫长表头自然换行 */
  .post-content th:nth-child(7),
  .post-content td:nth-child(7),
  .post-content th:nth-child(8),
  .post-content td:nth-child(8) {
    width: 85px !important; /* 根据效果可适当增减此值 */
    max-width: 85px !important;
    white-space: normal !important; 
    word-break: normal !important; /* 按英文单词自然换行，避免单词被生硬切断 */
    line-height: 1.2 !important; 
  }
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
