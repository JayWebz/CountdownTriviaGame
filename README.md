# Trivia-Game
A responsive 3-question timed trivia game that runs like a Buzztime trivia game.

Question data sourced from https://opentdb.com/api_config.php.<br/>

API: https://opentdb.com/api.php?amount=3&category=9&type=multiple<br/>

Sample Response:
```
{ 
  results": [
    {
      "category": "General Knowledge",
      "type": "multiple",
      "difficulty": "easy",
      "question": "What is the first book of the Old Testament?",
      "correct_answer": "Genesis",
      "incorrect_answers": [
        "Exodus",
        "Leviticus",
        "Numbers"
      ]
    }
  ]
}
```
