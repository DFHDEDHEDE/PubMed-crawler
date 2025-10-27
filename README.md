# PubMed-crawler-3.0
Added support from local AI which can help screen articles. We kept all the functions in PubMed crawler 2.0 while users can choose to use local generative AI model to help analyse the title and abstract of articale to give an screening result which might be better than simply counting keyword frequency.
Here we take deepseek-r1:14b from ollama as an example for it is open source and made our request in Chinese. You may switch to other open source models or online generative AI in different languages. In this example, make sure your ollama application is on before you run the program.
Please note that sometimes AI may give wrong results or simply no response.
If you do not want to use generative AI, answer 'F' when asked if you want to use AI to screen the articles and the results would be calculated just by keyword frequency.
