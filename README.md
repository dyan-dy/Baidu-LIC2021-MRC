# Baidu-LIC2021-MRC
models and codes for baiduAI LIC 2021 MRC tasks, based on paddlenlp

# usage
Modified the [baseline](https://github.com/PaddlePaddle/Research/tree/master/NLP/DuReader-Checklist-BASELINE) from paddlenlp.

Due to the poor push speed and the limitation of fold volume, dataset and model .pdparams are not pushed.

`download.sh` , downloading the dataset.
`train.sh`, train the model.
`run_eval.sh`, evaluation for the dev dataset.
`prediction.sh`, generate the demanding result.

# Final Result
| Rank | F1 |	EM	| in-domain(F1)	| checklist(F1)	| vocab(F1)	| phrase(F1)	| semantic-role(F1)	| fault-tolerant(F1) |	reasoning(F1) | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |  
| 68 | 54.863	| 46.596 | 62.747 |	47.972	| 50.658	| 55.706	| 44.278 | 47.15	| 42.068 |


# Test1 Result
| Rank | F1 |	EM	| in-domain(F1)	| checklist(F1)	| vocab(F1)	| phrase(F1)	| semantic-role(F1)	| fault-tolerant(F1) |	reasoning(F1) | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |  
| 85 | 58.89	| 48.774 | 66.659 |	52.6436	| 53.195	| 61.625	| 55.01 | 44.996	| 48.392 |

# Pretrained model with different weights' performance(F1) based on "[checklist](https://aclanthology.org/2020.acl-main.442.pdf)" and [baseline](https://github.com/PaddlePaddle/Research/tree/master/NLP/DuReader-Checklist-BASELINE)
![image](https://user-images.githubusercontent.com/53289454/136005024-df48577f-6fed-4af5-a6a7-e93168bc5aff.png)

