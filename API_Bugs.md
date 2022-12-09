# API Bugs
This file contains various bugs discovered on API endpoints which were verified by using Postman tool. These bugs are related to Happy Flow, Negative Flow and Other Flows.


------



## :one: Current Weather Data by city name on https://openweathermap.org/current#name :arrow_down:



### :exclamation::bug: Romanian language does not work uniformlly on all values of the parameters :fast_forward:
![23](https://user-images.githubusercontent.com/115346533/206691438-b93adccc-4963-42dc-8943-a485a3822998.jpg)


------



## :two: Call 5 day / 3 hour forecast data by city name on https://openweathermap.org/forecast5#name5 :arrow_down:



### :exclamation::bug: It is allowed to write city name with space :fast_forward:
![24](https://user-images.githubusercontent.com/115346533/206692275-f38e132a-aaf6-4e4a-82db-0c320a5ba2c1.jpg)

#



### :exclamation::bug: It is allowed to write negative number for "cnt" parameter :fast_forward:
![25](https://user-images.githubusercontent.com/115346533/206693372-dc16495c-6254-436a-a758-cb6c332d45f1.jpg)

#



### :exclamation::bug: It is allowed to write "CNt" instead of "cnt" and the response is valid :fast_forward:
![26](https://user-images.githubusercontent.com/115346533/206694484-7dfa13b1-9838-4d37-b710-5d34d10a8c9e.jpg)

#



### :exclamation::bug: City name is not translated in Chinese language :fast_forward:
![27](https://user-images.githubusercontent.com/115346533/206695035-ce101ac8-8814-418c-af20-c14a251cea61.jpg)

#



### :exclamation::bug: The endpoint works with an inactive API key :fast_forward:
![28](https://user-images.githubusercontent.com/115346533/206695428-a7a1612b-ca12-4efd-9094-1eb5236f0f41.jpg)


------



## :three: API CRUD on https://qachallenge.ro/api/ for CRUD operations (create, read, update, delete) :arrow_down:



### :exclamation::bug: The value of id key can be written with symbols / special characters :fast_forward:
![29](https://user-images.githubusercontent.com/115346533/206696603-e448d682-190d-4178-9bee-44853a50a990.jpg)

#



### :exclamation::bug: The key names could be written with spaces at beginning :fast_forward:
![30](https://user-images.githubusercontent.com/115346533/206698828-6d2a55da-0901-4867-aa60-60833d4456e3.jpg)

#



### :exclamation::bug: The value of the id could be written as decimal number :fast_forward:
![31](https://user-images.githubusercontent.com/115346533/206699563-b48b80df-885e-4ded-a79c-7b8a1eaab86c.jpg)

#



### :exclamation::bug: The value of the id could be written in various and inadequate ways (eg. "270+266=536") :fast_forward:
![32](https://user-images.githubusercontent.com/115346533/206700406-2a168c1c-2fc0-42e1-8329-8483a1bd803a.jpg)

#



### :exclamation::bug: The value of the id could be written with spaces :fast_forward:
![33](https://user-images.githubusercontent.com/115346533/206701299-1662129e-4390-4f24-9d6a-9efc9fd2e48a.jpg)

#



### :exclamation::bug: It could be written any character after comma or period :fast_forward:
![34](https://user-images.githubusercontent.com/115346533/206701770-ecc8261f-f9e7-4c9e-a3ba-a83cb27d18ab.jpg)

#



### :exclamation::bug: The endpoint works with a non-existent parameter :fast_forward:
![35](https://user-images.githubusercontent.com/115346533/206702078-393f625a-187c-44f0-b75b-eb0a5d530d38.jpg)

#



