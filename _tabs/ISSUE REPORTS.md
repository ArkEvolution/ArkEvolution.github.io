---
layout: page
icon: fas fa-tag
order: 2
title: ArkEvolution Results
permalink: /ISSUE-REPORTS/
nav_title: Evoluation Results
---

<style>
  /* 1. 让中间的内容容器撑满 */
  #core-wrapper {
    flex: 0 0 100% !important;
    max-width: 100% !important;
    width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  .row {
    margin: 0 !important;
    padding: 0 !important;
  }

  /* 2. 隐藏右侧侧边栏(目录等)，把右边的空间也抢过来 */
  #panel-wrapper {
    display: none !important;
  }

  /* 3. 解除文章内容区域的宽度限制和边距 */
  .post-content {
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }

  article.post {
    padding: 0 !important;
    margin: 0 !important;
  }

  /* 4. 彻底干掉主题自带的表格横向滚动层 */
  .table-wrapper {
    overflow-x: hidden !important; 
    width: 100% !important;
    max-width: 100% !important;
  }

  /* 5. 启用 Fixed 固定布局，强行锁定表格宽度为容器的 100% */
  .post-content table, .table-wrapper table {
    table-layout: fixed !important;
    width: 100% !important;
    max-width: 100% !important;
    border-collapse: collapse !important;
    font-size: 13px !important; 
    font-family: "Times New Roman", Times, serif;
    background: #ffffff;
    margin: 0 !important; 
  }

  /* 6. 强制所有单元格允许换行，打破主题的 nowrap 限制 */
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
  /* 7. 核心：精确分配 11 列的百分比宽度 (总和 100%) */
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
| 1 | @ohos/axios | 1.3.4 -> 1.8.4 | 109 | 86% | 84% | 312 | 24 | Style check &#10008; | Rejected | [PR #180](https://gitcode.com/openharmony-sig/ohos_axios/pull/180) |
| 2 | @ohos/axios | 1.3.4 -> 1.8.4 | 89 | 88% | 86% | 304 | 15 | Style check &#10008; | Rejected | [PR #181](https://gitcode.com/openharmony-sig/ohos_axios/pull/181) |
| 3 | @ohos/axios | 1.3.4 -> 1.8.4 | 76 | 87% | 85% | 509 | 21 | All reviews &#10004; | Merged | [PR #196](https://gitcode.com/openharmony-sig/ohos_axios/pull/196) |
| 4 | @ohos/axios | 1.3.4 -> 1.8.4 | 177 | 85% | 83% | 410 | 27 | All reviews &#10004; | Merged | [PR #197](https://gitcode.com/openharmony-sig/ohos_axios/pull/197) |
| 5 | @ohos/sax | 1.2.4 -> 1.4.4 | 23 | 100% | 100% | 85 | 0 | Style check &#10008; | Rejected | [PR #2847](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2847) |
| 6 | @ohos/sax | 1.2.4 -> 1.4.4 | 35 | 90% | 88% | 2384 | 78 | All reviews &#10004; | Merged | [PR #2952](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2952) |
| 7 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 5 | 95% | 92% | 582 | 23 | All reviews &#10004; | Merged | [PR #2953](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2953) |
| 8 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 8 | 100% | 100% | 431 | 0 | All reviews &#10004; | Merged | [PR #2954](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2954) |
| 9 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 7 | 100% | 100% | 428 | 0 | All reviews &#10004; | Merged | [PR #2955](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2955) |
| 10 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 6 | 92% | 89% | 416 | 12 | All reviews &#10004; | Merged | [PR #2956](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2956) |
| 11 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 4 | 100% | 100% | 419 | 0 | All reviews &#10004; | Merged | [PR #2957](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2957) |
| 12 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 3 | 100% | 100% | 437 | 0 | All reviews &#10004; | Merged | [PR #2958](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2958) |
| 13 | @ohos/xmpp | 0.13.1 -> 0.14.0 | 7 | 91% | 87% | 412 | 16 | All reviews &#10004; | Merged | [PR #2959](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2959) |
| 14 | @ohos/arangojs | 8.3.1 -> 8.5.0 | 8 | 93% | 91% | 521 | 31 | All reviews &#10004; | Merged | [PR #29](https://gitcode.com/openharmony-sig/arangojs/pull/29) |
| 15 | @ohos/arangojs | 8.3.1 -> 8.5.0 | 10 | 90% | 87% | 565 | 28 | All reviews &#10004; | Merged | [PR #30](https://gitcode.com/openharmony-sig/arangojs/pull/30) |
| 16 | @ohos/protobufjs | 7.2.4 -> 8.0.0 | 36 | 94% | 83% | 187 | 14 | All reviews &#10004; | Merged | [PR #90](https://gitcode.com/openharmony-tpc/protobuf/pull/90) |
| 17 | @ohos/htmlparser2 | 10.0.0 -> 10.0.1 | 203 | 100% | 100% | 56 | 0 | All reviews &#10004; | Merged | [PR #2960](https://gitcode.com/openharmony-tpc/openharmony_tpc_samples/pull/2960) |
| 18 | @ohos/jsonwebtoken | 9.0.1 -> 9.0.3 | 4 | 100% | 100% | 18 | 0 | All reviews &#10004; | Merged | [PR #27](https://gitcode.com/openharmony-sig/ohos_jsonwebtoken/pull/27) |
| 19 | Random-int | 3.0.0 -> 3.1.0 | 3 | 100% | 100% | 516 | 0 | All reviews &#10004; | Merged | [PR #2](https://gitee.com/ArkTSCentralRepository/random-int/pulls/2) |
