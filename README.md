Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.

# 📚 Rentool

This was our first group project at Le Wagon. It is a Desktop Rails app airbnb clone. It is a basic marketplace that allows users to list their tools for rent, and other users can rent them for use.

<br>
App home: [https://airbnb-carved-duck-e9e78c22c0c6.herokuapp.com/)
   

## Getting Started
### Setup

Install gems
```
bundle install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
Thanks to the teachers at Le Wagon for the help on our first team based rails app!

## Team Members
- [Will Sebastian](https://github.com/MaddRussian)
- [Julian Schoenfeld](https://github.com/carved-duck)
- [Hikari Hashiguchi](https://github.com/hikari-h)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License
