# Yesus-Lyric-Gen
An NLP project using NLTK that generates Kanye west verses using a corpus 364 verses from 243 songs

This project was a fun look into Natural Language Processing techniques. 
I built a simple word generator that produces original verses based on a selection of Kanye West Verses. 

This project was interesting in that I was able to find out a lot of cool details about ye’s music. First of all, besides a useless word like “that’s”, “nigga” is Kanye’s favorite word, or second most frequent word.

I then dug into the n-grams a bit more. For three word pairings Kanye sounds a little narcissistic.
![3-grams](https://i.imgur.com/pLWzE6t.png)
“I got a” , “I know that”, and “I have a” are used 15 times in his songs.  Interestingly enough Kanye uses “piss in your…” 13 times in 243 songs. This also counts all uses of an n-gram including when it’s used multiple times in one song. This is a factor that skews the meaning of this frequency as some of his songs tend to be repetitive like Blood on the Leaves or I love it. 

Kanye uses the 4-word ngram “Way I wanted to”, “I’m not loving you”, and  “piss on your grave” a total of 8 times in his verses.
![4-grams](https://i.imgur.com/czsVJUO.png)

Verse Generation:
I was able to generate some interesting verses from his past lyrics. 

![mostfly](https://i.imgur.com/ijgVGoG.png)
![redbull](https://i.imgur.com/1xPwzue.png)

I was also able to create a verse starting with a particular word or phrase. In this case I chose Donald Trump.
After all of ye's shennanigans as a "Trump supporter" I thought this was interesting based on his past lyrics.
![trump](https://i.imgur.com/H9LOhPm.png)
