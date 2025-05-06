# DBS311-Lab-10-MongoDB-Aggregation

Download Here: [DBS311 Lab 10 – MongoDB – Aggregation](https://codingherolab.com/product/dbs311-lab-10-mongodb-aggregation/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Tasks
1. Write an aggregate statement to sort the documents in the grades collection based on
students ID and class ID. Display only the student ID and the class ID for each document.
Sort the result from high to low values for student ID and from low to high for class ID.

2. Revise the previous query to show the result for students with IDs between 10 and 12.
3. Show only existing class IDs in the grades collection. (Do not show duplicates.)
4. Write a query to display student ID and class ID for students whose score are greater than
99.00. Sort the result based on student ID from high to low and class ID from low to
high.
5. Write a query to show the maximum and the minimum class ID for each student. Sort the
result based on student ID from low to high. Show only the first 10 students.
See the following sample output:
{ “_id” : 0, “max_class_id” : 30, “min_class_id” : 2 }
{ “_id” : 1, “max_class_id” : 28, “min_class_id” : 13 }
{ “_id” : 2, “max_class_id” : 27, “min_class_id” : 24 }
{ “_id” : 3, “max_class_id” : 25, “min_class_id” : 3 }
{ “_id” : 4, “max_class_id” : 26, “min_class_id” : 0 }
{ “_id” : 5, “max_class_id” : 30, “min_class_id” : 0 }
{ “_id” : 6, “max_class_id” : 29, “min_class_id” : 8 }
{ “_id” : 7, “max_class_id” : 17, “min_class_id” : 17 }
{ “_id” : 8, “max_class_id” : 29, “min_class_id” : 0 }
{ “_id” : 9, “max_class_id” : 30, “min_class_id” : 0 }

6. Write a query to find the number of failed exams for student with ID 48.
