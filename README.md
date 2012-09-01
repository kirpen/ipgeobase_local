# IpgeobaseLocal

География российских и украинских IP-адресов. Поиск местонахождения (города) IP-адреса, локальный поиск

## Installation

Add this line to your application's Gemfile:

    gem 'ipgeobase_local'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ipgeobase_local

## Usage

    ip_meta = Ipgeobase.lookup('10.11.12.134')

    ip_meta.city # => Москва

    ip_meta.country # => Россия

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
