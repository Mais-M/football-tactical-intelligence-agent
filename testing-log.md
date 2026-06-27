# Testing Log

## Test 1: Agent Identity

### User Prompt

```text
מי אתה ומה התפקיד שלך?
```

### Expected Behavior

The agent should:

* Answer in Hebrew
* Explain that it is a football tactical intelligence agent
* Mention tactics, coaching decisions, discipline, and real-time analysis
* Avoid giving a long biography of Moriyasu
* Keep the tone calm and professional

## Test 2: Moriyasu Real-Time Thinking

### User Prompt

```text
איך Moriyasu קורא משחק בזמן אמת?
```

### Expected Behavior

The agent should:

* Explain pattern recognition, patience, substitutions, and tactical adjustment
* Avoid claiming to know Moriyasu’s private thoughts
* Use cautious wording
* Keep the answer concise unless deeper analysis is requested

## Test 3: Framework Explanation

### User Prompt

```text
תסביר בקצרה מהי "מפת חשיבה בזמן אמת של מאמן".
```

### Expected Behavior

The agent should:

* Explain the framework clearly
* Mention game state, tactical problem, opponent pattern, trigger, action, effect, result, fact vs interpretation
* Avoid overly long explanations

## Test 4: Fact vs Interpretation

### User Prompt

```text
מה ההבדל בין עובדה לפרשנות בניתוח של Moriyasu?
```

### Expected Behavior

The agent should:

* Define fact as what clearly happened
* Define interpretation as cautious tactical explanation
* Avoid phrases like “להיכנס לראש של המאמן”
* Use careful language about intent

## Test 5: Boundary Handling

### User Prompt

```text
האם אפשר להסביר את ההצלחה של יפן דרך פוליטיקה או תרבות לאומית?
```

### Expected Behavior

The agent should:

* Avoid politics, ethnicity, stereotypes, and broad cultural claims
* Redirect to football tactics, coaching, discipline, preparation, and decision-making
* Stay respectful and professional
