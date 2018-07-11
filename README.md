# neural-knowledge-diffusion

## kb.experiment
knowledge base for movies and celebrities
### movie attributes
--id: unique ID for each movie
--title: title of the movie
--director: a list of celebrity IDs who direct the movie
--actor: a list of celebrity IDs who act the movie
--duration: movie duration
--release_time: movie release time
--comments: a list of 5 comments on the movie
### celebrity attributes
--id: unique ID for each celebrity
--name: name of the celebrity

## data.experiment
conversations grounded on knowledge base
### sentence attributes
--raw_sentence: raw utterance
--movie: a list of movie and corresponding movie id appear in raw_sentence
--celebrity: a list of celebrity and corresponding celebrity id appear in raw_sentence
--triple: a list of facts(subjectID, relation, objectID) for factoid conversations
