<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14304F,50:1A5F7A,100:5B8DEF&height=200&section=header&text=CodeFox&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Econometrics%20%C2%B7%20Accounting%20%C2%B7%20Open%20Source%20Tooling&descAlignY=54&descSize=16" width="100%" alt="header" />

<a href="https://codefoxs.github.io">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1200&color=5B8DEF&center=true&vCenter=true&width=640&height=60&lines=PhD+Student+in+Accounting+%26+Finance;Stata+Package+Developer;Empirical+Research+%2B+Automation" alt="typing" />
</a>

<br/>

<a href="mailto:codefox2020@163.com"><img src="https://img.shields.io/badge/Email-1A5F7A?style=for-the-badge&logo=maildotru&logoColor=white" alt="email" /></a>
<a href="https://www.zhihu.com/people/Keynes"><img src="https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-Keynes-2E6F9E?style=for-the-badge&logo=zhihu&logoColor=white" alt="zhihu" /></a>
<a href="https://codefoxs.github.io"><img src="https://img.shields.io/badge/Blog-3E88C7?style=for-the-badge&logo=githubpages&logoColor=white" alt="blog" /></a>
<img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E5%87%AF%E6%81%A9%E6%96%AF%E5%AD%A6%E8%AE%A1%E9%87%8F-5B8DEF?style=for-the-badge&logo=wechat&logoColor=white" alt="wechat" />

</div>

---

## 👋 About Me

> 经管类在读博士，研究方向为 **会计与公司金融实证研究 · 微观计量方法**。
>
> 日常在 Stata 与 Python 之间来回横跳：一边跑回归，一边把重复劳动写成命令包。
> 下面的仓库基本都是自己做实证踩坑之后顺手造的轮子 —— 能少点一次鼠标，就多睡十分钟。
>
> 🍟 爱吃垃圾食品 · 🧋 快乐肥宅

<div align="center">

<img src="https://skillicons.dev/icons?i=python,latex,git,github,vscode,js,sqlite&theme=dark" alt="Python LaTeX Git GitHub VS Code JavaScript SQLite" />&nbsp;<img src="./assets/tech-extra.svg" alt="Stata SAS DuckDB pandas" height="48" />

</div>

---

## 🧰 Stata Toolbox

<div align="center"><i>做实证时长出来的命令包 · 点击命令名查看文档与安装方式</i></div>

<br/>

**📐 估计与推断 · Estimation & Inference**

| Command | 说明 |
| :--- | :--- |
| [**`ivreghdfe2`**](https://github.com/codefoxs/ivreghdfe2) | `ivreghdfe` 增强版：修正二阶段 VCE，补齐 IV 诊断统计量与常数项，并同时保存两个阶段的结果 |
| [**`pstest`**](https://github.com/codefoxs/pstest) | `pstest` 改版：PSM / ebalance 的平衡性检验结果一键转成 dta，方便直接排版成表 |

**🧹 数据处理 · Data Wrangling**

| Command | 说明 |
| :--- | :--- |
| [**`pmerge`**](https://github.com/codefoxs/pmerge) | 把 SQL 的 join 语义搬进 Stata，底层由 DuckDB 驱动，大表合并不再受内存摆布 |
| [**`cncity`**](https://github.com/codefoxs/cncity) | 中国城市名标准化：把「深圳」「深圳市」「广东省深圳市」归到同一个口径 |
| [**`cnprov`**](https://github.com/codefoxs/cnprov) | 中国省份名标准化，`cncity` 的省级版本 |
| [**`csmar`**](https://github.com/codefoxs/csmar) | 一行命令导入 CSMAR 的 zip / xlsx 原始文件，自动处理表头与变量名大小写 |
| [**`batch`**](https://github.com/codefoxs/batch) | 把命令模板套到 varlist 的每个变量上：`batch price mpg, f(gen l@ = log(@))` |
| [**`datedv`**](https://github.com/codefoxs/datedv) | 快速日期处理，省掉一堆 `date()` / `format` 的样板代码 |

---

## 🔬 Research Automation

| Project | 说明 |
| :--- | :--- |
| [**`journal-rss`**](https://github.com/codefoxs/journal-rss) | 为 12 本财会顶刊生成 RSS 订阅源，数据取自 Crossref + OpenAlex，定时自动更新，不必再逐个刷期刊主页 |
| [**`chinese_comovement`**](https://github.com/codefoxs/chinese_comovement) | 计算中国上市公司股票收益共同运动（stock price synchronicity）的 SAS 代码 |

---

## 🛠 Productivity Plugins

| Plugin | 说明 |
| :--- | :--- |
| [**`utools-dataview`**](https://github.com/codefoxs/utools-dataview) | uTools 插件：秒开 csv / parquet / xlsx / dta / sav / sas7bdat 等数据文件，DuckDB 驱动，看一眼数据不用再启动 Stata |
| [**`udict`**](https://github.com/codefoxs/udict) | uTools 插件：离线 MDX / MDD 词典查询，写英文论文时的贴身查词工具 |

---

## 📊 GitHub Stats

<div align="center">
<img src="https://img.shields.io/github/followers/codefoxs?style=for-the-badge&logo=github&label=Followers&color=5B8DEF&labelColor=0d1117" alt="followers" />
<img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fcodefoxs&query=%24.public_repos&label=Repos&style=for-the-badge&logo=github&color=5B8DEF&labelColor=0d1117" alt="repos" />
<img src="https://komarev.com/ghpvc/?username=codefoxs&style=for-the-badge&label=Views&color=5B8DEF" alt="views" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=codefoxs&bg_color=0d1117&color=5B8DEF&line=5B8DEF&point=ffffff&area=true&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=codefoxs&bg_color=ffffff&color=1A5F7A&line=1A5F7A&point=1A5F7A&area=true&hide_border=true" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=codefoxs&area=true&hide_border=true" width="100%" alt="activity graph" />
</picture>

</div>

<!--
  已移除 streak-stats.demolab.com 的连续提交卡片：该服务响应耗时实测 3~22 秒
  （其余组件均 <1 秒），远超 GitHub camo 图片代理的抓取超时，导致长期裂图；
  且偶发返回残缺 SVG。贡献趋势已由上方 activity graph 与下方蛇图覆盖。
-->

<!--
  想加上 github-readme-stats 的「统计卡片 / 语言占比卡片」，需要自部署一个 Vercel 实例：
  官方公共实例 github-readme-stats.vercel.app 已 DEPLOYMENT_PAUSED，
  github-profile-trophy.vercel.app 已 Payment required，都不可用，故此处未采用。

  自部署后把 YOUR-INSTANCE 换成自己的域名，粘回上面的 <div align="center"> 里即可：

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://YOUR-INSTANCE.vercel.app/api?username=codefoxs&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=5B8DEF&icon_color=5B8DEF&text_color=c9d1d9&bg_color=0d1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://YOUR-INSTANCE.vercel.app/api?username=codefoxs&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&title_color=1A5F7A&icon_color=1A5F7A&text_color=24292f&bg_color=ffffff" />
    <img src="https://YOUR-INSTANCE.vercel.app/api?username=codefoxs&show_icons=true&hide_border=true" height="170" alt="stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://YOUR-INSTANCE.vercel.app/api/top-langs/?username=codefoxs&layout=compact&langs_count=8&hide_border=true&title_color=5B8DEF&text_color=c9d1d9&bg_color=0d1117" />
    <source media="(prefers-color-scheme: light)" srcset="https://YOUR-INSTANCE.vercel.app/api/top-langs/?username=codefoxs&layout=compact&langs_count=8&hide_border=true&title_color=1A5F7A&text_color=24292f&bg_color=ffffff" />
    <img src="https://YOUR-INSTANCE.vercel.app/api/top-langs/?username=codefoxs&layout=compact&hide_border=true" height="170" alt="top langs" />
  </picture>
-->


---

## 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/codefoxs/codefoxs/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/codefoxs/codefoxs/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/codefoxs/codefoxs/output/github-snake.svg" alt="snake" />
</picture>

</div>

---

<div align="center">

<i>做研究之余写点小工具。如果哪个命令帮你省下了半小时，给个 ⭐ 就是最好的反馈。</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5B8DEF,50:1A5F7A,100:14304F&height=120&section=footer" width="100%" alt="footer" />

</div>
