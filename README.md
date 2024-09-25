# SPSS
First you need to install OpenPrompt. see https://github.com/thunlp/OpenPrompt
Then, Adjust all target domain data pseudo-label and voted invariant label.

Final, Average the experimental results three times.

Note that the file paths should be changed according to the running environment.

example shell scripts:

python fewshot.py --result_file ./output_fewshot.txt --dataset newsgroups1 --template_id 0 --seed 140 --shot 20 --verbalizer manual