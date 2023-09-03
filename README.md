# Majestic-Forest
Majestic Forest
class MagicalForest:
    def __init__(self):
        self. flora = ["tall pines",
                       "mystical bluebells", "whispering willows"]
        self. fauna = ["celestial wolves",
                       "emerald serpents", "shapeshifting foxes"]

    def enter_forest(self):
        print("\nYou find yourself standing at the edge of a vast and enchanting forest.")
        input("\nPress enter to continue...")
        print(
            f"\nAround you, there are {self. flora[0]} that seem to touch the skies, fields of {self. flora[1]} that glow under the moonlight, and the gentle sway of the {self. flora[2]} that beckon you forward.")
        self.hear_forest()

    def hear_forest(self):
        sounds = ["wind rustling through the leaves",
                  "distant fairy giggles", "mystical tunes floating on the breeze"]
        print(
            f"\nAs you take a step deeper into the forest, you hear {sounds[0]}, {sounds[1]}, and {sounds[2]}.")
        self.encounter_fauna()

    def encounter_fauna(self):
        print(
            f"\nA shimmering figure appears before you. It's one of the {self.fauna[2]}!")
        action = input("\nDo you approach the fox? (yes/no): ")
        if action == 'yes':
            print("\nThe fox gracefully transforms into a majestic stag, guiding you further into the magical realm.")
            self.discover_clearing()
        else:
            print("\nYou decide to continue on your path, feeling the mysteries of the forest unravel with each step.")

    def discover_clearing(self):
        print("\nThe stag leads you to a moonlit clearing where fairies dance, and the aura is imbued with magic.")
        input("\nPress enter to absorb the magical aura...")
        print("\nAnonymous name appears beside you, wrapping his arms around you. You both stand still, lost in the magical symphony of the forest, feeling the heartbeats synchronize and time standing still.")


if __name__ == "__main__":
    forest = MagicalForest()
    forest.enter_forest()

