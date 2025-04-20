# Patient Information Card

#Patient Details
patient_name = "Ali Rehman"
age = 35
gender = "Male"
blood_group = "O+"
diagnosis = "Hypertension"
medications = ["Losartan", "Hydrochlorothiazide", "Aspirin"]

#Printing Patient Information Card
print("\n=======================")
print("Patient Information Card")
print("--- Patient Details ---")
print("=======================")
print(f"Name: {patient_name}")
print(f"Age: {age}")
print(f"Gender: {gender}")
print(f"Blood Group: {blood_group}")
print(f"Diagnosis: {diagnosis}")
print("Medications: " + " , ".join(medications))