# ESGBERT
A demonstration of using BERT for topic classification.

Currently a single jupyter notebook demonstrating model loading, pretraining, finetuning and inference; this was developed with understandability in mind.

<ins>Strategy overview</ins>: Pretrain Huggingface BERT model architecture (small) on MLM objective (whole-word masking) with domain-specific text. Then trian the encoder with a classifcation head on topic classification

<ins>Datasets available on</ins>: https://huggingface.co/ESGBERT

**Strategy is inpired by this paper:** https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4622514
