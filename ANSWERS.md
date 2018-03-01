## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

The nil represents the default value when you submit the form and don't input anything.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
 This doesn't work because there's no GET request there yet. 

3. What type of request did your browser just perform?

My browser performed a GET request. 
4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

I end up at localhost:3000/teachers
5. Why does `localhost:3000/teachers` work now?

A get request worked, as something is now 'shown' from the teachers_controller file. 