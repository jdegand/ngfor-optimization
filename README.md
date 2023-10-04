# Ngfor Optimization

[Angular Challenges](https://angular-challenges.vercel.app/challenges/angular-performance/36-ngfor-optimize/) #36 NgFor Optimization solution

## Built With

- [Angular](https://angular.io)
- [Angular CLI](https://github.com/angular/angular-cli) version 16.2.2.

## Thoughts

- Would be nice if person model had an id -> could just add trackBy without a custom function
- Using the profiler, it is tough to tell if the trackBy function is working.
- Looking at the elements of the app-list is better to tell that the whole list is not updating when using the input, the delete or update buttons.   

## Useful Resources

- [Stack Overflow](https://stackoverflow.com/questions/47843856/angular-what-is-the-point-of-implementing-trackby) - angular what is the point of implementing trackby
- [Telerik](https://www.telerik.com/blogs/angular-basics-keep-track-incoming-data-angular-trackby-method#:~:text=The%20TrackBy%20Directive,-Angular%20came%20up&text=TrackBy%20and%20ngFor%20together%20allow,of%20rebuilding%20the%20whole%20array.) - angular basic keep track incoming data angular trackby method
- [Angular University](https://blog.angular-university.io/angular-2-ngfor/) - angular 2 ngFor
- [Github](https://github.com/angular/angular/issues/12969) - Supporting trackBy: expression|id #12969
- [Medium](https://medium.com/@ingobrk/here-is-how-you-can-use-trackby-with-a-property-name-ec3bbba8fa75) - here is how you can use trackby with a property name