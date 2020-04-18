# service-health

create keys 

SET services:ms1:1 healthy EX 60
SET services:ms1:2 healthy EX 60 
SET services:ms1:3 healthy EX 60 

check keys 

KEYS services:ms1* 
