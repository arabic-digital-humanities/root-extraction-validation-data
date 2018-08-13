# Dataset for evaluating root extraction

This dataset contains data to evaluate the roots extracted by Arabic
morphological analyzers.

The dataset was created in the context of the Bridging the Gap project.

The `txt` directory contains the text files for which roots were extracted,
and `gs` contains csv files with columns `word` and `root`, containing the words
from the text and the manually corrected roots. If multiple roots apply, they
have been separated using a backslash (`\`). If the word is a letter, the root is `#`.

## To do

* data license
* texts for other use cases
