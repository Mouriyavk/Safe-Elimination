# Safe-Elimination

Welcome to the **Safe Elimination**! This game is designed for a group of players, where the objective is to be the last player standing. Players are eliminated based on their ability to deduce and strategize using the Safe or Elimination card.

## Table of Contents

- [Gameplay Overview](#gameplay-overview)
- [Setup](#setup)
- [How to Play](#how-to-play)
  - [Selecting Players](#selecting-players)
  - [Questioning Phase](#questioning-phase)
  - [Decision Phase](#decision-phase)
- [Winning the Game](#winning-the-game)
- [Example](#example)
- [Tech Stack](#Tech-Stack)
- [Requirements](#Requirements)
- [Contributing](#contributing)
- [License](#license)

## Gameplay Overview

In each round, two players are selected from the group. One player is shown a card that can either be "Safe" or "Elimination." The other player must ask questions to deduce the nature of the card. Based on the responses, the second player decides whether to steal the card or leave it. If they steal and it’s an Elimination card, they are eliminated. If they don’t steal and it’s an Elimination card, the first player is eliminated. The game continues until only one player remains.

## Setup

1. **Players**: Minimum of 3 players.
2. **Cards**: Create a set of cards with equal numbers of "Safe" and "Elimination" cards.
3. **Facilitator**: A person or system to manage the game flow, select players, and show cards.

## How to Play

### Selecting Players

1. At the start of each round, the facilitator randomly selects two players from the group.
2. One of the two selected players is randomly chosen to view the card.

### Questioning Phase

1. The player who did not see the card (Player B) starts asking questions to the player who saw the card (Player A).
2. The questioning phase lasts for a predetermined number of questions

### Decision Phase

1. After the questioning phase, Player B must decide whether to steal the card or not.
   - **If Player B steals the card**:
     - If it’s a Safe card, Player B remains in the game, and Player A is safe for this round.
     - If it’s an Elimination card, Player B is eliminated from the game.
   - **If Player B does not steal the card**:
     - If it’s a Safe card, both players remain in the game.
     - If it’s an Elimination card, Player A is eliminated from the game.

## Winning the Game

The game continues with rounds of questioning and decision-making until only one player remains. That player is declared the winner.

## Example

1. Players: Alice, Bob, Charlie, and Dana.
2. Facilitator selects Alice and Bob.
3. Alice is shown an Elimination card.
4. Bob asks questoions
5. Bob decides not to steal the card.
6. Since the card was an Elimination card, Alice is eliminated.
7. The game continues with the remaining players.


## Tech Stack

### Frontend

- **HTML5**: For structuring the web pages.
- **CSS3**: For styling the web pages.
  - **Sass**: A CSS preprocessor to write more maintainable and reusable styles.
- **JavaScript**: For adding interactivity to the web pages.
  - **React**: A popular JavaScript library for building user interfaces.
  - **TypeScript**: A superset of JavaScript that adds static typing, making your code more robust and easier to maintain.
- **Bootstrap**: A CSS framework to quickly design responsive web pages.

  
### Backend

- **Python**: A versatile programming language used for backend development.
- **Flask**: A lightweight WSGI web application framework for building APIs.
- **SQLAlchemy**: An ORM for Python that provides a full suite of well-known enterprise-level persistence patterns and provides a high-level API for database interactions.
- **PostgreSQL**: A powerful, open-source object-relational database system.

### Development Tools

- **VSCode**: A powerful code editor with extensions for JavaScript, TypeScript, Python, and more.
- **Git**: A version control system for tracking changes and collaborating with others.
- **Webpack**: A module bundler for JavaScript applications.
- **ESLint**: A tool for identifying and fixing JavaScript code issues.
- **Prettier**: A code formatter to ensure consistent code style.

### Testing

- **Jest**: A JavaScript testing framework for frontend testing.
- **React Testing Library**: A library for testing React components.
- **pytest**: A testing framework for Python that makes it easy to write simple and scalable test cases.
- **Flask-Testing**: An extension for Flask that provides testing utilities.

## Requirements

- **Node.js**: Required to run the React development server and build the frontend.
- **npm**: The Node.js package manager, included with Node.js.
- **Python 3.x**: Required for running the Flask backend.
- **PostgreSQL**: Required for the database.
- **Git**: For version control.


## Contributing

We welcome contributions to enhance the Safe Elimination Game. If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy the game and may the best strategist win!
