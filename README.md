# hse_hw3_chromhmm
Collab: https://colab.research.google.com/drive/1G0dPLHE_9F6vh0arDS0pOP_H-mojMxvH?usp=sharing

файл | имя
---|---
wgEncodeBroadHistoneH1hescH2azStdAlnRep1.bam | H2AFZ
wgEncodeBroadHistoneH1hescH3k27acStdAlnRep1.bam | H3K27ac
wgEncodeBroadHistoneH1hescH3k27me3StdAlnRep1.bam | H3K27me3
wgEncodeBroadHistoneH1hescH3k36me3StdAlnRep1.bam | H3K36me3
wgEncodeBroadHistoneH1hescH3k4me1StdAlnRep1.bam | H3K4me1
wgEncodeBroadHistoneH1hescH3k4me3StdAlnRep1.bam | H3K4me3
wgEncodeBroadHistoneH1hescH3k79me2StdAlnRep1.bam | H3K79me2
wgEncodeBroadHistoneH1hescH3k9acStdAlnRep1.bam | H3K9ac
wgEncodeBroadHistoneH1hescH3k09me3StdAlnRep1.bam | H3K9me3
wgEncodeBroadHistoneH1hescH4k20me1StdAlnRep1.bam | H4K20me1

emission | overlap 
---|---
![emissions_10](https://user-images.githubusercontent.com/103137801/230792911-fcf6812a-8a7e-4373-a292-7d326e4af139.png) | ![H1_10_overlap](https://user-images.githubusercontent.com/103137801/230792921-17275109-b657-4d90-9d9c-12a84fd68523.png) 

 neiborhood1 | neiborhood2 | transition
---|---|---
![H1_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/103137801/230792934-f92f1b17-c978-4dbd-9bdf-29f92fb8256c.png) | ![H1_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/103137801/230793029-76296a70-2641-43a9-82af-15fa51f30241.png) | ![transitions_10](https://user-images.githubusercontent.com/103137801/230793038-2cf3457a-f9db-4b7b-9ff0-8570a8fd236e.png)


Номер | Имя | Гистонные модификации | Расположение | Пример
---|---|---|---|---
1|  |  H3K9ac, H3K4me3 | CpG островки, экзоны |
2|  |  H3K9ac, H3K4me3, H3K79me2 | ген (иногда в экзонах) |
3|  |  H3K79me2 | ген |
4|  | - | ген |
5|  |  H3K36me3 | экзоны (без CpG островков) и гены |
6|  |  H3K9me3 | ядерная ламина (не попадает на гены) |
7|  | - | ядерная ламина (не попадает на гены) |
8|  |  H2AFZ | ядерная ламина (не попадает на гены) |
9|  |  H3K4me1 | разное чаще всего ген |
10|  |  H3K27me3 | разное чаще не ген |
