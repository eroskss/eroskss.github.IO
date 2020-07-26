---
#layout: article
title: 网站上都有些什么？
permalink: /docs/What_is_on_the_page
key: docs-What-is-on-the-page
mermaid: True
---
## 网页的五大板块与一项配置

**注！** 该页面本为项目专项介绍之所，现为网页教学，如学成，删去`/docs/_docs/*`下所有文档，或不删自行修改、配置即可。
{:.error}
  
[complementary blog posts](/docs/enterprise_data_science
)

#### used python packages in the lecture

```
- numpy
- pandas
- scikit-learn
- bokeh
- seaborn
- tensorflow
```

<!--more-->
#### High level enterprise data science flow graph

The graph gives only a very high level abstraction of enterprise data science. Note, that many lectures are focusing on the top (technical) data science part. Which is important especially to train mandatory programming / math skill sets, however, the enterprise world is more complicated. The link to business and the impact is vey challenging. In the lecture series we try to address some high level aspects.

```mermaid
graph LR;
    A0(Enterprise Data Science)
    B0(Data Science -technical)
    B1[Enterprise Value]
    C0[Explorative IT - Explain]
    C1[Math/ML]
    C2[Operational IT - Deploy]
    D0[Business Processes]
    D1[Decisions and Impact]
    E0(Continuous Support & Operation)
    F0[Dashboards]
    F1[Homepage / App]
    F2[IT Backend]
    G3[Communication / Change]
    A0-->B0;
    A0-->B1;
    B0-->C0;
    B0-->C1;
    B1-->D0;
    B1-->D1;
    C1-->C0;
    C1-->C2;
    B0-->C2;
    C2-->E0;
    C0-->F0;
    D0-->C2;
    D0-->E0;
    D1-->E0;

    E0-->F0;
    E0-->F1;
    E0-->F2;
    E0-->G3;
    F0-->G3;
    F1-->G3;
    F2-->G3;
    D1-->G3;
```
