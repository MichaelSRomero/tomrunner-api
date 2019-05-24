<h1 align="center">
  <a href="https://github.com/MichaelSRomero/tomrunner"><img src="https://github.com/MichaelSRomero/tomrunner/blob/master/assets/tomrunner-logo.png" alt="Tom the Runner" width="300"></a>
  <br>
</h1>

Tom Runner is an endless runner game built with Phaser 3, Vanilla JS and Ruby on Rails. Tom (the main character) is out to survive the cyber punk city after escaping his cohort. Jump back and forth through platforms and see how long Tom can survive. But beware, some platforms fall, and getting too close to the screen can mean death!

<h1 align="center">
  <a href="https://michaelsromero.github.io/tomrunner/">PLAY NOW!</a>
</h1>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

First you must fork and clone this Repository onto your terminal. After you have done so, you can fork and clone the Client-side repo which is located here: [Tom-Runner-Client](https://github.com/MichaelSRomero/tomrunner)

```
<!-- API -->
git clone https://github.com/MichaelSRomero/tomrunner-api.git
<!-- Front End -->
git clone https://github.com/MichaelSRomero/tomrunner.git
```

### Installing

#### Ruby Version
`2.6.1`

```
Bundle Install
```

Make sure Postgres is on & create the database:

```
rails db:create
```

Run Migrations:

```
rails db:migrate
```

Run the Server:
```
rails s
```

## Demo

<h1 align="center">
  <a href="https://michaelsromero.github.io/tomrunner/"><img src="https://github.com/MichaelSRomero/tomrunner/blob/master/assets/tom-runner.png" alt="Tom the Runner" width="300"></a>
  <br>
</h1>

## Deployment

* Backend was deployed on Heroku using the free Hobby Dev option
* Frontend is deployed and being hosted by GitHub
<br>

[Tom Runner Game](https://michaelsromero.github.io/tomrunner/?fbclid=IwAR3Gm1gssi3wR7sh3YDrOdCzjphZ3GOBn41mlVh3ihdcH6FVBBjkBt7HLWc)

## Built With

* [Phaser 3](http://phaser.io/news) - The game framework used
* [Ruby on Rails](https://rubyonrails.org/) - Backend
* Javascript - Plain old Javascript

## Authors

* [**Mazen AlSwar**](https://github.com/mazenswar) - *Initial work*
* [**Michael Romero**](https://github.com/michaelsromero) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Animated Runner Character - by [irmirx](https://opengameart.org/users/irmirx)
* Sci Fi Platforms - from [GameArt2d](https://www.gameart2d.com/free-sci-fi-platformer-tileset.html)
