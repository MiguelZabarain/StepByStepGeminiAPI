# StepByStepGeminiAPI
This project is intended as an ipython notebook with a collection of snippets that can be used to interact with the Gemini API to access all of its capabilities.

It starts by showing the code needed to load the API KEY for Gemini from the .env file, thus avoiding having to publish this type of sensitive information in the code.

It then presents snippets that perform a particular function documented in the Gemini API in each subsequent cell, in a way that is easy to understand and reuse in other projects where it could be useful.

Each cell is independent of the others, so you can execute them in the order you want; however, you must execute the first cell before attempting to execute any other; this is required to have access to the API KEY for Gemini.

Below is the list of snippets created so far:
1. Snippet that loads the Gemini API KEY from the .env file and puts it in the MDLS_API_KEY environment variable.
2. Snippet to generate Text from Text (zero-shot approach).
3. Snippet to generate Text from Text & Image (zero-shot approach).
4. Snippet to initiate a Chat using only Text input (zero-shot approach).
5. Snippet to generate Text from Text passing two config attributes: max_output_tokens and temperature.
6. Snippet to generate Text from Text passing one config attribute and System Instructions.
7. Snippet to generate Text from Text and two PDF documents using the File API that allows using documents up to 2GB in size -and 20GB in total. 
8. Snippet to get streaming response capability for real-time text generation.
9. Snippet to configure content safety settings and thresholds for content filtering.
10. Snippet to get structured JSON responses using chat functionality with explicit formatting.
11. Snippet to generate and compare text embeddings for semantic similarity analysis.

