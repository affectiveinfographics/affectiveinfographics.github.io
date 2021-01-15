# Smile or Scowl? Looking at Infographic Design Through the Affective Lens
This respository contains the corpus we collected and the study data generated from our crowdsourcing study.

## (1) corpus.csv
- the list of the 976 infographics manually collected from [information is beautiful award](https://www.informationisbeautifulawards.com/showcase?award=2019&type=awards) and [visual.ly](https://visual.ly/view#feature_type=undefined&type=static&).
- fields: "title", "source", "author/publisher", "corpus_id", "link".

## (2) corpus folder
- 976 images

## (2) study_data.json
- contains the data we collected from a crowdsourcing study, organized into a json structure.
- there are 976 objects (i.e., the 976 infographics) in this dict
- each infographic has 17 attributes, including "title", "link", "primary_affect", "primary_affect_mean", the mean scores of the 12 affects respectively ("happy_mean", "surprised_mean", etc.), and the raw "ratings".
- the raw "ratings" are objects that contain 10 users' ratings. For each of the 10 users, we privide his/her "gender", "age", and the "scores" he/she set to the 12 affects (5-point Likert scale). If the user set a score above 1 to the infographic (in our study, 1 denotes "not at all aware" of an affect, while 5 denotes "strongly aware" of an affect), we thought he/she had experienced that affect more or less and include the affect as "experienced".

{"pic1": 
    {"title": "100 Days of Summer - Plants in Finland", 
    "source": "https://www.informationisbeautifulawards.com/showcase/2389-100-days-of-summer-plants-in-finland", 
    "primary_emotion": "overwhelmed", 
    "primary_emotion_mean": 2.7, 
    "happy_mean": 2.5, 
    "surprised_mean": 2.3, 
    "excited_mean": 1.8, 
    "content_mean": 2.1, 
    "awestruck_mean": 1.7, 
    "hopeful_mean": 1.9, 
    "sad_mean": 1.0,
    "bored_mean": 1.2, 
    "concerned_mean": 1.0, 
    "overwhelmed_mean": 2.7, 
    "shocked_mean": 1.1, 
    "annoyed_mean": 1.3, 
    "ratings": 
        {"user10": {"age": "52", 
                   "gender": "female", 
                   "label": ["overwhelmed"], 
                   "score":
                        {"happy": 1, 
                         "overwhelmed": 5, 
                         "shocked": 1, 
                         "annoyed": 1, 
                         "surprised": 1, 
                         "excited": 1, 
                         "content": 1, 
                         "awestruck": 1, 
                         "hopeful": 1, 
                         "sad": 1, 
                         "bored": 1, 
                         "concerned": 1
                        }
                   },
         "user9": {...},
         "user8": {...},
         "user7": {...},
         "user6": {...},
         "user5": {...},
         "user4": {...},
         "user3": {...},
         "user2": {...},
         "user1": {...},
        }
   }
}

You can click the "code" button above to download these materials as a zip :)

