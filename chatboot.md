```python
print("Chatbot: Hello! Type something (type 'exit' to stop).")

while True:
    user_input = input("You: ")   # taking input

    if user_input.lower() == "exit":
        print("Chatbot: Goodbye!")
        break                     # exits the loop

    # simple responses
    print("Chatbot: You said →", user_input)
```

    Chatbot: Hello! Type something (type 'exit' to stop).
    

    You:  you
    

    Chatbot: You said → you
    

    You:  exit
    

    Chatbot: Goodbye!
    


```python
print("Chatbot: Hi! Type 'bye' to quit.")

while True:
    msg = input("You: ").lower()

    if msg == "bye":
        print("Chatbot: Take care! Goodbye.")
        break

    elif msg in ("hi", "hello", "hey"):
        print("Chatbot: Hello! How can I help you?")

    elif "name" in msg:
        print("Chatbot: I am your simple rule-based chatbot.")

    elif "age" in msg:
        print("Chatbot: I don't have an age, I run on Python!")

    else:
        print("Chatbot: Sorry, I didn’t understand.")
```

    Chatbot: Hi! Type 'bye' to quit.
    

    You:  hi
    

    Chatbot: Hello! How can I help you?
    

    You:  hello
    

    Chatbot: Hello! How can I help you?
    

    You:  hey
    

    Chatbot: Hello! How can I help you?
    

    You:  kesav
    

    Chatbot: Sorry, I didn’t understand.
    

    You:  bye
    

    Chatbot: Take care! Goodbye.
    


```python

```
