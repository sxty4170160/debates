# `debates`: US Presidential Debate Transcripts <img src="man/figures/logo.png" align="right" width=120 />

Presidential debates are an important opportunity for candidates to share their platforms. `debates` provides easy access to debate transcripts from Presidential, Vice Presidential, and primary candidate debates. The current version includes Presidential and Vice-Presidential debate transcripts starting in 1960, and for most debates from the 2012, 2016, and 2020 primary elections. `debates` includes one dataset, transcripts.df, as a compact RData object. Once the package is installed and loaded, the dataset can be loaded using the `data()` function.

transcripts.df includes speaker-level and debate-level data. Each row in transcripts.df represents one statement. Along with the text of the statement, each row includes the speaker's name and an indicator variable that identifies whether or not the speaker is a candidate (as opposed to being a moderator, an announcer, or someone asking a question). Each row also indicates the date, location, and type of debate. To suggest additional fields, please open an issue. 

## Installation

To install `debates`, use the `install_github` function from the `devtools` package:

```
library(devtools)
install_github("jamesmartherus/debates")
```

Alternatively, you can download transcripts.RData directly from the `data` folder. 

## Examples

```
library(debates)

data(transcripts.df) #Load Transcript Data File
```

## Acknowledgments

- Transcripts were gathered from a variety of sources including [Rev.com](https://www.rev.com/blog/transcript-category/debate-transcripts?view=all), [debates.org](https://www.debates.org/voter-education/debate-transcripts/), and a variety of news sites. 


