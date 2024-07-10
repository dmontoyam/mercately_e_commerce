# E-commerce App

A simple e-commerce application for managing items and orders.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Testing](#testing)

## Introduction

This project is an e-commerce application designed to manage items and process orders through a web interface.

## Features

- Displaying items with images, descriptions, and prices
- Adding items to a cart and adjusting quantities
- Creating orders based on items in the cart
- Validating orders and calculating total prices
- Deleting items and orders (soft delete)

## Technologies Used

- Ruby on Rails
- Tailwind CSS
- Import-map-rails
- Stimulus.js
- PostgreSQL
- RSpec for testing
- SimpleCov for test coverage

## Setup Instructions

### Prerequisites

- Ruby 3.2.2
- Rails 7.1.3
- PostgreSQL

### Configuration

- `config/database.yml` configure your database settings.

### Installation

1. Clone the repository.
2. Install dependencies with `bundle install`.
3. Set up the database with `rails db:setup`.
4. Start the server with `rails server`.

## Usage

1. Navigate to `http://localhost:3000`.
2. Browse available items and add them to your cart.
3. Proceed to checkout to create an order.

## Testing

Run tests with RSpec:

```bash
bundle exec rspec
```
