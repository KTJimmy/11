%%{init: {'theme': 'neutral', 'themeVariables': { 'background': '#ffffff', 'primaryBorderColor': '#000', 'lineColor': '#000'}}}%%
graph TD
    classDef title fill:#fff,stroke:#000,stroke-width:2px,font-size:18px,font-weight:bold
    classDef box fill:#fff,stroke:#000,stroke-width:1px,rx:4,ry:4,font-size:12px

    T1[改良农户种植困境现状、改善农业技术推广机制的实现路径]:::title

    subgraph S1 [研究基础]
        direction TB
        A1[调查背景: 科技发展产生的先进农业技术; 乡村振兴战略实现农业现代化发展的基本要求]:::box
        A2[问题探讨: 我国农业技术推广的普及程度? 基层农户对农业技术推广的需求与现实困境]:::box
        A3[文献搜索: 农业技术推广的存在的问题及对策; 农技推广相关的政策]:::box
    end

    subgraph S2 [分期框架]
        direction TB
        B1[农业技术推广研究现状]:::box
        B2[国内研究现状: 广东“农友圈”平台; 山东三级联动推广模式; 湖北以钱养事、以事养人]:::box
        B3[国外研究现状: 美国“三位一体”模式; 法国“政产学研”融合; 加拿大校企合作]:::box
        B1 --> B2
        B1 --> B3
    end

    subgraph S3 [调查设计]
        direction TB
        C1[基于武汉市部分村镇及其农业推广局的调查研究]:::box
        C2[问卷设计]:::box
        C3[数据分析]:::box
        C4[方法选择]:::box
        C5[模型搭建]:::box
        
        C6[分析问卷所得数据/总结访谈所得的结论]:::box
        C7[描述性统计分析/主题、案例分析]:::box
        
        C8[发现问题: 农户获取信息困难]:::box
        C9[对策: 农技推广人员积极性]:::box

        C1 --> C2
        C2 ~~~ C3 ~~~ C4 ~~~ C5
        C3 --> C6
        C6 --> C7
        C7 --> C8
        C7 --> C9
    end

    T1 --- S1
    S1 --- S2
    S2 --- S3```
