# Cassandra Data Modeling
Case: Data modeling for Cassandra data base for an educational institute

This is a case study for modeling database that takes advantage of faster reads and writes in Cassandra database. The domain chosen for this case study is an educational institute.

Points about the educational institute. Let's call it Rising Stars Academy.
1. Students are enrolled in a class and they remain in the class for a year. 
2. After successful completion of the final exams they graduate to the next class. 
3. There are various teachers who are assigned various departments based on the subjects.
4. A teacher can teach multiple subjects.
5. A teacher teaches a class in a lecture which typically lasts for an hour. 
6. Teacher takes multiple lectures in a day and a class attends multiple lectures through the day.
7. Students could be given an assignment during a lecture and are scored on it by the teacher.
8. Periodically a teacher conducts an exam and exam can be given to multiple classes studying the same subject.
9. Students are evaluated on the exams and aggregate from the exam above a cutoff qualifies them to the next class.
