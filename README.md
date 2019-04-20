# Trivia-Game
A responsive 3-question timed trivia game that runs like a Buzztime trivia game. Powered by Javascript.

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

Known issues and future enhancements:
-when app is running, app must remain in active window. If referred back to, game will break due to DOM timing misses.
-Scoring needs should be visible at the end of each question.
-Space out clue delivery a bit more.
