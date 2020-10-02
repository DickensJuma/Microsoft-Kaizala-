# Database Schema

Online [API](https://health-form1.herokuapp.com/)

## Installation



```bash


git clone https://github.com/DickensJuma/fleet-management

npm install
npm run dev

http://localhost:3000 ## Hello Driver
http://localhost:3000/register
http://localhost:3000/start
http://localhost:3000/servicing
http://localhost:3000/incident
http://localhost:3000/accident
http://localhost:3000/mirrors-check
http://localhost:3000/fueling
http://localhost:3000/engine-check
http://localhost:3000/electrical-check 



```

## Post

```python
#register
 {
       
        "registration": "KBC123R",
        "current_odometer_reading": 200,
        "date": "2020-09-03T21:00:00.000Z",
        "location": "winam"
       
    }

    {
    "registration": "KBC123V"
}

#servicing
{
    "registration": "KBC1290L",
    "current_odometer_reading": 900,
     "service_due_date": "2020-02-03",
     "garage":"Auto Express",
      "parts_needed":"engine oil",
     "comments":"it needs servicing",
     "date": "2020-02-03",
    "location": "eldoret"
}

#accident
{
    "registration": "KBC123V",
    "extend_of_damage": "mild",
    "comments": "The damage was mild",
    "date": "09/4/2020",
    "location": "winam"
}

#fueling
{
     "fuel_station": "shell",
    "cost": 2000,
    "linter": "perfect",
    "registration": "KMW291X",
    "date": "02/3/2010",
    "location": "kisumu"
}

#incident
{

"incident_type": "Collusion head on",
"registration": "KRO120X",
"date": "2020-03-08",
"location": "kitale",

}

#electrical-check
{  
    "registration": "KRO120X",
    "oil_level":"good",
     "radiator_fluid":"good",
      "clutch_brake_fluid": "good",
      "fan_belt_tightness": "good",
      "exhaust_pipe":"faulty",
      "fueltank_cap_leaks": "good",
      "comment": "should be serviced again"
}


#engine-check
{
      "registration": "KAM124V",
      "oil_level":"good",
      "radiator_fluid":"good",
      "clutch_brake_fluid": "good",
      "fan_belt_tightness":"good",
      "exhaust_pipe":"faulty",
      "fueltank_cap_leaks": "good",
      "comment": "good"
    }

    #mirrors-check
    {
        "registration":"KEN1233B",
         "windscreen":"good",
        "sidemirrors": "good:,
        "rear_view_mirrors":"good",
         "comment":"good condition"

     }