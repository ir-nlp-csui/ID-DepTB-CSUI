# d2d-converter
The Head-directionality Converter for Indonesian Dependency Treebank

## The d2d converter


## The CSUI Dependency Treebank

The CSUI treebank is a conversion from an Indonesian constituency treebank in the Penn Treebank format named [**Kethu**](https://github.com/ialfina/kethu) that was also a conversion from a constituency treebank built by [**Dinakaramani et al. (2015)**](https://github.com/famrashel/idn-treebank). 
We named this treebank **CSUI**, since all the three versions of the treebanks were built at Faculty of Computer Science, Universitas Indonesia.

Other characteristics of the treebank:
* This treebank consists of 1030 sentences and 28,263 words.
* The genre of the sentences are mainly news in formal Indonesian. 
* Average sentence length is around 27.4 words per-sentence, which is very high compare to the [Indonesian-PUD](https://github.com/UniversalDependencies/UD_Indonesian-PUD) treebank that has average sentence length of 19.4.


### The Split
We provide two splits of the CSUI Dependency Treebank:
* Split-105-925, that was used on the experiment on a paper that described how the treebank was constructed (Alfina et a., 2020). This split consists of two dataset:
  * csui-test-105, the gold standard that manually annotated
  * csui-train-925, the training dataset that automatically converted 
  
* Split-400-630, thas was published in UD website with name [UI Indonesian CSUI](https://github.com/UniversalDependencies/UD_Indonesian-CSUI)



## Acknowledgments

* The original constituency treebank was built with manual annotation by [Arawinda Dinakaramani, Fam Rashel, Andry Luthfi, and Ruli Manurung](https://github.com/famrashel/idn-treebank) at Faculty of Computer Science, Universitas Indonesia in 2015.
* The previous treebank was converted to the Penn Treebank format by Ika Alfina and Jessica Naraiswari Arwidarasti at Faculty of Computer Science, Universitas Indonesia in 2019. This PTB version was named [**Kethu**](https://github.com/ialfina/kethu).
* The Kethu treebank was converted to a UD treebank by Ika Alfina and Jessica Naraiswari Arwidarasti in 2020.

## References
* Ika Alfina, Indra Budi, and Heru Suhartanto. "**Tree Rotations for Dependency Trees: Converting the Head-Directionality of Noun Phrases**". In Journal of Computer Science (_accepted_)
* Jessica Naraiswari Arwidarasti, Ika Alfina, and Adila Alfa Krisnadhi. ["**Converting an Indonesian Constituency Treebank to the Penn Treebank Format**"](https://ieeexplore.ieee.org/abstract/document/9037723). In the Proceeding of The 2019 International Conference of Asian Language Processing (IALP 2019) in Shanghai, China, 15-17 November 2019. 


## Changelog

2020-10-15 v1.0
* Initial release 

