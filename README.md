# HN Monitor

## Receive alerts on keywords and domains on Hacker News

This is a product being built by the Assembly community. You can help push this idea forward by visiting [https://assembly.com/hn-monitor](https://assembly.com/hn-monitor).

### How Assembly Works & contributions

Assembly products are like open-source and made with contributions from the community. Assembly handles the boring stuff like hosting, support, financing, legal, etc. Once the product launches we collect the revenue and split the profits amongst the contributors.

Visit [https://assembly.com](https://assembly.com) to learn more.

### Setup

- Create a PostgreSQL role if you don't have one
<br>`create role username login createdb;`
- Install the required gems list
<br>`bundle install`
- Set up the database
<br>`rake db:create`
<br>` rake db:migrate`
- Run the app
<br>`rails s`


####Tech Stack:
- Ruby version 2.1.2
- Rails version 4.1.6

- Authentication:
  - Devise

- Database:
  - PostgreSQL

- Testing:
  - RSpec
  - Capybara

- Server:
  - Puma

- CSS framework:
  - Bootstrap 3
  - Bootstrap SASS


