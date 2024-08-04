# Tic Tac Toe Technical and Visual Outline

For the project itself, visit the [GitHub folder](https://github.com/jtrshy/portfolio/tree/main/projects/Tic%20Tac%20Toe).

## Technical Outline

Tic Tac Toe is a simple game where a player tries to achieve 3 X's or O's in a row, column, or diagonally.

We have recreated the game in a web applications using the following technologies (in no particular order):
1. HTML/CSS for front end design
2. JavaScript for client side interactions
3. PHP for server side interactions
4. PostgreSQL for managing data

The project was made for CSI 3140, the WWW Struc Techn & Standards course at the University of Ottawa. It went through 4 primary iterations, each corresponding with assignments 1 to 4.

### Features
- Player vs Player gameplay
- Player vs Computer gameplay
- Interactive UI
- Winning message display
- Falling X's and O's animation
- Top 10 leaderboard
- User account functionality (with admin and player roles)
- Current score display

### Setup instructions

Initial database setup:
1. psql -U postgres
2. CREATE database tictacdb
3. exit
4. psql -U postgres -d tictacdb -f db/schema.sql

Notes:
1. For the error "Connection failed: could not find driver", make sure extension=pdo_pgsql does not have a leading ";" in php.ini
2. While in PSQL, use \c tictacdb to connect to the database and \dt to list the tables

To run this project locally with the PHP component (after the database is setup):
1. Clone the repository.
2. Navigate to the project location within CMD.
3. Use: php -S localhost:9000
4. Navigate to http://localhost:9000 in your web browser.

## Visual Outline

### Login page

![Login page](Tic%20Tac%20Toe/docs/design_system/assets/v3/login.png)

### Signup page

![Signup page](Tic%20Tac%20Toe/docs/design_system/assets/v3/signup.png)

### Initial Game Interface

![Initial interface](Tic%20Tac%20Toe/docs/design_system/assets/v3/initial_interface.png)

### Rules

![Rules](Tic%20Tac%20Toe/docs/design_system/assets/v3/rules.png)

### Player vs Player Mode

![Player vs player mode](Tic%20Tac%20Toe/docs/design_system/assets/v3/player_vs_player.png)

### Player vs Computer Mode

![Player vs computer mode](Tic%20Tac%20Toe/docs/design_system/assets/v3/player_vs_computer.png)

### Winning state

![Winning state](Tic%20Tac%20Toe/docs/design_system/assets/v3/winning_state.png)

### It's a tie state

![Tie state](Tic%20Tac%20Toe/docs/design_system/assets/v3/tie_state.png)

### Update profile page

![Update profile page](Tic%20Tac%20Toe/docs/design_system/assets/v3/update_profile.png)

### Admin dashboard

![Admin dashboard](Tic%20Tac%20Toe/docs/design_system/assets/v3/admin_dashboard.png)