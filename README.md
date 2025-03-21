# WordSquares
A simple C++ solver for dense word grids. BUT BETTER :P

##Forked from codeparade this is a readable wordsquares developed with help from chat gpt (i dont know much c++). After around 30 minutes of figuring out how to use MinGW, its done

###how to use:
i added (well chat gpt) 1 useable variable, BOXES_PER_ROW (g_box_count is for memory), on my monitor I was able to fit around 27 boxes per row in a fullscreen command prompt after just 3 changes.
i commented all of my changes and did not remove any code (just commented it out), in releases there will be my testing folder with all of the files needed.
if u have trouble dont be scared to ask chatgpt ;0
#eee

See this [YouTube Video](https://youtu.be/zWIsnrxL-Zc) for the best explanation.

**NOTE:** This repository is not actively maintained and is for reference only.

## Usage
To use this solver, you'll need a list of valid words and a word frequency list. If you'd like to use the same files as shown in the video, download links are provided below.

[Scrabble Words List](https://raw.githubusercontent.com/andrewchen3019/wordle/refs/heads/main/Collins%20Scrabble%20Words%20(2019).txt)

[NGram Viewer Frequencies](https://www.kaggle.com/datasets/wheelercode/dictionary-word-frequency)

You'll need to update the `DICTIONARY` and `FREQ_FILTER` paths to reference these files. These and other parameters are found on the top of `main.cpp`. Modify these to try different kinds of word grids. Basic documentation is provided in this file.
