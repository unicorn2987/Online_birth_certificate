# Online_birth_certificate
import datetime

class BirthCertificate:
  def _init_(self, first_name, last_name, date_of_birth, place_of_birth):
    self.first_name = first_name
    self.last_name = last_name
    self.date_of_birth = date_of_birth
    self.place_of_birth = place_of_birth

def apply_online(first_name, last_name, date_of_birth, place_of_birth):
  birth_certificate = BirthCertificate(first_name, last_name, date_of_birth, place_of_birth)
  return birth_certificate

def main():
  first_name = input("Enter your first name: ")
  last_name = input("Enter your last name: ")
  date_of_birth = input("Enter your date of birth (DD/MM/YYYY): ")
  place_of_birth = input("Enter your place of birth: ")
  birth_certificate = apply_online(first_name, last_name, date_of_birth, place_of_birth)
  print("Your birth certificate application has been submitted successfully!")

if _name_ == '_main_':
  main()
