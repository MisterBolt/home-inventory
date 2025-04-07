# Home Inventory
[![Ruby](https://img.shields.io/badge/ruby-3.4.2-brightgreen.svg)](https://www.ruby-lang.org/en/news/2025/02/14/ruby-3-4-2-released)
[![Rails](https://img.shields.io/badge/rails-8.0.2-brightgreen.svg)](https://rubygems.org/gems/rails/versions/8.0.2)
[![Ruby Style Guide](https://img.shields.io/badge/code_style-omakase-brightgreen.svg)](https://github.com/rails/rubocop-rails-omakase)

A home inventory app to track items in your home.

## Table of Contents
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
* [Development](#development)
* [Test](#test)

## Getting Started

### Prerequisites
- **Ruby** - https://www.ruby-lang.org
- **Postgresql** - https://www.postgresql.org

### Installation
1. Clone the repo:
    ```sh
    git clone https://github.com/MisterBolt/home-inventory.git
    ```
1. Configure required environment variables shown in `app/.env.development` file.
1. Setup and run application:
    ```sh
    bin/setup
    ```

## Development
1. Run application:
    ```sh
    bin/dev
    ```

## Test
1. Run unit tests:
    ```sh
    rails test
    ```
1. Run system tests:
    ```sh
    rails test:system
    ```
