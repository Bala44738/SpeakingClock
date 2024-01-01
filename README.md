Speaking clock
Specification ------

Given a 24-hour clock convert the current time into words e.g. "08:34" should be converted to "It's eight thirty four"
Make another controller to handle input from user in the format “11:25”
Return Midday and Midnight as "It's Midday and "It's Midnight"
Endpoints
Swagger Link :- http://localhost:9090/swagger-ui/index.html#/

Endpoint to convert time into words :- http://localhost:9090/speakingClock/{time}

FOR eg. :- http://localhost:9090/speakingClock/07:25

Endpoint to tell It is Mid-day, Mid-night or none :- http://localhost:9090/speakingClock/dayType/{time}

For eg. :- http://localhost:9090/speakingClock/dayType/01:33
