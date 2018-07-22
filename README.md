# Second HomeWork:

---------

This will be a restraunt reservation app without registration.
* Create `Reservation` and `Customer` models.
*  You can create your own models and controllers.
*  Make a relationship between `Reservation` and `Customer` models.
*  `before_create` you must create random string and you must set `reservation_code`to this attribute on Reservation model.
*  `after_create` you will send email new `reservation_code` to your `customer`.(psuedo code)
*  `before_validation` you need to delete spaces in your `full_name` string on Customer model. (regular expressions)
*   You can only save orders except sundays.
