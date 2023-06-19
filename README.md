# LLMsForSheets_Frontend

Backend code: https://github.com/SarthakS97/LLMsForSheets_Backend

Please follow the video for instructions: https://youtu.be/FiB1hx5IDsY

## Instructions

- In the Google Sheet find Extensions and click on it to find Apps Script. Open a new Apps Script file and name it LLM.
- Paste the code from code.gs.txt from this repo.
- Create a new html file and name it sidebar.html. Paste the code from sidebar.html in this repo.
- Save and run. You should see LLM under Extenions back in google sheets
- Click on LLM and click configure. Paste your Replicate API key in the textbox and hit save. 

That's it! You can now use Dolly, Vicuna and Open Assistant in your sheet. 

## Use the following formula in the cell you want the output in
- Dolly: =dolly({prompt})
- Vicuna: =vicuna({prompt})
- Open Assistant: =open({prompt})

## When you use the formulas for the first time you'll get a timeout error. To avoid this run the models in Replicate.com first and then use the formulas
