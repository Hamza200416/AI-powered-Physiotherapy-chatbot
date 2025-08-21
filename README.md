Setup (Colab)

Open the notebook in Colab (click badge above).

First cell will install dependencies:

!pip install sentence-transformers ipywidgets torch pandas --quiet


Enable widgets:

from google.colab import output
output.enable_custom_widget_manager()


Upload your dataset (or create a new one):

from google.colab import files
uploaded = files.upload()

use the main code in the file
# Upload physiotherapy_dataset.csv

🧠 How to Use

Enter Body Part (e.g., "neck")

Enter Severity (e.g., "severe")

Click Get Recommendation

If bot doesn’t know → type exercise in Expert box → Submit ✅

🔧 Fixing Indentation Errors in Colab

Sometimes Colab messes up indentation when pasting large scripts.
If you see IndentationError, do one of these:

Select all code (Ctrl + A) → press Ctrl + ] to auto-indent.

Or paste the code into ChatGPT → ask “fix indentation errors” → paste back into Colab.
