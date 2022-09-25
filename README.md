# refactor

In controller first of all have constructor.this is good practice you make an object and using all attribute in controller-

Also you use repository pattern ,this is easiest way to handle all the logic and make collection in repository ,just append a collection in controller. 

The main advantage of repository pattern is make our application run smoothly and nop need to much code in controller-

using repository pattern is, in future, easily configurable/changeable interface system-It really comes down to how you have set-up your code. In your particular case, there wouldn't appear to be much benefit-

make booking request method for validation of storing function-also need request function for updating
method-

In Booking repository you can create object but just need add all fillable field in model and use creat($request->all());

In BookingRepository you can not using eager loading you using lazy loading it reduce the proformance of the time and do response later-

try to use cases in function, except if else statement-