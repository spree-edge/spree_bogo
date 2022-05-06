#  **Spree Buy X Get Y Free**

## **About**
* A spree extension that provides ability to have special discounts like Buy X Get Y free.
* Adminsrated role user create customized promotions using this and configure the product quantity as per the need.

## **Feature List**
* This extension extends the spree promotions and provides ability to create different type of promotions. 
  Some of the following promotions we can create are using this -
  * Buy One Get One
  * Buy Two Get Two
  * Buy One Get Half and many others combinations.
* These promotions can also be work in combination with the spree [Product Rule](https://user-docs.spreecommerce.org/promotions/creating-a-new-promotion#products).

## **Demo**
<img width="1000px" src="https://user-images.githubusercontent.com/80692612/163324308-344c1dca-7acf-42bb-9977-9293631d24f7.png">
<img width="1000px" src="https://user-images.githubusercontent.com/80692612/163324317-c884a17e-f7f7-4c96-b2d0-5699f15fcaa5.png">

## Installation

1. Add this extension to your Gemfile with this line:

    ```ruby
    gem 'spree_buy_x_get_y'
    ```

2. Install the gem using Bundler

    ```ruby
    bundle install
    ```

3. Copy & run migrations

    ```ruby
    bundle exec rails g spree_buy_x_get_y:install
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

[See corresponding guidelines](https://github.com/spree-edge/spree_buy_x_get_y/blob/master/CONTRIBUTING.md)

---

Copyright (c) 2022 Spree Edge. released under the [New BSD License](https://github.com/spree-edge/spree_buy_x_get_y/blob/master/LICENSE)
