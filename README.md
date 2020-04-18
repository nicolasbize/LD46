# LD46 - Keep it alive

## Game idea

You are a surgeon wannabe who takes a flight when the speakerphone asks for a doctor to respond to an emergency as someone is having a heart attack.
Luckily for him, you brought your "Surgeon for dummy" kit which includes an instruction booklet and a few surgery tools. On the patient you find a blood card, an ID card and a passport. The patient also has physical traits like eye colors, hair color, etc. which come into play.
Throughout the flight (5 min gameplay) things will be happening to the patient, requiring you to combine the different clues to perform the correct surgery procedures and help you keep it alive!

Replayability comes from different patient characteristics, random events.

Inspired from "Keep calm and nobody explodes" + "papers please"

### Driver license information

[DOB]
[Signs]: like corrective lenses, tatoo, scar
[Sex]:
[Height]:
[Hair]:
[Eyes]:
[Weight]:

### Passport information

[Country issuance]:
[Last countries visited]:

### Donor card

Blood Type: O-/O+/A-/A+/B-/B+/AB-/AB+
[Allergies]:

### Medical letter

List of procedures had in the past

### Patient symptoms

Temperature (with thermometer)
Pressure (with blood pressure cuff)
Heart rate (rate counter)
Breathing rate (rate counter)

### Procedures

Body targets: arms/legs/head
Tools: hand, knife, seringe, cup, compress
Pills: allergen, flu vaccine, aspirin, antivomit
Serums: [colors]
Water: [temperature] + [quantity]

### Instruction booklet

Vital signs section

        | temp H | temp L | pres H | pres L | HR H | HR L | BR H | BR L |
temp H  |
temp L  |  => illness table
pres H  |  allergy, cold, flu, pinkeye, diarrhea, headache
pres L  |  nausea, fever, diabetes, asthma
HR   H  |
HR   L  |
BR   H  |
BR   L  |

Illness section

Allergy:
Create allergy shot:
- 2 allergen pills
- if surgery past 6 months, add [blue]
- if blood type negative, add [red]
- if woman, add [yellow]
- dilute with water
- shoot according to age+bodypart table

Cold:
Create compress:
- take compress
- dilute with water
- bring to temperature: patient temp + compress temp == 200
- if dark hair: increase by 20 degrees
- apply compress to head if adult, arms if children

Note: if patient originates from southern hemisphere, NEVER use a compress. Do an incision instead. By default, legs are a good place.

Flu:
- Same as allergy shot but:
- use flu vaccine.
- only dilute with half the water.
- add 20 years to patient age if they have light eyes

Pinkeye:
- if patient has history of allergy, slap on arms
- otherwise cut a leg (I hear it helps)

Diarrhea:
- if patient visited asia or europe in the past 3 months, then double the proportions that follow:
- take cup
- each diarrhea pill contains 200mg of concentrated banana
- table for age: 200, 400, 600, 800, 1000mg
- dilute with water
- have patient drink

Note: if patient is originally from asia or woman, then disregard the first note about doubling the proportions.

Headache:
- Same age table as Diarrhea but:
- Use aspirin pills (100mg each)
- Dilute with water
- Inject treatment instead of drinking:
- Inject in head by default, unless surgery past 3 months. Inject in legs.

Nausea:
- take cup
- add a certain number of antivomit drug pills
- dilute with water
- have patient drink

Fever:
- same as headache but only use 100ml of water for dilution
- if tattoos, use compress on arms instead of drinking

Diabetes:
- combine pills from diarrhea and fever
- dilute with water
- drink
- if patient's age is an even number it may be better to just slap them on the arm

Asthma:
- asthma is a fake illness. A simple slap in the face might do.
- unless they are male, in which case dilute some aspirin pills and have them drink it.
- if they are female do the same as for males but inject in the arm.


Origin
------
These rules take precedence over everything else in the manual:
Europe: all slaps must be done in the face
Africa: all incisions must be done in arms
America: all shots must be given in the legs

Sex
---
Whenever a shot or incision must be made:
If woman, prefer the right leg or arm
If man, use the left leg or arm

Water dilution
--------------
table height+weight for quantity

Drug quantity
-------------
In case it is not mentioned, use the following table and say a prayer:
zodiac signs: # of pills



================

