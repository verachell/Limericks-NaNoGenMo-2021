# Limericks NaNoGenMo 2021
Generates > 50,000 words of limericks  

These limericks are generated via word substitution (mad-lib style) using [YeetWords](https://github.com/verachell/YeetWords).

## Usage - how to run this program
Please note: This code requires that:   
- ruby is installed on your machine and  
- you have the yeetwords.rb file from the YeetWords repository (see below for where to place it).  

To run this limerick generator, first download the contents of this repository into your working directory. You will also need to download the ```yeetwords.rb``` file from the [YeetWords repository](https://github.com/verachell/YeetWords) (v 1.1.0 or up) and place it at the same directory as ```limericks.txt``` from this repository.

Then in your command line, type ```ruby yeetwords.rb limericks.txt```

A file of limericks of > 50,000 words in markdown format will be generated. You will not prompted for anything except for the output filename if a file with the default name already exists.

## Features
- Within one limerick, a character's name and job remains constant. Not all line template choices will refer to the character's name and/or job, so it is possible that this consistency is not visible in many of the limericks. However, the ability to generate characters is a feature of YeetWords which is used in a sutble way in this program.

## Limitations
- Some of the words do not rhyme well, even if the spelling of the word endings are similar (e.g. automobile and prehensile). This is due to the source of the rhymes, which are from another repository of mine where they were obtained via the spelling of the end of the words; see sources of words and templates below for details.  

- No attention is paid to number of syllables although the templates aim for an approximate number of correct syllables on average. For example, if all longer words happen to be substituted in a line then the line will have too many syllables for a limerick. Conversely if all short words are substituted then the line will have too few syllables. Therefore many of the limericks in this work will not have the correct number of syllables.

## Credits: sources of words and templates
### Template lines
I made up options for the various templates myself for each the lines of a limerick, and these are located in the ```sentences``` folder. Lines 3 and 4 are considered interchangeable and therefore select from the same choices of template. Each line may choose from 5 different options for that line so there is a bit of variety, and each line has several choices of word substitution within one line. 

### Words
- Rhyming words came from the repository [Rhyming Words Mostly](https://github.com/verachell/Rhyming-Words-Mostly); as described above they are not guaranteed to rhyme but many do.  

- Verbs, adjectives, prepositions, conjunctions, adverbs, and plural nouns came from the repository [English word lists parts of speech approximage](https://github.com/verachell/English-word-lists-parts-of-speech-approximate)  

- Emotions, portable nouns, and occupations came from the repository [English word lists miscellaneous categories](https://github.com/verachell/English-word-lists-miscellaneous-categories)

- Male and female names came from the list of most popular baby names in the US for the year 2019 at https://www.ssa.gov/OACT/babynames/index.html. The 200 most popular names for male and for female names were used in this project.
