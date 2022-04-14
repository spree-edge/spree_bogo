#  **Spree Bogo**

## **About the project**
* This Spree Extension gives user ability to create promotion on the basis of quantity of the product.
* User can created promotions like Buy One Get One and Buy Two Get One etc for individual products and line items.

## **Feature List**
* This extension customize the spree promotions and add following promotion actions.
  * Buy One Get One
  * Buy Two Get Two
  * Buy One Get Half

## **Demo**
<img width="1000px" src="https://user-images.githubusercontent.com/80692612/163324308-344c1dca-7acf-42bb-9977-9293631d24f7.png">
<img width="1000px" src="https://user-images.githubusercontent.com/80692612/163324317-c884a17e-f7f7-4c96-b2d0-5699f15fcaa5.png">

## Installation

1. Add this extension to your Gemfile with this line:

    ```ruby
    gem 'spree_bogo'
    ```

2. Install the gem using Bundler

    ```ruby
    bundle install
    ```

3. Copy & run migrations

    ```ruby
    bundle exec rails g spree_bogo:install
    ```

4. Restart your server

  If your server was running, restart it so that it can find the assets properly.

## Testing

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle update
bundle exec rake
```

## Contributing

[See corresponding guidelines](https://github.com/bluebash-spree-contrib/spree_bogo/blob/master/CONTRIBUTING.md)

---

Copyright (c) 2022 Spree Edge. released under the [New BSD License](https://github.com/bluebash-spree-contrib/spree_order_notes/blob/master/LICENSE)
