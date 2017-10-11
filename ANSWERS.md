## Questions

1. What is the difference between `new` and `create` for a model?

'New' creates the local object, but does not save it. 'Create' creates an object and saves it to the database.

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?

Cat.new.save

3. What is the default integer column that exists on every table but we did NOT define?

id

4. What single line of ruby code can insert a cat with the name "Kira" in the database?

Cat.create(:name => 'Kira')

5. How did you like this homework in comparison with the previous homeworks?

This homework was hard. The previous ones were ok, but it was probably because there were more examples and demos. This one was particularly harder because the resources and the lack of a video demo contributed to my confusion.
