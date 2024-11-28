def get_actor_lists():
    # Returns two lists: actorGivenList and actorFamilyList
    actorGivenList = ['Andrei', 'Harry', 'Yuan', 'Sadiq', 'Zeng']
    actorFamilyList = ['Stephens', 'Venables', 'Spield', 'Elbahi', 'Ergan']
    return actorGivenList, actorFamilyList

def generate_alien_names(given_names, family_names):
    # Combines parts of given and family names to generate alien names
    alien_names = []
    for i in range(len(given_names)):
        alien_name = family_names[i][:3] + given_names[i][:2]
        alien_names.append(alien_name)
    return alien_names

def print_credits(given_names, family_names, alien_names):
    # Print the credits
    print("The Alien Adventure")
    print("Starring")
    print("The cast:")
    for i in range(len(given_names)):
        actor_name = given_names[i] + " " + family_names[i]
        print(actor_name + " played the part of " + alien_names[i])

def main():
    # Main function to execute the program
    given_names, family_names = get_actor_lists()
    alien_names = generate_alien_names(given_names, family_names)
    print_credits(given_names, family_names, alien_names)

# Execute the program
if __name__ == "__main__":
    main()
