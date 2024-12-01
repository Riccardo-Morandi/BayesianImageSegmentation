# BayesianImageSegmentation
 scalable image segmentation applied to brain data.

 This repo contains the code for the project of the Bayesian Statistics course offered at Politecnico di Milano.

## Abstract:
Image segmentation aims at grouping similar pixels of an image under a common class label and can be therefore interpreted as a clustering problem. In this project we use the hidden Potts model, which describes the distribution of pixels in an image via a Bayesian mixture model, while accounting for the spatial dependence between adjacent pixels. The spatial dependence is introduced via hidden Markov random fields – in particular, a Gibbs random field.
We implement a Gibbs sampler for the hidden Potts model capable of dealing with images of arbitrary shape and number of channels.
We fit the model to real brain spectroscopy data, a challenging dataset due to the high dimensionality. Our goal is to integrate multiple molecular spectra to extract meaningful insights – and possibly anomalies – from these real biological images.

For further details please refer to the report.

Part of the project cosisted in the creation of a R library for the multidimensional hidden potts model, which can be downloaded at https://github.com/alfredo-g-zapiola/multiPotts

The content of this project then lead to a publication:

@inproceedings{fe65b2b757614d2d8f93fc702a603819,
   title = "Detecting latent spatial patterns in mass spectrometry brain imaging data via Bayesian mixtures",
   abstract = "Mass spectrometry methods can record biomolecule abundance for a broad set of molec- ular masses given a sample of a specific biological tissue. In particular, the MALDI-MSI technique produces imaging data where, for each pixel, a mass spectrum is recorded. There is the urge to rely on suited statistical methods to model these data, fully addressing their morphological characteristics. Here, we investigate the use of Bayesian mixture models to segment these real biomedical images. We aim to detect groups of pixels that present sim- ilar patterns to extract interesting insights, such as anomalies that one cannot capture from the original pictures. This task is particularly challenging given the high dimensionality of the data and the spatial correlation among pixels. To account for the spatial nature of the dataset, we rely on Hidden Markov Random Fields.",
   keywords = "Mass spectrometry, Brain imaging, Potts model, Bayesian mixture models, Mass spectrometry, Brain imaging, Potts model, Bayesian mixture models",
   author = "G. Capitoli and S. Colombara and A. Cotroneo and {De Caro}, F. and R. Morandi and C. Schembri and Zapiola, {A. G.} and Francesco Denti",
   year = "2023",
   language = "English",
   isbn = "9788891935618AAVV",
   pages = "1127--1132",
   booktitle = "Book of the Short Papers SEAS IN 2023",
   note = "SIS 2023 - Statistical Learning, Sustainability and Impact Evaluation ; Conference date: 21-06-2023 Through 23-06-2023",
}

which is reportes here in the file SIS23.

## Team

- Riccardo Morandi
- Alfredo Zapiola
- Francesco De Caro
- Simone Colombara
- Chiara Schembri
- Alessia Cotroneo

## Credits

This project is under the supervision of proferrsos Francesco Denti (Università Cattolica del Sacro Cuore) and Giulia Capitoli (Università degli studi Milano Bicocca).
