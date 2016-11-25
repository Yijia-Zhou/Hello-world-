# notes about using CLEM to measure yeast prion

## From *In vivo evidence for the fibrillar structures of Sup35 prions in yeast cells*

### Introduction

##### Amyloids in general

- highly ordered fibrillar protein aggregates with a cross β-sheet structure
- binds Congo red and thioflavin dyes
- some aggregates with **nonpathological** origins

##### Sup35 - Representative examples of such nonpathological amyloid formation

- normally functions as a **translation termination factor**
- aggregated forms in [*PSI+*]
- Hsp104, a **chaperone** which disassembles protein aggregates in an ATP-dependent manner with the aid of the Hsp70/40 system
- Sup35 fused with GFP gives rise to the formation of visible spherical aggregates, called **foci**, in the cytosol
- Besides, rod- or ring-shaped aggregates may also be formed when Sup35NM-GFP is overexpressed in *[psi−] cells* and in *[PSI+] cells treated with 3–5 mM guanidine hydrochloride* (cure [*PSI+*] by perturbing Hsp104)

##### foci

- not dead-end complexes - can be dispersed throughout the cytoplasm as diffuse oligomers
- formed by the **N-terminal** (N) and **middle (M) domains** of Sup35 fused with GFP (**Sup35NM-GFP**)

##### 过往观察

In Vitro:

> recombinant Sup35 proteins bearing the prion-determining N-terminal domain form fibrils with a diameter of ∼10–20 nm ([Glover et al., 1997](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib10); [Kishimoto et al., 2004](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib17); [Krzewska and Melki, 2006](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib20))

suggested the existence of amyloid fibrils in vivo:

1. Sup35 aggregates in [*PSI+*] cells are **stained by an amyloid-staining dye**, thioflavin S, suggesting the presence of cross β-sheet structures in [*PSI+*] cells ([Kimura et al., 2003](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib16)). 
2. an EM analysis of Sup35 oligomers **isolated** from [*PSI+*] lysates revealed ∼20-nm-wide barrels and larger structures (bundles; [Bagriantsev et al., 2008](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib3)). 
3. the induction of the **[*PSI+*] phenotype** by the **expression** of recombinant Sup35 implied that [*PSI+*] cells contained amyloid fibrils originating from Sup35 ([Tanaka et al., 2004](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2930275/#bib33)).（因为过表达Sup35可以诱导prion表型[*PSI+*]说明[*PSI+*]细胞内有聚集成淀粉状的Sup35？）

So far there is no **direct** evidence, and the **detailed structure** is not known.



### Results:

[PSI+] cells里的沉积物主要有两种形态，圆的（点状/球形的，**spherical aggregates** / **Dotlike aggregates**）和杆状(**rodlike aggregates**)的。其中正常情况下出现的的圆的。

**Fig. 1**是直接用rapid-freeze EM做的，A-F是各种形态的spherical aggregates, G, H, I 用target GFP的免疫电镜证明这些东西确实含Sup35(GFP是和Sup35融合的).

观察spherical aggregates的同时也发现会有一些束状、平行排列、非常整齐的纤维结构。



**Fig. 2**上了CLEM, 荧光显微镜下找到GFP的绿斑(A左)，超薄切片放电镜看(A右, B)发现跟rapid freeze EM底下看到的结构基本一样。做个傅里叶变换(C)发现里面有很多纤维结构。



**Fig. 3** 观察的是Rodlike aggregates in GuHCl-treated [*PSI+*] cells. GuHCl是Hsp104的抑制剂，而Hsp104可以切开Sup35形成的纤维，因此加GuHCl可以让Sup35堆积得更狠。

观察手段还是老一套，CLEM和rapid-freeze EM, 最后来个免疫电镜确认。只不过这回观察到的都是长条形的。

为了搞清楚rodlike是怎么形成的，垂直于杆的轴做连续切片，然后用CLEM观察(**Fig. 4**) 得到3D结构，发现杆的截面是个蜂窝状结构，而蜂窝状结构很可能是由纤维平行排列形成的。（与Fig. 1中的有dot也有纤维状结构的结果相吻合。）



之前已经证明aggregates是动态的结构，不停地有Sup35 oligomers(寡聚体)附着和脱落，于是想知道游离的oligomers长啥样，

1. 用半变性电泳（不加GuHCl）测了分子量，
2. 用FCS(荧光相关光谱，以前看过一下没看懂啥意思……)测了扩散常数，
3. 发现扩散长度要比假设其是球形算出来的理论值低得多，而假设它是纤维状的则可以解释，并算出其长度/直径比值大概在65左右（用了一个叫Perrin factor的奇怪数值）。

而加GuHCl的情况下，

1. 分子量普遍大了很多（没有Hsp104切了）
2. 长度/直径比值却基本没变

那么唯一的解释就是Hsp104的缺失不仅会使Sup35形成的纤维变短，也会使它变细，并且基本是相同比例的。

(**Fig. 5**基本就是这一堆数据画出来的图)