graph TD
    %% --- 全局样式定义 ---
    classDef mainTitle fill:#fff,stroke:#000,stroke-width:2px,font-weight:bold,font-size:18px
    classDef block fill:#fff,stroke:#000,stroke-width:1px,font-size:14px
    
    %% --- 顶部主标题 ---
    Top[改良农户种植困境现状、改善农业技术推广机制的实现路径]:::mainTitle
    
    %% --- 第一大模块：研究基础 ---
    subgraph Phase1 [研究基础]
        direction TB
        P1[调查背景: 科技发展产生的先进农业技术; 乡村振兴战略实现农业现代化发展的基本要求]:::block
        P2[问题探讨: 我国农业技术推广的普及程度? 基层农户对农业技术推广的需求与现实困境]:::block
        P3[文献搜索: 农业技术推广的存在的问题及对策; 农技推广相关的政策]:::block
    end
    
    %% --- 第二大模块：分期框架 ---
    subgraph Phase2 [分期框架]
        direction TB
        Title2[农业技术推广研究现状]:::block
        
        subgraph Sub2 [ ]
            direction LR
            D1[国内研究现状: 广东“农友圈”平台; 山东三级联动推广模式; 湖北以钱养事、以事养人]:::block
            D2[国外研究现状: 美国“三位一体”模式; 法国“政产学研”融合; 加拿大校企合作]:::block
        end
        Title2 --> Sub2
    end
    
    %% --- 第三大模块：调查设计 ---
    subgraph Phase3 [调查设计]
        direction TB
        Title3[基于武汉市部分村镇及其农业推广局的调查研究]:::block
        
        subgraph Sub3 [ ]
            direction TB
            S1[问卷设计]:::block
            S2[数据分析]:::block
            S3[方法选择]:::block
            S4[模型搭建]:::block
            
            C1[分析问卷所得数据/总结访谈所得的结论]:::block
            C2[描述性统计分析/主题、案例分析]:::block
            
            R1[发现问题: 农户获取信息困难]:::block
            R2[对策: 农技推广人员积极性]:::block
        end
        
        Title3 --> S1
        S1 ~~~ S2 ~~~ S3 ~~~ S4
        S2 --> C1
        C1 --> C2
        C2 --> R1
        C2 --> R2
    end
    
    %% --- 连接三大模块 ---
    Top --- Phase1
    Phase1 --- Phase2
    Phase2 --- Phase3
    
    %% --- 连线调整 ---
    linkStyle default stroke:#000,stroke-width:1.5px;
方法三：手动绘制教程（适合 Word / PPT）
