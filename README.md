
# Summer Work, 2026
Benji Gold/Arthur Spirling summer work, 2026

I have all the intermediate summary documents stored so we can generate additional scores based on those summaries or compare summaries across different models as necssary. 

There are 3 score files currently in the main branch. Deepseek V3.2, gemini 3.5-flash, and gpt 4.1 were used in all 3 files.  Amazon's nova lite 2 V2, claude Haiku 4.5, and gpt 3.5 turbo were used only in file allscores3.csv

The column names first list the model that created the summary and then list the model that scored the summary. For example the column name "EU_gpt_geminiScore" was the summary made by gpt 4.1 for EU issues. The summmary was then scored by gemini. "gpt" is used for gpt 4.1 and "gpt3.5" is used for gpt 3.5.

1. allScores.csv - First cut with the first 20 manifestos in the file. Runs on first 3 models
2. allScores2.csv - Second cut. Uses 30 random manifestos. Runs on first 3 models. Errors are listed for scores where no summary was made. Blanks mean the score was NA for a manifesto summary that did exist.
4. allScores3.csv - Third cut. Uses the same 30 manifestos as allSCores2, but adds an additional 24 manifestos. Right now, scores are available for 4 of the 6 models for summaries created by all 6 models. 

<img width="500" height="250" alt="OpenRouter DiXoyepE" src="https://github.com/user-attachments/assets/c4758da1-519f-43c9-86f5-3a9706983c5e" />
