# Data analysis
- Document here the project: music_similarity
- Description: Project aimed to find similarity between songs
- Data Source: Spotify API
- Type of analysis: K-NN Recommender


# Medium article

[Read more here](https://medium.com/@griggio.federico/discover-new-songs-with-music-similarity-c650ca5f5bea)


# Our webapp

[Try the webapp here](https://music-similarity-anffoy276a-uc.a.run.app/)


# Install

Clone the project and install it:

```bash
git clone git@github.com:{group}/music_similarity.git
cd music_similarity
pip install -r requirements.txt
make clean install test                # install and test
```
Functionnal test with a script:

```bash
cd
mkdir tmp
cd tmp
music_similarity-run
```
