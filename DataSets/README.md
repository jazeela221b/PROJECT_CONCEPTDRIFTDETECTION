# Streaming data sets

This repository contains a collection of datasets. While some data sets are used for batch learning they can be also be used in the streaming setting. On the other hand, some data sets have characteristics that make them better suited for the stream learning setting, e.g., they contain non-stationary data.

* **Agrawal-abrupt and Agrawal-gradual** (agr_a.csv, agr_g)

  *Type: Binary classification*
  
  Based on the Agrawal generator, represent a data stream with six nominal and three numerical features. Different functions map instances into two different classes. Three abrupt drifts are simulated for `AGRa` and three gradual drifts for `AGRg`.
  > Heitor Murilo Gomes, Albert Bifet, Jesse Read, Jean Paul Barddal, Fabricio Enembreck, Bernhard Pfharinger, Geoff Holmes, Talel Abdessalem. Adaptive random forests for evolving data stream classification. In Machine Learning, DOI: 10.1007/s10994-017-5642-8, Springer, 2017.

* **Airlines** (airlines.csv)

  *Type: Binary classification*
  
  Real world data containing information from scheduled departures of commercial flights within the US. The objective is to predict if a flight will be delayed.
  > Heitor Murilo Gomes, Albert Bifet, Jesse Read, Jean Paul Barddal, Fabricio Enembreck, Bernhard Pfharinger, Geoff Holmes, Talel Abdessalem. Adaptive random forests for evolving data stream classification. In Machine Learning, DOI: 10.1007/s10994-017-5642-8, Springer, 2017.

  *Note:* Variation of the [airlines dataset](http://kt.ijs.si/elena_ikonomovska/data.html) from Ikonomovska.


* **Electricity Market** (elec.csv)

  *Type: Binary classification*
  
  Data from the Australian New South Wales electricity market where prices are not fixed but change based on offer and demand. The 2 target classes represent changes in the price (1=up or 0=down).
  > M. Harries, N.S. Wales, Splice-2 comparative evaluation: Electricity pricing, 1999.

  *Notes:* This version does not include the attributes 'date' and 'day'.



* **Music (emotions)** (music.csv)

  *Type: Multi-label classification*
  
  593 songs with 6 clusters of music emotions based on the Tellegen-Watson-Clark model.
  > Read, J., Reutemann, P., Pfahringer, B. and Holmes, G., 2016. Meka: a multi-label/multi-target extension to weka. The Journal of Machine Learning Research, 17(1), pp.667-671.
  
  > K. Trohidis, G. Tsoumakas, G. Kalliris, I. Vlahavas. "Multilabel Classification of Music into Emotions". Proc. 2008 International Conference on Music Information Retrieval (ISMIR 2008), pp. 325-330, Philadelphia, PA, USA, 2008.

