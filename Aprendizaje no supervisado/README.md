En 2022, hubo 420,368 nuevos casos de cáncer de endometrio, de acuerdo con World Cancer Research Fund (2025).




El cáncer de endometrio es el cuarto más común entre las mujeres en los Estados Unidos, según American Cancer Society (s.f.).


Debido al impacto de este tipo de cáncer en la población femenina y que aún no se puede explicar completamente la causa de éste, resulta importante explorar los casos ya existentes para poder encontrar patrones o posibles causas de esta problemática. Por lo tanto, este proyecto tiene como objetivo identificar posibles agrupaciones basadas en la expresión genética y posteriormente interpretar estos grupos de variables clínicas con el fin de aportar evidencia que ayude a explicar la variabilidad presente en el cáncer de endometrio.


En este proyecto se analizaron datos de expresión genética utilizando técnicas de reducción de dimensionalidad y aprendizaje no supervisado para explorar la estructura de los datos e identificar posibles subgrupos de muestras.


Se aplicó PCA para reducir la dimensionalidad de los datos. Posteriormente se seleccionó el método de k-means clustering, identificando 3 clusters principales. Finalmente los clusters obtenidos se compararon con variables clínicas provenientes de TCGA para evaluar asociaciones biológicas o clínicas. 


Los datos fueron obtenidos de [UCSC Xena](https://xenabrowser.net/datapages/), usando los datos tipo STAR - TPM y el archivo de Gene Mapping. 


La base de datos cuenta con 586 pacientes y 60,660 genes. 


Este proyecto incluye los siguientes documentos:
- [Reporte en formato ipynb](./P%20P3.%20623201.ipynb)
- [Reporte en formato html](./P%20P3.%20623201.html)
- [Base de datos STAR - TPM]([./TCGA-UCEC.clinical.tsv](https://xenabrowser.net/datapages/?dataset=TCGA-UCEC.star_tpm.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443))
- [Base de datos Gene Mapping]([./TCGA-UCEC.star_tpm.tsv](https://xenabrowser.net/datapages/?dataset=TCGA-UCEC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443))





