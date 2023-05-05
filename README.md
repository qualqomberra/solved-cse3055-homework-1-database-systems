Download Link: https://assignmentchef.com/product/solved-cse3055-homework-1-database-systems
<br>
Homework #1

1) Match the following terms to the appropriate definitions

a) Whether an instance of a supertype must also be amember of at least one subtype_____ disjointness constraintb) contains two (or more) attributes_____ weak entityc) Depends on the existence of another entity type_____ attributed) Property of an entity_____ subtype discriminatore) Whether an instance of a supertype may simultaneously_____ cardinality constraint be a member of two (or more) subtypes_____ degreef) Specifies maximum and minimum number of instances_____ completeness constraint g) Number of participating entity types in relationship_____ identifierh) Uniquely identifies entity instances_____ ternaryi) Relationship of degree 3_____ composite key j) An attribute of the supertype whose values determine thetarget subtype(s)

2) The Prescriptions-R-X chain of pharmacies has offered to give you a free lifetime supply of medicine if you design its database. Given the rising cost of health care, you agree. Here’s the information that you gather:• Patients are identified by an SSN, and their names, addresses, birthdate, and ages must be recorded.• Doctors are identified by an SSN. For each doctor, the name, specialty, and years of experience must be recorded. Doctors have one or more specialties.• Each pharmaceutical company is identified by name and has a phone number.• For each drug, the trade name and formula must be recorded. Each drug is sold by a given pharmaceutical company, and the trade name identifies a drug uniquely from among the products of that company. If a pharmaceutical company is deleted, you need not keep track of its products any longer.• Each pharmacy has a name, address, and phone number. Address is composed of city, state, and zipcode.• Every patient has a primary physician. Every doctor has at least one patient.• Each pharmacy sells several drugs and has a price for each. A drug could be sold at several pharmacies, and the price could vary from one pharmacy to another.• Doctors prescribe drugs for patients. A doctor could prescribe one or more drugs for several patients, and a patient could obtain prescriptions from several doctors. Each prescription has a date and a quantity associated with it. You can assume that, if a doctor prescribes the same drug for the same patient more than once, only the last such prescription needs to be stored.• Pharmaceutical companies have long-term contracts with pharmacies. A pharmaceutical company can contract with several pharmacies, and a pharmacy can contract with several pharmaceutical companies. For each contract, you have to store a start date, an end date, and the text of the contract.• Pharmacies appoint a supervisor for each contract. There must always be a supervisor for each contract, but the contract supervisor can change over the lifetime of the contract.

a) Draw an ER diagram that captures the preceding information. Identify any constraints not captured by the ER diagram.b) How would your design change if each drug must be sold at a fixed price by all pharmacies?

c) How would your design change if the design requirements change as follows: If a doctor prescribes the same drug for the same patient more than once, several such prescriptions may have to be stored.