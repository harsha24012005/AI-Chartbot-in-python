# Simple AI Chatbot in Python

def main():
    print("🤖 Hello! I'm ChatBot. Let's talk. (Type 'bye' to exit)")

    while True:
        user_input = input("You: ").lower()

        if "hi" in user_input or "hello" in user_input:
            print("Bot: Hi there! 😊")
        elif "how are you" in user_input:
            print("Bot: I'm just a program, but I'm doing fine! Thanks for asking.")
        elif "your name" in user_input:
            print("Bot: I'm your friendly chatbot. You can call me ChatBot!")
        elif "bye" in user_input or "exit" in user_input:
            print("Bot: Goodbye! Have a great day! 👋")
            break
        elif "who made you" in user_input or "created you" in user_input:
            print("Bot: I was created by a Python programmer. 🙂")
        else:
            print("Bot: Hmm... I didn't understand that. Can you try something else?")

if __name__ == "__main__":
    main()

