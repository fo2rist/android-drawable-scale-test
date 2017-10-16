# android-drawable-scale-test
Test how Android scales drawables for different resolutions

Project contains same simple pattern with 1px and 2px lines in different folders (mdpi, hdpi, etc.)
and simple activity that shows all the images alongside to show the difference in shrinking alogorithm for transformations
MDPI->LDPI, HDPI->MDPI etc.
Artefacts caused by transformations 2->1 and 4->1 (e.g. XHPI->MDPI, XXXDPI->MDPI) also higligted:

![4->1 artefact example](https://habrastorage.org/webt/59/e4/3a/59e43afce02df818564783.png)
![2->1 artefact example](https://habrastorage.org/webt/59/e4/3a/59e43afbe808b694459961.png)
