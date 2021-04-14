# Day 38 - Week 11
## C-Sharp Week 2

## What is the difference between a primary key and a foreign key
A Primary Key is the main key within the project or file that you want to target as the accessibility point. While the Foreign Key is a accessibility point brought into a new file that represents a piece of data from another non-local file. 
## What is an Alias?
An Alias is a name for data that represents the data but is not the original naming convention created.
## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

internal IEnumerable<Doctor> GetAll()
{
    string sql = @"
    SELECT
    doc.*,
    pat.*
    FROM doctors doc
    JOIN patients pat ON doc.id = pat.id";

    return _db.Query<Doctor, Patient, Doctor>(sql, (doctor, patient) => 
    {
        return doctor;
    }, splitOn: "id");
}

### CREATE TABLE doctors (
  ### id INT NOT NULL AUTO_INCREMENT,
  ### -- CODE OMITTED
  ### PRIMARY KEY (id)
)

### CREATE TABLE patients (
  ### id INT NOT NULL AUTO_INCREMENT,
  ### -- CODE OMITTED
  ### PRIMARY KEY (id)
)

### CREATE TABLE doctors (
 ###  id INT NOT NULL AUTO_INCREMENT,
  ### doctorId INT NOT NULL,
  ### patientId INT NOT NULL,

  ### FOREIGN KEY (doctorId)
  ### REFERENCES doctors(id),
  ### FOREIGN KEY (patientId)
  ### REFERENCES patients(id),
)