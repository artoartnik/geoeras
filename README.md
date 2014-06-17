geoeras
=======

A gem that adds geologic time period methods to the Date class

Example:
```ruby
:001 > require 'date'
=> true
:002 > require 'geoeras'
=> true
:003 > date = Date.million_years_ago(0.12)
:004 > date.in_late_pleistocene?
=> true
```
