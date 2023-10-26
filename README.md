Hospital Management
 Description of the Project:
 1) Patient: 
In patient module here, we can register the new patient, during registration we enter the
basic information regarding patient. There are two types of patient one is INPATIENT
and another is OUTPATIENT. If patient is INPATIENT then we can check the
availability of room in particular ward.
 2) Appointment Scheduling Module
 In appointment scheduling we schedule the appointment for new patient in which
we assign the date, time, department and doctor is available that time. If patient want
particular doctor then we can search the doctors scheduling and available time for that
doctor. Here we add the urgency and reminder to patient. We can also cancel the
appointment of particular patient.
 
Medoc’s (Medical documentation and services):
We can enter or view the previous medical record of particular patient. 
We can enter or view the PRESCRIPTION of particular patient.
We can enter or view other information like:
• Notes and reports,
• Allergy,
• Diet Plan,
• Physician Orders,
• Problems,
• Measurement, 
• Diagnosis,
• Therapy,
• Medical advice
 3) Admission:
In this module we can search the only admitted patient. Here we can update his details
like prescription, notes and reports, measurement, birth details, pregnancies and we
can cancel the particular admission.
4) Ambulatory:
In this module we can see the information related to patients which are outpatient. Here
we can see the department wise appointment and particular day’s outpatient. We can
also see the today’s waiting list and also transfer or take over the patient from one
department to another department. From here we can also admit the patient. 
5) Nurse:
In this module we can register the new specialist, for which we can enter the basic
information about employee and his professional details. 
6) Doctors:
In this module we can view the today’s doctor on call schedule department-wise. Here
we can create the duty plan of doctor and edit or update the duty plan of particular
doctor. Here we can add/delete the doctor to particular department. 
7) Ward Management:
Here we can create new ward, in particular department, assign the rooms to ward, how
many beds for particular room. All of these we can set from here.
8) Room Management:
Here we can search the patient who is gone through any operation and his detail
information like operation date, surgeon, therapy, special notice, operation type,
operation room number. Here we can also give the quick view of today’s nurses on
standby duty and we can create the duty plan for particular nurse. 
7) Services:
In this module we have to fill up the form and send the request to laboratory test. Here
we can also see the pending request. We can also search the particular patient and view
the laboratory information of particular patient.
 Type of laboratories: -
• Medical Lab,
• Pathological Lab,
• Bacteriological Lab,
• Blood Bank.
• Bill Management
• Department Management
Software Requirements
 Computer software is a set of programs, procedures, functions, associated
data and/or its documentation, if any. Program software performs the function of the
program it implements, either by directly providing instructions to the digital
electronics or by serving as an input to another piece of software.
 IDE Tool : Net beans 7.2.1.
 Backend kit : Java 1.8
 Frontend : html,css,jsp
 Database : SQLyog
 
 Java Database Connectivity Steps:-
 Before you can make a java jdbc association with the database, you should first
import the java.sql package.
• Loading a database driver,(Ex Class.forName(”sun.jdbc.odbc.JdbcOdbcDriver”);)
• Establishing the Connection
(Ex. Connection con=DriverManager.getConnection (“url”,”username”,”password”))
• Create a JDBC Statement Object (Ex. Statement statement = con.createStatement ();)
• Executing the Statement (Ex. Statement.executeUpdate())
• Close JDBC Objects (Ex. Statement.close(),rs.close(),con.close()# Health-Management-system
