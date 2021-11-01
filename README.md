# Limericks-NaNoGenMo-2021
Generates > 50,000 words of limericks  

These limericks are generated via word substitution (mad-lib style) using YeetWords.

## How to run this program
Please note: This code requires that:   
- ruby is installed on your machine and  
- you have the yeetwords.rb file from YeetWords (see below for where to place it).  

To run this limerick generator, first download the contents of this repository into your working directory. You will also need to download the ```yeetwords.rb``` file from the YeetWords repository (v 1.1.0 or up) and place it at the same directory as ```limericks.txt``` from this repository.

Then in your command line, type ```ruby yeetwords.rb limericks.txt```

A file of limericks of > 50,000 words in markdown format will be generated. You will not prompted for anything except for the output filename if a file with the default name already exists.

## Features
- Within one limerick, a character's name and job remains constant. Not all line template choices will refer to the character's name and/or job, so it is possible that this consistency is not visible in many of the limericks. However, the ability to generate characters is a feature of YeetWords which is used in a sutble way in this program.

## Limitations
- Some of the words do not rhyme well, even if the spelling of the word endings are similar (e.g. automobile and prehensile). This is due to the source of the rhymes, which are from another repository of mine where they were obtained via the spelling of the end of the words; see section below for details.  

- No attention is paid to number of syllables although the templates aim for an approximate number of correct syllables on average. For example, if all longer words happen to be substituted in a line then the line will have too many syllables for a limerick. Conversely if all short words are substituted then the line will have too few syllables. Therefore many of the limericks in this work will not have the correct number of syllables.

## Sources of words and templates
I made up options for the various templates myself for each the lines of a limerick, and these are located in the ```sentences``` folder. Lines 3 and 4 are considered interchangeable and therefore select from the same choices of template. Each line may choose from 5 different options for that line so there is some variety, and each line has several choices of word substitution within one line.

