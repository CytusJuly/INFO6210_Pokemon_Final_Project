# INFO6210_Pokemon_Final_Project
## INFO-6210-FINAL-PROJECT --- POKEMON PROJECT



## This documentation is try to show what's contain in different file in this zip file.

## The domain of this project is Pokemon, we try to set up a Pokemon community database containing Pokemon Game Developers, Gamers and Game contents. We build database on Navigate Premuim 12 and write use cases to prove our database works out.

### In this project, we acquire raw data though 3 social media API: Twitter - Twitter API, Insgram - Instaloader, Reddit - PRAW by using Python 3.7 on Jupyter notebook and normalize our tables then output csv.file. 




##  Report File: 
###  report.doc : It's a report of the whole project, containing output of code and MYSQL queries results.



## Project File: containing several sub files of everthing in projects.
### Code file:

#### reddit.ipynb: This code file shows how to acquire data by using Reddit API -- PRAW. We collect reddiors and their posts from 4 POKEMON Games( PokemonGO, PokemonLet'sGO, Pokemon-SwordAndSheild, DectectivePikachu) belongs to our domain, then we normaliza the raw tables and create 2 new tables: Gamers & Gamers' post.

#### GameCompany_draft.ipynb: This code file shows how to acquire data by using Insgram API -- Instaloader. We collocet posts from 3 different Game company(PokemonGo, DetectivePikachu, Pokemon-SwordAndSheild) INS account and extract hashtag from each posts. After normalization, we output 3 csv.file(Game Company, Game Company Post, Hashtag).

#### Twitter2019(1).ipynb:  This code file shows how to acquire data by using Twitter API. From previous Hashtag.csv file, we select 5 keywords as Game contents and using API to search what people talking about these specific topics.After normalization, we output 3 csv.file(Game Cotent, Game Cotent Post, Hashtag).

#### RelationshipAndCommunity.ipynb : This code file we use data from previous file and creat 2 table ( relationship, community)

#### missspellingwords.ipynb / sysnonmous_word.ipynb : python to answer 2 OF 4 QUESTION.



### Csv file: (Data after normalization): 9 files of different tables



### ER-diagram file: 
#### ER-D.jpg(Before normalization),  
#### ERD.PDF (After normalization)
 
 

### Q1-Q9 Answer file
#### Contain 9 output tables of 9 question in the project requirement.



### T1-T4 file
####  Contain 2 output tables of T1 & T4 and 2 .ipynb file which are the answer of T2 & T3




## Team Member Info:
## Yijin Zhu 001498312
## Yuhang Li 001442226
## Yujin Xiang 001496297

