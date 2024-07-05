# 蛋白质组学专业术语备忘录 by Wenhao 🦅🦅🦅

## 基础生物化学术语

- **氨基酸（Amino Acid）**：构成蛋白质的基本单位，每个氨基酸包含一个中心的碳原子（Cα），连接一个氢原子、一个氨基（-NH2）、一个羧基（-COOH）和一个特定的侧链。

- **氨基（Amino Group）**：氨基酸中的组成部分，化学式为-NH2，是一个基本的含氮组。

- **羧基（Carboxyl Group）**：氨基酸中的另一个组成部分，化学式为-COOH，表现为酸性。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/4a51c8fc-1ebf-4dfe-83ba-cf0904a1fa07)

## 蛋白质结构与分析术语

- **序列（Sequence）**：指的是蛋白质或肽段中氨基酸的排列顺序，通常由一系列氨基酸的缩写字母表示。

- **蛋白质螺旋结构（Protein Helix Structure）**：蛋白质的一种二级结构，通常指α-螺旋，它是由氨基酸残基通过氢键形成的紧密卷曲的结构。这种结构在许多蛋白质中都能找到，对蛋白质的稳定性和功能具有重要作用。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/75b4269e-1ec6-49bd-8810-4c69c8f6d2df)

- **完整蛋白质（Intact Protein）**：指的是未经切割或消化的蛋白质分子，保持其原始的三维结构和生物功能。

- **肽段（Peptide）**：较短的氨基酸链，通常是在蛋白质消化过程中由特定酶（如胰蛋白酶）切割生成的。肽段比完整蛋白质小，更易于质谱分析。

- **肽中心（Peptide-Centric）**：一种蛋白质组学分析方法，强调对分析肽段而非整个蛋白质的重点。此方法通常用于自底向上蛋白质组学分析，侧重于通过肽段的鉴定和定量来推断整体蛋白质的信息。

## 蛋白质合成与结构术语

- **转录（Transcription）**：在细胞中，DNA序列被转录成mRNA的过程。这是蛋白质合成的第一步，涉及到从DNA信息转换成RNA的过程。

- **翻译（Translation）**：在细胞的核糖体上，mRNA模板被用来合成特定的蛋白质。这一过程涉及mRNA上的编码信息被翻译成氨基酸序列，进而形成蛋白质。
  
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/9c2303c8-710d-4ed7-8716-761302ee027c)

- **密码子（Codon）**：mRNA上由三个核苷酸组成的单位，对应于一个特定的氨基酸。密码子在翻译过程中指导特定氨基酸的加入到正在形成的蛋白质链中。

## 特定化学键和蛋白质修饰

- **肽键（Peptide Bond）**：连接两个氨基酸的羧基和氨基形成的共价键。这种键是通过一种脱水反应形成的，其中一个氨基酸的羧基与另一个氨基酸的氨基失去一个水分子而形成。

  ![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/d2e54286-3dd5-42ac-9fb0-0b1a68a44f2b)

- **蛋白质翻译后修饰（Post-Translational Modification, PTM）**：蛋白质在翻译后发生的化学修改，包括磷酸化、泛素化、糖基化等。这些修饰能够影响蛋白质的功能、稳定性、位置和相互作用。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/ff8024a3-c9e7-480e-b6a8-3ac7b4b77764)

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/cbdc815a-4298-49ee-b269-569b0f670d77)

### 蛋白质样本处理流程

1. **样本提取**：从生物样本中提取蛋白质是第一步。

2. **蛋白质定量**：在提取蛋白质后，需要对蛋白质进行定量，以确保后续步骤使用的蛋白质量一致。

3. **蛋白质还原（Reduction）**：还原步骤的目的是破坏蛋白质中的二硫键。

4. **蛋白质烷基化（Alkylation）**：烷基化步骤的目的是防止二硫键重新形成。

5. **蛋白质消化（Digestion）**：消化步骤的目的是将蛋白质切割成肽段。详细步骤如下：
   - 酶切前处理：将蛋白质样本在合适的缓冲液（如100 mM Tris-HCl，pH 8.0）中稀释。
   - 加入胰蛋白酶（Trypsin）：按1:50或1:100的酶与蛋白质比例加入胰蛋白酶。例如，若样本中有100 µg蛋白质，则加入2 µg胰蛋白酶（1:50比例）。
   - 酶解：将混合物在37°C孵育过夜（12-16小时），确保完全消化。
   - 终止酶解：可加入甲酸或乙酸调节pH至3以终止酶解反应。

6. **过胶（Gel Electrophoresis）**：为了分离蛋白质或肽段，可进行聚丙烯酰胺凝胶电泳（SDS-PAGE）。步骤如下：
   - 准备SDS-PAGE凝胶，并装入电泳槽。
   - 加入样本和Marker进行电泳，通常在恒电压（如100-150V）条件下运行1-2小时，直到染料前沿到达凝胶底部。
   - 电泳完成后，染色（如Coomassie Brilliant Blue染色）以可视化蛋白质带。
   - 去污（如用甲醇和乙酸）以去除背景染色。

7. **肽段纯化（Purification）**：消化后的肽段需要纯化，去除杂质和缓冲液成分。

8. **样本浓缩与干燥**：纯化后的肽段需要浓缩和干燥，以便于后续的质谱分析。

9. **质谱分析准备**：干燥后的肽段重新溶解在适当的溶剂中（如0.1%甲酸溶液），准备进行液相色谱-质谱联用（LC-MS/MS）分析。

10. **质谱数据分析**：通过LC-MS/MS获取质谱数据后，利用专业的软件（如Mascot、MaxQuant）进行数据分析和肽段鉴定。
 
液相色谱（LC）能够有效的将有机物待测样品中的有机物成分分离，而质谱（MS）能够对分开的有机物逐个的分析，得到有机物分子量，结构（在某些情况下）和浓度（定量分析）的信息。质谱的基本原理是蛋白质经过蛋白酶的酶切消化后成肽段混合物，液相色谱进行肽分离，在质谱仪中肽段混合物电离形成带电离子，质谱分析器的电场、磁场将具有特定质量与电荷比值（即质荷比，M/Z）的肽段离子分离开来，经过检测器收集分离的离子，确定每个离子的M/Z值。经过质量分析器可分析出每个肽段的M/Z，得到蛋白质所有肽段的M/Z图谱，即蛋白质的一级质谱峰图。离子选择装置自动选取强度较大肽段离子再次破碎和分析进行二级质谱分析，输出选取肽段的二级质谱峰图，通过和理论上蛋白质经过胰蛋白酶消化后产生的一级质谱峰图和二级质谱峰图进行比对而鉴定蛋白质。

## 自底向上蛋白质组学分析方法：

自底向上的蛋白质组学涉及到在质谱分析之前蛋白质的水解消化。术语自下而上意味着有关组成蛋白质的信息是由单独鉴定的片段肽重建的。
对于自底向上的蛋白质组学流程图，采用凝胶法，通过二维电泳分离蛋白质混合物。在斑点可视化后，从凝胶中提取蛋白质，消化，并进行质谱分析，通过数据库搜索进一步鉴定。采用无凝胶法，将蛋白质混合物直接消化为多肽混合物，通过多维分离方法分离。然后用质谱分析肽。利用数据库搜索从生成的质谱中鉴定蛋白质。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/25d48d1f-e78b-4095-8039-a0323840514b)

## 自顶向下蛋白质组学分析方法：
自上而下的蛋白质组学可以从复杂的生物系统中描述完整的蛋白质。这种方法通常允许接近100%的序列覆盖和蛋白质形态的全部特征，蛋白质形态是由遗传变异、可变剪接和翻译后修饰组合而成的特定分子形式。串联质谱的裂解是通过电子俘获解离(ECD)或电子转移解离(ETD)完成的。蛋白质通常被电喷雾电离并在傅立叶变换离子回旋共振或四极离子阱质谱仪中捕获。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/a83c8659-b99b-4008-b63b-bca6b5740327)

# 蛋白质多组学关键术语及其在蛋白质测序中的作用

## Spectram 和 Spectra
- **定义**：Spectram (通常指的是单数形式，但较少使用) 和 Spectra (复数形式) 指的是通过质谱仪生成的**图谱**，显示了不同质量的离子在质谱中的分布。
- **作用**：在蛋白质测序中，质谱图被用来鉴定蛋白质样本中的**肽段**和蛋白质，通过测量它们的质量到电荷比（m/z）来进行。

## Pepsin
- **定义**：Pepsin 是一种消化酶，通常在蛋白质消化过程中用于辅助肽链的分解。
- **作用**：在蛋白质测序中，pepsin 可用于在体外消化蛋白质，从而生成较小的肽段，这些肽段随后可以通过质谱进行分析。

## Sequence
- **定义**：Sequence 指的是蛋白质或肽段的氨基酸序列。
- **作用**：蛋白质序列的确定是蛋白质测序的核心部分，通过比对实验得到的质谱数据与已知的蛋白质数据库，可以推断出未知样本的蛋白质序列。

## Light Chain 和 Heavy Chain
- **定义**：
  - **Light Chain**：轻链，是构成某些类型蛋白质（如抗体）的较小的多肽链。
  - **Heavy Chain**：重链，是同一蛋白质中较大的多肽链。
- **作用**：在蛋白质测序中，特别是在研究抗体时，区分轻链和重链对于了解抗体的结构和功能至关重要。
- 
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/91f74eb3-4384-4696-9319-f860fdf64aae)

## In Solution 和 In Gel
- **定义**：
  - **In Solution**：指的是在溶液中进行的实验。
  - **In Gel**：指的是在凝胶（如聚丙烯酰胺凝胶）中进行的实验。
- **作用**：这两种方式通常用于蛋白质或肽段的分离和净化，有助于随后的质谱分析。在溶液中的处理通常涉及到液相色谱，而凝胶通常用于电泳。
- **区别**：
  - **In Solution** 方法涉及将蛋白质或肽段直接在溶液中处理，适合于快速、直接的样品处理。
  - **In Gel** 方法涉及将样品首先通过凝胶电泳分离，然后进行进一步的处理，有利于处理复杂或含杂质较多的样品。

## Alignment
- **定义**：Alignment 指的是序列比对，是将蛋白质或核酸序列与已知的数据库进行比对，以寻找相似的序列。
- **作用**：在蛋白质测序中，通过比对可以帮助识别未知序列中的已知蛋白质或功能区域，这对于理解蛋白质的功能和结构至关重要。

## Everybody's Sequence
- **定义**：虽不是一个专业术语，这里我们假设指的是在多个蛋白质样本中普遍存在的序列。
- **作用**：识别这些普遍的序列可以帮助研究者快速识别常见的蛋白质或肽段，有助于标准化实验流程和数据比较。

## m/z (Mass-to-Charge Ratio)
- **定义**：m/z 是质量到电荷比的缩写，表示在质谱分析中检测到的离子的质量与其电荷数的比值。
- **作用**：m/z 是质谱分析中最基本的测量指标，用于鉴定和区分不同的分子和离子。在蛋白质测序中，通过分析肽段或蛋白质的m/z值，可以推断其结构和组成。

## Intensity
- **定义**：在质谱图中，Intensity 指的是某个特定m/z值下，离子信号的强度。
- **作用**：信号强度反映了在样品中该离子的相对丰度。在蛋白质测序中，通过比较**不同肽段的信号强度**，可以估计蛋白质或肽段的丰度，这对于定量分析和比较不同样本中蛋白质表达的差异非常重要。

# UV 图与 TIC 图
在蛋白质多组学中，UV图和TIC图是两种常用的色谱分析图谱，它们在分析蛋白质的组成、结构和性质方面起着重要作用。

## UV图（UV Chromatogram）：
UV图是通过紫外线吸收检测器记录样品在色谱柱中流动过程中紫外线吸收的变化而得到的图谱。在蛋白质多组学中，UV图主要用于检测蛋白质及其相关物质在不同波长下的吸光度变化。蛋白质在紫外区域（通常在200至280纳米范围内）有明显的吸收峰，这些峰可以用来监测蛋白质在色谱柱中的分离情况。UV图可以提供关于蛋白质含量、纯度和杂质含量的信息，因此在蛋白质分离纯化和定量分析中被广泛应用。
- 横轴（X轴）：通常表示色谱分析的时间或者色谱柱的洗脱时间。在色谱过程中，样品成分会根据其特性以不同的速率从色谱柱中洗脱出来，横轴上的时间表示这个洗脱过程。
- 纵轴（Y轴）：表示紫外线吸收度（或称为吸光度）。在UV图中，纵轴上的数值表示样品在不同波长下的吸光度值。蛋白质在UV区域有明显的吸收峰，通过检测这些吸收峰的强度可以了解样品中蛋白质的含量、纯度和杂质含量。

## TIC图（Total Ion Chromatogram）：
TIC图是通过质谱检测器记录样品在色谱柱中流动过程中产生的离子总数随时间变化而得到的图谱。在蛋白质多组学中，TIC图主要用于监测样品中蛋白质及其降解产物的离子信号。通过质谱检测器，可以将样品中的蛋白质分子转化为离子，进而得到TIC图。TIC图可以提供关于样品中蛋白质的分子量、离子强度和离子分布等信息，对于鉴定蛋白质及其修饰、降解产物等具有重要意义。
- 横轴（X轴）：同样表示色谱分析的时间或者色谱柱的洗脱时间。在色谱过程中，样品成分会随着时间从色谱柱中洗脱出来，横轴上的时间反映了这个洗脱过程的时间变化。
- 纵轴（Y轴）：表示质谱信号的强度。TIC图中的纵轴上的数值表示样品中产生的总离子信号的强度。这些离子信号来自于质谱检测器对样品中蛋白质分子产生的离子进行检测，反映了样品中蛋白质及其相关物质的分布和丰度。
  
UV图和TIC图在蛋白质多组学中通常结合使用，通过色谱分离和质谱检测相结合的方式，全面地了解样品中蛋白质的组成、结构和性质。这些图谱可以为蛋白质研究提供关键的定性和定量信息，有助于深入理解蛋白质的功能和生物学特性。总的来说，UV图和TIC图都是通过记录样品在色谱过程中的变化来获取信息的，只不过UV图主要关注样品在紫外区域的吸光度变化，而TIC图则主要关注样品中产生的总离子信号的强度变化。通过这些图谱，可以了解样品中蛋白质的分离、组成和特性，为蛋白质多组学研究提供重要的数据支持。

**在质谱检测中，离子的生成和检测速度通常比UV检测要慢，这可能导致TIC图中的峰出现时间相对较晚。离子化的过程需要一定的时间，而且离子信号的累积也需要一定的时间，因此TIC图中的峰出现时间可能相对延迟 。**

## Epibiologics Antibody（上皮生物学抗体）
上皮生物学抗体是指专门针对上皮组织中蛋白质或多肽的特异性抗体。上皮细胞覆盖身体的内外表面，广泛存在于皮肤、呼吸道、消化道等部位。上皮生物学抗体在以下几个方面具有重要作用：
- 癌症研究和治疗：许多上皮来源的肿瘤，如乳腺癌、结肠癌等，可以通过识别特异性抗原的抗体进行标记，从而用于诊断和靶向治疗。
- 免疫检测：上皮生物学抗体可以用于检测上皮细胞表面特定抗原，帮助了解疾病进展和治疗效果。

## Glycan（糖链）
糖链是蛋白质上的糖基化修饰部分，由多个单糖分子通过糖苷键连接而成。糖基化是蛋白质翻译后修饰（PTM）中最常见的形式之一，对蛋白质的稳定性、功能和细胞间相互作用具有重要影响。
- 结构和功能稳定性：糖基化可以影响蛋白质的折叠、稳定性和半衰期。
- 细胞识别和信号传导：糖链在细胞识别、信号传导和免疫应答中起关键作用。
- 疾病相关性：异常的糖基化与许多疾病相关，如癌症、糖尿病和神经退行性疾病。

## Disulfide Bond（二硫键）
二硫键是由两个半胱氨酸残基之间的硫原子形成的共价键。二硫键在蛋白质的三维结构和功能稳定性方面起重要作用。
- 结构稳定性：二硫键帮助蛋白质维持其三维结构，防止蛋白质变性和降解。
- 蛋白质折叠：二硫键在蛋白质折叠过程中起调控作用，确保蛋白质正确折叠。
- 功能调控：二硫键可以调控蛋白质的活性，如酶的活性和受体的功能。

## Hinge Region（铰链区）
铰链区是抗体分子中连接恒定区（C区）和可变区（V区）的灵活区域，允许抗体在结合抗原时灵活运动。
- 灵活性和结合性：铰链区的灵活性使抗体能够更好地结合抗原，增加结合效率。
- 效应功能：铰链区对抗体的效应功能（如与Fc受体结合和补体激活）具有重要作用，影响抗体的免疫效应。

## Inter Chain（链间）
链间是指多肽链之间的相互作用或连接，尤其是指在多肽或蛋白质二级和三级结构中的链间二硫键或非共价相互作用。
- 蛋白质复合物形成：链间相互作用对于蛋白质复合物的形成和稳定至关重要，如抗体的重链和轻链之间的连接。
- 功能协调：链间相互作用可以调控蛋白质复合物的功能，如酶-底物复合物的形成和解离。

## Intra Chain（链内）
链内是指同一多肽链内部的相互作用或连接，如链内二硫键或其他结构域之间的相互作用。
- 蛋白质折叠：链内相互作用对蛋白质的正确折叠和功能至关重要。
- 稳定性和活性：链内二硫键和其他相互作用可以增强蛋白质的稳定性和活性，防止变性和降解。

## IgG1（免疫球蛋白G1）
IgG1是免疫球蛋白G（IgG）家族中的一个亚型，是人体血清中最主要的抗体类型之一，占IgG总量的70-75%。

- 中和作用：IgG1可以中和病毒、细菌毒素等病原体。
- 调理吞噬作用：IgG1通过与Fc受体结合，促进吞噬细胞识别和清除病原体。
- 补体激活：IgG1可以激活补体系统，增强免疫反应。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/14587a9f-07b0-48b7-84f2-3f24dabfc322)
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/4c07160a-4ae1-4482-a9c4-d277c489f319)

![image](https://github.com/liyinred/Proteomics/assets/83255231/9f79e355-c32f-47f9-b79d-d78ffca6ad54)

## IgM的结构
免疫球蛋白 M 是第三种最常见的血清免疫球蛋白，有两种形式：

1. 所有重链和轻链均相同的五聚体
2. 单体（在 B 淋巴细胞中作为 B 细胞受体存在）
- 在 B 细胞表面，该分子以具有四链单元（两个 μ H 链和两个 L 链）的单体形式表达于质膜上。
- 在这种形式下，它是一种 B 细胞抗原受体，其中每个 H 链均含有额外的疏水结构域，用于锚定在膜上。
- 在血液中，IgM 由五个四链单位（五聚体）组成，这些单位通过 μ 链羧基末端的二硫键连接在一起。
- 五聚体结构中的五个单体均由两条轻链（κ 或 λ）和两条重链组成。然而，与 IgG 不同，IgM 单体中的重链由一个可变区和四个恒定区组成，其中额外的恒定区取代了铰链区。
- J 链也与血液中的 IgM 相关，并在其从浆细胞分泌时启动其亚基的聚合。
![image](https://github.com/liyinred/Proteomics/assets/83255231/bc7affb2-b1b3-48ff-89ad-b3785421ab7d)

## 打开二硫键的目的
- 结构解析：二硫键（-S-S-）是蛋白质二级、三级和四级结构的重要组成部分。它们在蛋白质折叠和维持稳定结构中起着关键作用。通过还原剂如二硫苏糖醇（DTT）或2-巯基乙醇打开二硫键，可以使蛋白质解折叠，从而更容易进行后续的结构解析。
- 质谱分析准备：质谱法（MS）用于蛋白质鉴定和定量分析时，蛋白质的解折叠和二硫键的还原是必要的步骤。这有助于提高酶切效率和质谱分析的精度。

## 打开二硫键后质谱得到轻重链分子量的目的
- 确定蛋白质亚基结构：在抗体等多亚基蛋白质中，轻链和重链通过二硫键连接。通过还原二硫键，可以分离轻链和重链，分别测定其分子量。这对于确定抗体的亚基组成和结构非常重要。
- 检测蛋白质修饰和变异：质谱可以精确测量蛋白质片段的分子量，从而检测蛋白质的翻译后修饰（如糖基化、磷酸化）和变异（如突变、缺失）。通过分离轻链和重链，可以更清晰地分析这些修饰和变异的分布情况。

**在蛋白质多组学和生物化学中，“Da”代表道尔顿（Dalton），这是衡量原子和分子的质量单位。一个道尔顿等于一个质子的质量，即约1.66053906660 × 10^-27 千克。在蛋白质研究中，道尔顿常用来表示蛋白质或多肽链的分子量（也称为相对分子质量，Mr）。**

**CRO（Contract Research Organization，合同研究组织）** 业务是指为医药、医疗器械和生物技术公司提供临床试验及其他相关研究服务的商业服务。CRO通过合同形式，与制药公司、科研机构等合作，承担药物研发过程中从临床前研究到临床试验各个阶段的任务。
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/3c985859-44c6-489e-8e3e-df0dded70c67)

**Handover sheet（交接单）** 是一种记录和传递信息的文件，通常在工作班次交接、项目管理、医疗护理以及其他需要明确职责和任务交接的场合中使用。

**Quotation（引文或引用）** 在学术写作、文学创作、演讲以及日常交流中都是一种常见的修辞手法。它是指引用他人说过的话、写过的文字或创作的作品，以支持自己的观点、增强说服力或提供背景信息。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/27338ba7-90a2-4811-97a1-6fdf3f2879e8)
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/f5ae93e1-23c5-4ebf-93c6-f08612b93159)

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/2186e386-a657-4181-82b6-249ee61271ad)

图片中的数据列出了两种不同状态下的抗体（E03258_Ab2 和 E03263_degly_Ab2）测量的分子量（Da）。

![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/764c44b0-b7c1-43d5-9703-9d03e051e8c9)
![image](https://github.com/liyinred/Proteomics_Wenhao/assets/83255231/8bf069df-43cf-4737-ae48-a8f1237ea24d)

字母表示氨基酸序列，每三个字母代表一个氨基酸。

IGHM_HUMAN：这是蛋白质的名称，其中IGHM表示免疫球蛋白重链μ，HUMAN表示这是人类（Homo sapiens）的序列。
Immunoglobulin heavy constant mu：这是蛋白质的描述信息，表示该序列是免疫球蛋白重链μ。

人类免疫球蛋白G（IgG）中的重链序列具有特定的结构特征。重链的可变区（VH）通常从一个保守的氨基酸序列开始，以Q（谷氨酰胺）作为起始氨基酸，而恒定区（CH）在PGK（脯氨酸-甘氨酸-赖氨酸）处结束。

**IgG_heavy_high_mass**通常指的是在分析过程中检测到的IgG重链的高分子质量状态。这种状态可能是由于重链上有多个糖基化位点或其他翻译后修饰（post-translational modifications, PTMs）所引起的。这些修饰可能包括：
- 糖基化（Glycosylation）： 糖基化是IgG重链上最常见的翻译后修饰，通常发生在恒定区（CH）的某些特定位点。这会增加分子的总体质量。
- 磷酸化（Phosphorylation）： 磷酸化可以改变蛋白质的质量和电荷特性。
- 羟基化（Hydroxylation）： 这种修饰也会导致分子质量的变化。

**IgG_heavy_low_mass**则指的是IgG重链的低分子质量状态。这通常表示该重链没有经过或仅经过少量的翻译后修饰。这种低质量状态的重链通常与高质量状态的重链相比，缺少一些修饰，如糖基化。
在某些情况下，IgG重链的低质量状态还可能是由于蛋白质在体外处理过程中发生了降解，或者是样本中存在一些部分缺失的重链片段。

1. de novo（意为“从头开始”）在蛋白质研究中有两种常见的应用：
- de novo蛋白质设计：指从头设计全新的蛋白质结构，而不是基于已有的天然蛋白质。这通常涉及计算机辅助设计和合成生物学，以创建具有特定功能的新蛋白质。
- de novo测序：指没有参考序列的情况下，通过质谱技术直接从实验数据中推导出蛋白质或多肽的序列。这对于未知蛋白质的研究尤为重要。
2. Assemble 在蛋白质研究中通常指的是将短的DNA或RNA序列片段拼接成完整序列的过程，这个过程在基因组学和转录组学研究中尤为关键。常见的组装方法包括：
- 基于重叠的片段组装（Overlap-Layout-Consensus, OLC）：用于长读长测序数据，通过识别片段之间的重叠区域进行组装。
- de Bruijn图组装：用于短读长测序数据，通过构建k-mer图进行组装。
在蛋白质组学中，组装通常涉及将短的肽段组装成完整的蛋白质序列。这可以帮助研究人员识别蛋白质的结构和功能。

3. BLAST (Basic Local Alignment Search Tool)是一种用于比较生物序列信息的算法。它可以快速找到与输入序列（例如DNA、RNA或蛋白质）相似的序列。BLAST在蛋白质研究中的应用包括：
- 同源蛋白质的识别：通过BLAST搜索，可以找到与目标蛋白质相似的已知蛋白质，从而推测其功能。
- 功能预测：通过比对新发现的蛋白质序列与数据库中的已知序列，可以预测其潜在功能。
- 进化分析：通过比较不同物种之间的蛋白质序列，可以研究蛋白质的进化关系。

基于排序的假设检验（Rank-Based Hypothesis Testing），也称为非参数假设检验，是一种不依赖于数据分布形式的统计检验方法。与传统的参数假设检验不同，基于排序的假设检验不需要数据服从某种特定的分布（例如正态分布），因此在处理非正态分布的数据时更加灵活和稳健。


