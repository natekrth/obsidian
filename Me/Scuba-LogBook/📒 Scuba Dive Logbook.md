```dataview
table 
    dive-number as "Dive #",
    date,
    location,
    dive-site as "Dive Site",
    max-depth as "Max Depth",
    bottom-time as "Bottom Time",
    total-time as "Total Time",
    air-in as "Air In (psi/bar)",
    air-out as "Air Out (psi/bar)"
from "Me/Scuba-LogBook"
where contains(tags, "scuba")
sort date asc
```