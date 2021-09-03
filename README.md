# NewBottleSum

Code for Natural Language Understanding Course Project by Qucheng Peng, Qiyu Xiao and Kai Liao at New York University.




#### Compatibility:
```
pytorch 0.4 
pytorch-pretrained-bert
sacremoses
nltk
tqdm
```

#### Temporary code instructions:

Note: We are still working on improving this codes' implementation.

To run bottleSumEx with the same settings as ours:

```
python bottleEx_summarize.py -S1_path <S1FILE> -S2_path <S2FILE> -S3_path <S3FILE> -rem_words 3 -out_name <OUTNAME>
```
S1FILE contains the original sentences. S2FILE contains the next sentences of the original ones. S3FILE includes the title of the original sentences' corresponding text.

#### Acknowledge：

Borrow a lot from https://github.com/peterwestuw/BottleSum.git.
Thanks so much for Mr. Peter West at University of Washington, our Professor Samuel Bowman and all the TAs of this course.
