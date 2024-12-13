# ctfd
# main.py
def greet(name):
    """
    Returns a greeting message for the given name.
    """
    return f"Hello, {name}! Welcome to Project Alpha."

if __name__ == "__main__":
    user_name = input("Enter your name: ")
    print(greet(user_name))
