# RottenPotatoes 🎬

RottenPotatoes is a Ruby on Rails web application for managing a movie collection. Users can browse movies, view their details, and add, edit, or delete records.

## Features

- View all movies in a table.
- View individual movie details.
- Add movies with a title, rating, and release date.
- Edit and delete existing movies.
- Sort movies by title, rating, or release date.
- Remember the selected sorting preference.
- Populate the database with sample movies.

## Technology Stack

- Ruby
- Ruby on Rails
- Active Record
- HTML and ERB

## Getting Started

### Prerequisites

Install Ruby, Bundler, and the Rails version specified in the project's `Gemfile`.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/DarshTulsiyan/rottenpotatoes.git
   cd rottenpotatoes
   ```

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Create the database, run migrations, and load sample data:

   ```bash
   bin/rails db:prepare
   bin/rails db:seed
   ```

4. Start the application:

   ```bash
   bin/rails server
   ```

5. Open the application in your browser:

   http://localhost:3000

## Usage

- Open the movie list to browse the collection.
- Click a movie title to view its details.
- Use the available links to add, edit, or delete a movie.
- Click the title, rating, or release date column heading to sort the list.

## Project Structure

| Location | Purpose |
|----------|---------|
| `app/models/` | Application models and database relationships |
| `app/controllers/` | Request handling and application logic |
| `app/views/` | Pages and ERB templates |
| `config/routes.rb` | Application routes |
| `db/migrate/` | Database migrations |
| `db/seeds.rb` | Sample movie data |
| `Gemfile` | Ruby and Rails dependencies |

## Sample Data

The seed data includes movies such as:

- My Neighbor Totoro
- Green Book
- Parasite
- Nomadland

Run `bin/rails db:seed` to load the sample data.

## Author

[Darsh Tulsiyan](https://github.com/DarshTulsiyan)
