import random
import string

def generate_steam_key():
    key_length = 5
    block_count = 5

    steam_key = "-".join("".join(random.choice(string.ascii_uppercase + string.digits) for _ in range(key_length)) for _ in range(block_count))
    return steam_key

# Generating and printing 1000 Steam-like keys
for _ in range(1000):
    print(generate_steam_key())
