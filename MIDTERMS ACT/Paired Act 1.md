# Midterm Paired Task 1. 
### **Object Oriented Analysis and Design**

1.	Following the OO workflow as discussed in class, you are task to design the OO Model of the given problem (use draw.io) of the scenario below:
   
Problem Statement. Tiny Hospital keeps information on patients and hospital rooms. The system assigns each patient a patient ID number. In addition, the patient’s name and date of birth are recorded. Some patients are resident patients (they spend at least one night in the hospital) and others are outpatients (they are treated and released). Resident patients are assigned to a room. Each room is identified by a room number. The Tiny hospital system also stores the room type (private or semi-private) and room fee. Overtime, each room will have many patients who stay in it. Each resident patient will stay in only one room. The hospital system has features that can view patient information and view whether a room is occupied or not. Both patient and room entities must have features that allows adding, updating and searching of records.

STEP1. IDENTIFY all the necessary OBJECT within the problem domain
•	Patient
•	ResPatient
•	OutPatient
•	HosRoom
•	HosFlow

STEP 2. IDENTIFY all the properties and methods/behaviors in the problem statement.
Patient
	patientID
	name
	dateOfBirth
	patientType
Behavior
	addPatient()
	updatePatient()
	searchPatientinfo()
	getPatientinfo()
ResPatient
	roompatient
	assignRoom()
OutPatient
	discharge()
HosRoom
	roomNumber
	roomType
	roomFee
	occupied
	assignPatient()
	releasePatient()
	isOccupied
HosFlow
	patientList
	roomList
	addPatient()
	updatePatient()
	searchPatient()
	viewPatient()
	viewRstat()

