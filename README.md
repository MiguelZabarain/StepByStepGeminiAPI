# StepByStepGeminiAPI
This project is intended as an ipython notebook with a collection of snippets that can be used to interact with the Gemini API to access all of its capabilities.

It starts by showing the code needed to load the API KEY for Gemini from the .env file, thus avoiding having to publish this type of sensitive information in the code.

It then presents snippets that perform a particular function documented in the Gemini API in each subsequent cell, in a way that is easy to understand and reuse in other projects where it could be useful.

Each cell is independent of the others, so you can execute them in the order you want; however, you must execute the first cell before attempting to execute any other; this is required to have access to the API KEY for Gemini.

Below is the description of the snippets created so far:
1. Loads the Gemini API KEY from the .env file and puts it in the MDLS_API_KEY environment variable.
2. Instantiates the model to generate Text from Text.
3. Instantiates the model to generate Text from Text & local Image.
4. Instantiates the model to initiate a Chat using only Text input.
5. Instantiates the model configuring **max_output_tokens** and **temperature** to generate content using only Text input.
6. Instantiates the model configuring **temperature** and **system_instruction** to generate content using only Text input.
7. Uploads two PDF files to the cloud so the LLM model can have access to them. The process finalize deleting the uploaded files. 
8. Instantiates the model, setting streaming response, for real-time content generation using only Text input.
9. Instantiates the model using safety settings to generate filtered content using only Text input.
10. Instantiates the model to generate Text from Text & web Image.

