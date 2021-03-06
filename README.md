# Project Ullrich
By NEO Endurance

Project Ullrich is the team management system for NEO Endurance Series league. With this platform team are able to register their team and entries. The organisation can manage the grid and teams.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
* Install latest LTS version [NodeJS](https://nodejs.org/en/).
* Install CLI for [Angular](https://cli.angular.io).

### Installing
1. Clone the repository.
2. Install dependencies:
```
npm install
```
3. Create .env file
```
DISCORD_SECRET=<secret>
SESSION_SECRET=<not so secret>
AIRTABLE_BASE=<not so secret>
AIRTABLE_API_KEY=<secret>
```
4. Start Express server locally:
```
npm start
```
5. Open de browser and go to `localhost:3000`.

## Built With
* [Angular](https://angular.io) - The front-end framework used
* [Express](https://expressjs.com/) - The back-end framework used
* [Airtable](https://airtable.com/) - The database used

## Authors
* **Niel Hekkens** - *Initial work* - [NEO Endurance](https://www.neo-endurance.com)

See also the list of [contributors](https://github.com/HappyNiel/neo-project-ullrich/graphs/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Hat tip to anyone who's code was used
* Inspiration
* etc
