# CodeAlpha_Basic-Chatbot
def chatbot():
    print("Chatbot: Hello! Type 'bye' to exit.")

    while True:
        user = input("You: ").lower()

        if user == "hello":
            print("Chatbot: Hi!")
        elif user == "how are you":
            print("Chatbot: I'm fine, thanks!")
        elif user == "bye":
            print("Chatbot: Goodbye!")
            break
        else:
            print("Chatbot: Sorry, I don't understand.")
chatbot()


"Description"
This program creates a simple rule-based chatbot using Python. The chatbot interacts with the user by taking input and responding to predefined messages. It continues the conversation until the user types "bye".

"Concepts Used"
Functions (def)
Infinite loops (while True)
Conditional statements (if, elif, else)
User input (input())
String methods (lower())
Loop control (break)
