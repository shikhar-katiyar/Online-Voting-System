This online voting system code consists of three main classes: Voter, Candidate, and VotingSystem, along with a Main class.

* Voter Class: Represents a voter with a voterId and name.
* Candidate Class: Represents a candidate in the election with a name and voteCount.
* VotingSystem Class: It's the core class that manages the voting process. It include:
  * registerCandidate(): Adds a new candidate to the system and checks for empty names and duplicate registrations.
  * getCandidateNames(): Returns a list of all registered candidate names.
  * displayCandidates(): Prints the list of all registered candidates to the console.
  * castVote(): Allows a voter to cast a vote for a specific candidate, validates the voter ID format, checks if the voter has already voted, and ensures the selected candidate is valid.
  * displayResults(): Calculates and displays the current voting results, including the total votes for each candidate and their percentage of the total votes and candidates are sorted by their vote count in descending order.
  * displayVoterDetails(): Shows a list of all voters who have cast a vote, along with their IDs and names.
  * getTotalVotes(): A private helper method to calculate the total number of votes cast in the system.

* Main Class: It presents a menu-driven interface to the user, allowing them to:
  1. Register candidates
  2. Display registered candidates
  3. Cast a vote
  4. Display voting results
  5. Show voter details
  6. Exit the application
