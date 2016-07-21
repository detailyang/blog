

#RESTFUL
Let me talk about something about return code of restul api.

When I would like to design a restful api, the result of api always be `200 OK` previously. But When I as a system admin, I suddenly understand that the HTTP Status Code is the better design. 

Some people including me prefer return the code as following:

````bash

200 OK

{
	code: 0,
	msg: 'ok',
	value: xxxxx
}
````

It looks like ok to me. But when I as a system admin, the HTTP code always be 200 ok on the monitor system. What the fuck, cannot count the HTTP code distribution including 2xx, 3xx, 4xx, 5xx.
