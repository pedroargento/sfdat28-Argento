**Movie Script analysis**

**Introduction**

Film industry is extremely successful, it generates many billions dollars in revenue each year. But although the industry overall is profitable, many individual movies still fail to break even.

On the other side, an average producer receives about 10000 screenplays a year, most of them are never read by a human being. How many hidden gems were lost? How many Shawshank Redemptions were put aside to give place to Jason in space?

There is great advantages of teaching a computer to read screenplays: Predicting major flukes, filtering and helping prioritize witch scripts should be read by a human being. After the movie has been approved, having a good revenue forecast can lead to better and more realistic decision in budgeting.

**Objective**

The objective of this work is to teach a machine learn algorithm how to read scripts and recognize patterns that leads to success. There are three things to be predicted: How much revenue a movie will make, how it will be rated in IMDB and will it be nominated for an Academy Award.

**Dataset**

The dataset used is a mix of movie scripts scrapped from the Internacional Movie Script Database(IMSDB) and common movie information from IMDB (eg. Actors, Budget, Director, etc))

**Concerns**

As all movies used in the analyses were vetted and aproved by human beens, there is an unavoidable sampling bias and it is impossible to be sure weather results will apply to new scripts.

**Methodology**

It is important to use the least information about the movie as possible, so the model can be used in the early pre production work flow (eg. Before actors are cast).  It would be ideal if the model can achieve a good performance using only the script and information inferred from it, such as the genre.
