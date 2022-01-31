# GUCPostGrad Office Database Demo
## Project Overview
  The GUC has a postgrad office responsible for masters and PhD. programs. The postgrad office wants to create a system to keep track of students doing their postgrad studies as well as manage the process of students taking prerequisite courses for the postgrad studies. Students need to register for their master or PhD through this system. The aim of the project is to implement a system that provides these features to the parties involved.
  
## Users
Different types of users can use the postgrad system. Users are either: Admin, Supervisor or Student. Any user can view, and search any information related to the theses and publications available on the system.
1. Admin: The admin can update the details stored in the system.
2. Student: Two different types of students could register; non GUCian and Gucian.
3. Supervisor: A supervisor is responsible for the supervision of students doing their theses. 

## Thesis 
Each thesis has a unique serial number, title, type (Master or PhD), field, startDate, endDate, seminarDate, and number of extensions needed (in case the student did not finish it before the endDate). The postgrad office should be able to calculate the number of years spent in the thesis since the start date. A student can make his/her Master and PhD in the university so the system needs to keep track of his/her theses in these two cases. Each thesis has a payment that should be completed. Each thesis has its own defense.

## Defense
A student represents his/her thesis work in a defense. It has a date, grade, and location. Furthermore,
examiners attend to evaluate the defense and provide his/her comments. An examiner has a name, field
of work, and may be a national or international examiner.

## Progress report
A student can fill progress reports for a specific thesis. A progress report shows the progress state (numeric). A progress report has a description, date, and evaluation.

## Course
Non GUCian student have to take courses. Each course has a unique ID, code, and credit hours. The postgard office keeps track of the grade the student in this course. Each course has fee that should be paid by the registered student.

## Publication
A student can publish different publications. Each publication has a date when it will be posted , title of the publication , host which is the name of the conference it will be posted in , and place which is the location of the conference. The postgrad office keeps track if it is accepted. A publication belongs to one or more theses.

## Payment
The postgrad office keeps track of the total amount, fund percentage, number of installments, and payment ID. Some publications have payment. Each payment can be divided into one or more installments. Each installment will have a date, amount, and status (paid or not).

## Authors 
1. [Salma Sleem](https://github.com/salmasleem)
2. [Malak El Kashab](https://github.com/malakel-khashab)
3. 
4.  

