## Questions

1. What is the difference between new and create for a model?
	The difference is that 'create' instantiates an object, validates it, and then saves it into the database. 'New' instantiates a local object but does not save it into the database.
2. What command combined with new will emulate the same behavior as create?
	'@___.save' will emulate the smae behavior as create.
3. What is the default integer column that exists on every table but we did NOT define?
	id
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
	@cats.create(:name =>'Kira')
5. How did you like this homework in comparison with the previous homeworks?
	Hw 3 was the best, this was the 2nd best. Hw 2 was a little brutal to figure on my own.
