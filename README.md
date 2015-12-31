# pysplit
similar to UNIX split command except:
- keeps the suffix
- can keep header line for each smaller file
- more flexible

Some benchmark showing that this python version is:
- small files (<20GB): as fast or faster than UNIX split command
- big files (>50GB)  : slower than UNIX split command

potential improvements:
- Ability to split zipped files (this function was removed after several revision as I never need it).

Acknowledgement
The original split.py was from: https://github.com/StanfordBioinformatics/HugeSeq.git
