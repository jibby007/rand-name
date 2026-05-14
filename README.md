# rand-nameimport random

cities = [
    "Columbus", "Cincinnati", "Chicago", "Seattle",
    "Austin", "Nashville", "Baltimore", "Buffalo",
    "San Diego", "Pittsburgh", "Louisville", "Kansas City"
]

adjectives = [
    "Flying", "Golden", "Dark", "Electric",
    "Savage", "Wild", "Royal", "Frozen",
    "Mighty", "Rapid", "Fearless", "Epic"
]

mascots = [
    "Bears", "Cobras", "Hawks", "Panthers",
    "Rhinos", "Pirates", "Lions", "Eagles",
    "Foxes", "Bulls", "Warriors", "Tigers"
]

print("Here Are 5 New NBA Teams...\n")


for i in range(5):
    city = random.choice(cities)
    adjective = random.choice(adjectives)
    mascot = random.choice(mascots)

    print(city, adjective, mascot)
