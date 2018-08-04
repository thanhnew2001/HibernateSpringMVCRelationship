This project helps set a sample for addresing the link between 2 entities. A student will have some visits to hospitals. A visit will belong to only 1 student.
- In Student has a List<Visit>
- In Visit class has a property refering to Student
        
By setting cascading for Student, we can save a student and many visit with one POST
By setting cascading for Visit, we can save a visit and a student with one POST
