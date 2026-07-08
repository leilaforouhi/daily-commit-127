def find_longest_string(strings):
    return max(strings, key=len)


if __name__ == "__main__":
    words = [
        "python",
        "repository",
        "commit",
        "automation",
        "developer"
    ]

    print("Words:", words)
    print("Longest word:", find_longest_string(words))
