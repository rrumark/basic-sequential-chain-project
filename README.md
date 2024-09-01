# basic-sequential-chain-project
![image](https://github.com/user-attachments/assets/847aee44-bb0f-416b-9a15-f766a1556588)

Project: Basic Sequential Chain
Notebook: "basic-sequential-chain-project.ipynb"

This project illustrates how to build a basic sequential chain using LangChain. It integrates two interconnected chains:

Genre Recommender: Suggests related movie genres based on the user’s preferred genre.
Movie Recommender: Provides movie recommendations derived from the suggested genres.

Key Components:
AzureChatOpenAI: Leverages Azure's OpenAI API for the language model operations.
PromptTemplate: Configures the prompts used by the language model.
SimpleSequentialChain: Connects the two chains, ensuring a smooth flow from genre recommendation to movie selection.

"plaintext"
> Favorite movie genre: War
Output:
> Initiating new BasicSequentialChain...
1. Historical Drama - "Braveheart"
2. Action - "Saving Private Ryan"
3. Thriller - "Zero Dark Thirty"
> Chain completed.

