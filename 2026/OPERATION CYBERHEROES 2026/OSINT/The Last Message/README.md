# The Last Message

- **Category:** OSINT

## Challenge Description

> My wife had overtime today, so she went back home later than usual.
> 
> She only sent me this photo and said, "I'm here now."
> 
> I was already half asleep, so I got confused and could not figure out exactly where she was.
> 
> Can you help me identify the station where this photo was taken?
> 
> Flag Format:
> OPUCC{Train_Name_Station_Name}

## Analysis
### Step 1: Analyze the image
I first looked at the obvious details in the photograph:
- Station sign
- Platform number
- Destination board listing:
  - Salak Tinggi
  - KLIA
  - KLIA2
- Train line logo (KLIA Transit)

These clues suggested that the station belonged to the **KLIA Transit** railway line.


### Step 2: Searched KLIA Transit route

Since the train was heading towards **Salak Tinggi**, **KLIA**, and **KLIA2**, the station had to be located **before Salak Tinggi** on the KLIA Transit route.


<img width="647" height="474" alt="image" src="https://github.com/user-attachments/assets/d8707df3-cd0f-496a-9b2e-9e6cc39fa252" />

Putrajaya & Cyberjaya is the station before Salak Tinggi

### Step 3: Construct the Flag

From the evidence:

- **Train Name:** KLIA Transit
- **Station Name:** Putrajaya & Cyberjaya

Therefore, the flag is:

```text
OPUCC{KLIA_Transit_Putrajaya_Cyberjaya}
```

---


