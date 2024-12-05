# MANGO
This is the repository for the paper Cultural Commonsense Knowledge for Intercultural Dialogues (CIKM 2024).

## Code

- We used the api_request_parallel_processor.py script provided by OpenAI (https://github.com/openai/openai-cookbook/blob/main/examples/api_request_parallel_processor.py) to generate assertions with GPT. Full prompt templates are provided in our earlier manuscript (https://arxiv.org/pdf/2402.10689v1 - see Table 7 in Page 12).
- For clustering, we used this script (https://github.com/UKPLab/sentence-transformers/blob/master/examples/applications/clustering/agglomerative.py) by the SBert authors.

## Released dataset

We release the following data under the CC BY 4.0 license:

- The Mango collection of 167K high-quality cultural commonsense knowledge assertions: [mango_dataset_v1.jsonl.zip](https://www.mpi-inf.mpg.de/fileadmin/inf/d5/research/mango/mango_dataset_v1.jsonl.zip)

You can also browse the dataset at https://mango.mpi-inf.mpg.de/search

## Citation

If you use the dataset in your research, please cite the following paper:

```bib
@inproceedings{mango,
  author = {Nguyen, Tuan-Phong and Razniewski, Simon and Weikum, Gerhard},
  title = {Cultural Commonsense Knowledge for Intercultural Dialogues},
  year = {2024},
  isbn = {9798400704369},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3627673.3679768},
  doi = {10.1145/3627673.3679768},
  booktitle = {Proceedings of the 33rd ACM International Conference on Information and Knowledge Management},
  pages = {1774–1784},
  numpages = {11},
  keywords = {cultural commonsense knowledge, intercultural dialogues, knowledge distillation},
  location = {Boise, ID, USA},
  series = {CIKM '24}
}
```
