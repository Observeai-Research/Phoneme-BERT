# Phoneme-BERT ([Accepted to Interspeech 2021, Czechia](https://www.interspeech2021.org/))

Repository for data used for PhonemeBERT.

* `sample_data` contains sample dataset for all downstream tasks utilized in the work

* `phomeme-bert-data` contains the data used to train and evaluate the models as reported in the paper


Folder Structure

* [`pre-training`](phomeme-bert-data/pre-training): contains train, test and valid datasets for pre-training the model on ASR corpus

* [`downstream-datasets`](phomeme-bert-data/downstream-datasets): contains train, test and valid datasets for downstream tasks: SST, TREC-50, TREC-6 and ATIS

* Each of the zipped folder contains four parallel files for each of train, test and valid splits:
	* `en.classification.txt` - contains ASR transcript of the speech version of original texts
	* `labels.classification.txt` - contains class labels
	* `ph.classification.txt` - contains phoneme transcript
	* `text_original.txt` - contains original text



If you use the provided dataset, please cite our paper as:

```
	@article{sundararaman2021phoneme,
	  title={Phoneme-BERT: Joint Language Modelling of Phoneme Sequence and ASR Transcript},
	  author={Sundararaman, Mukuntha Narayanan and Kumar, Ayush and Vepa, Jithendra},
	  journal={arXiv preprint arXiv:2102.00804},
	  year={2021}
	}
```


