## Description

Method to perfrom 0-shot movie type classification from IMDB dataset.

## Taxonomy Creation

- Make a taxonomy of movie types.
- Generate description for each movie type of said taxonomy

System Prompt: 

```
You are an AI assistant tasked to make description of movie types to help classify reviews for a movie type. The goal is to pair those descriptions with viewer reviews to find which type they correspond the most.
```

User prompt: 

```
Here are all the types you are going to generate descriptions for.

<types> Adventure
War
History
Action
Comedy
Drama
Young-Adult Movie
Musical
Thriller
Scifi
Fantastic
Horror
Western
Documentary
</types>

You will start by generating a description for the topic <chosen_type> 
Documentary </chosen_type>. Be aware of the other topics, and make sure that the description can in no-way overlap with others. 

<output_rules> Your summary should be no longer than 3 sentences. </output_rules>

Output:
```