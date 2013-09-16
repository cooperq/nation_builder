# nation_builder

A very simple ruby gem for interacting with NB people API. 

http://nationbuilder.com/api_documentation

## Usage

```
require 'nation_builder'
client = NationBuilder.new(hostname: 'whatever.nationbuilder.com', client_id: 'id', client_secret: 'secret', username: 'you@nation.com', password: 'pass')
client.people.list # returns people in nation

```

## Copyright

Copyright (c) 2013 Nathan Woodhull. See LICENSE.txt for
further details.
