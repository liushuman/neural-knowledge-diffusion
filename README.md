# Neural-Knowledge-Diffusion

A database of the *Knowledge Diffusion for Neural Dialogue Generation*.

The files are in json and the encoding format is UTF8.

## kb.experiment

KB for movies and celebrities

### movie attributes

`--id` : unique ID for each movie

`--title` : title of the movie

`--director` : a list of celebrityIDs who direct the movie

`--actor` : a list of celebrityIDs who act the movie

`--duration` : movie duration in minutes

`--release_time` : movie release year

`--comments` : a list of 5 comments on the movie

### celebrity attributes

`--id` : unique ID for each celebrity

`--name` : name of the celebrity

## data.experiment

Conversations grounded on knowledge base

### sentence attributes

`--raw_sentence` : raw utterance

`--movie` : a list of movie and corresponding movieID appear in raw_sentence

`--celebrity` : a list of celebrity and corresponding celebrityID appear in raw_sentence

`--triple` : a list of facts(subjectID, relation, objectID) for factoid conversations

# Citation
We appreciate your citation if you find our dataset is beneficial.

@inproceedings{liu2018NKD,
  title={Knowledge Diffusion for Neural Dialogue Generation},
  author={Liu, Shuman and Chen, Hongshen and Ren, Zhaochun and Feng, Yang and Liu, Qun and Yin, Dawei},
  booktitle={Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics(Volume 1: Long Papers)},
  pages={1489--1498},
  year={2018},
  publisher = {Association for Computational Linguistics},
}
