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



### :exclamation::bug: Any character could be written after comma or period :fast_forward:
![34](https://user-images.githubusercontent.com/115346533/206701770-ecc8261f-f9e7-4c9e-a3ba-a83cb27d18ab.jpg)

#



### :exclamation::bug: The endpoint works with a non-existent parameter :fast_forward:
![35](https://user-images.githubusercontent.com/115346533/206702078-393f625a-187c-44f0-b75b-eb0a5d530d38.jpg)

#



### :exclamation::bug: New user could be create without any name :fast_forward:
![36](https://user-images.githubusercontent.com/115346533/206850254-b50c5e3c-706f-4750-a8f1-1251db1134da.jpg)

#



### :exclamation::bug: The error message is not clear enough for user :fast_forward:
![37](https://user-images.githubusercontent.com/115346533/206850599-5edf48d2-6557-4c5c-b63a-5cc30b4733a5.jpg)

#



### :exclamation::bug: The last_name parameter has a 10 characters limit :fast_forward:
![38](https://user-images.githubusercontent.com/115346533/206850760-2aeb60ba-0328-45ab-abad-4e1e3c0e49ae.jpg)

#



### :exclamation::bug: The first_name parameter has a 10 characters limit :fast_forward:
![39](https://user-images.githubusercontent.com/115346533/206850934-cfa89def-47a2-47b7-a8e4-bc7e84c96fb9.jpg)

#



### :exclamation::bug: Both names in the first_name value :fast_forward:
![40](https://user-images.githubusercontent.com/115346533/206851040-952ad435-af01-402b-a457-6c794e4f76f4.jpg)

#



### :exclamation::bug: Update an id which does not exist :fast_forward:
![41](https://user-images.githubusercontent.com/115346533/206851177-728bad22-2462-420a-8541-d89c21903334.jpg)

#



### :exclamation::bug: Update the names with any type of characters :fast_forward:
![42](https://user-images.githubusercontent.com/115346533/206851288-6ed43b69-6a69-42c6-b973-e3068250aaa0.jpg)

#



### :exclamation::bug: The id could be updated successfully without any value :fast_forward:
![43](https://user-images.githubusercontent.com/115346533/206851339-40a92ea3-cb7f-4437-9fa4-e3f284423d1b.jpg)

#



### :exclamation::bug: Update successfully with no parameters values :fast_forward:
![44](https://user-images.githubusercontent.com/115346533/206851426-cd076fa7-8a2a-4e60-b7a2-7e2a64a5bbca.jpg)

#



### :exclamation::bug: Id value written with symbols, not numbers :fast_forward:
![45](https://user-images.githubusercontent.com/115346533/206851476-8be86a32-8aff-4875-99fe-5340a72f7145.jpg)

#



### :exclamation::bug: The endpoint works with non-existing parameters :fast_forward:
![46](https://user-images.githubusercontent.com/115346533/206851773-6bc0b0d9-27c2-4a49-b45f-f31865c56822.jpg)

#



### :exclamation::bug: "Success" message with wrong id value :fast_forward:
![47](https://user-images.githubusercontent.com/115346533/206851936-6ba30d1e-4025-4fab-ab14-9b3148ef01ae.jpg)

#



### :exclamation::bug: "Success" message with no id value :fast_forward:
![48](https://user-images.githubusercontent.com/115346533/206852006-979f4932-904f-4eef-9ca5-a2867b03da5e.jpg)

#



### :exclamation::bug: "Success" message with wrong written key and value :fast_forward:
![49](https://user-images.githubusercontent.com/115346533/206852061-98408ea2-0911-4deb-8e03-39a4ef8aa15b.jpg)

#



### :exclamation::bug: "Success" message without id key :fast_forward:
![50](https://user-images.githubusercontent.com/115346533/206852103-d39b08aa-0e7f-4ac6-b107-5d62c077609c.jpg)


------



## :four: The Open Movie Database API on https://www.omdbapi.com/ :arrow_down:



### :exclamation::bug: Return a valid result with a title and a different IMDb ID :fast_forward:
![51](https://user-images.githubusercontent.com/115346533/206852488-384006d1-fcfa-430d-a6f7-ad069b39ea45.jpg)

#



### :exclamation::bug: Wrong message error (the parameter is incorrect, not IMDb ID) :fast_forward:
![52](https://user-images.githubusercontent.com/115346533/206852595-7272ad6a-461f-4cf8-89ef-b56f0ada21cb.jpg)

#



### :exclamation::bug: Parameter "y" (year) is written wrong, but valid result :fast_forward:
![53](https://user-images.githubusercontent.com/115346533/206852656-d13f013a-a2dc-4ed4-8c0e-68b634c9dea7.jpg)

#



### :exclamation::bug: Wrong message error (parameter "s" is written incorrect, not the ID) :fast_forward:
![54](https://user-images.githubusercontent.com/115346533/206852884-04d35442-c7bd-4031-a4fb-0d44fa428561.jpg)

#



### :exclamation::bug: Valid result with "plot" key written wrong :fast_forward:
![55](https://user-images.githubusercontent.com/115346533/206853280-35412044-2918-4e9c-b095-bd6bc79b8d4b.jpg)

#



### :exclamation::bug: Valid result with "plot" value written incorrect :fast_forward:
![56](https://user-images.githubusercontent.com/115346533/206853339-4400a2ca-ba70-409f-99f8-2a8a652c612f.jpg)

#



### :exclamation::bug: Incorrect error message + do not return an existent result :fast_forward:
![57](https://user-images.githubusercontent.com/115346533/206853456-a7b1a44e-ae03-4bc3-b1fd-1f2cc68072f0.jpg)

#



### :exclamation::bug: The error message is not detailed and inconsistent :fast_forward:
![58](https://user-images.githubusercontent.com/115346533/206853556-3a2deb4c-de4e-406c-b136-d84acd212690.jpg)

#



### :exclamation::bug: Without an ID, it is returned an unclear error message :fast_forward:
![59](https://user-images.githubusercontent.com/115346533/206853973-b66a53c1-b931-433b-9a66-806b2d9cb5b2.jpg)


------



## :five: News API on https://www.newsapi.ai/documentation?tab=searchArticles :arrow_down:



### :exclamation::bug: The "resultType" key written wrong, but correct response :fast_forward:
![60](https://user-images.githubusercontent.com/115346533/206859261-ed4f83fb-c693-41ee-b692-8e41092418cd.jpg)

#



### :exclamation::bug: Incorrect error message for "apiKey" key which is written wrong :fast_forward:
![61](https://user-images.githubusercontent.com/115346533/206859327-3422f811-2974-48e1-af43-9731188b04a5.jpg)

#



### :exclamation::bug: Inappropriate error message for negative value of "articlesCount" :fast_forward:
![62](https://user-images.githubusercontent.com/115346533/206859380-ea224ce6-e539-456b-84b1-ad5022bc6554.jpg)

#



### :exclamation::bug: Correct response with incorrect value of "includeArticleBody" :fast_forward:
![63](https://user-images.githubusercontent.com/115346533/206859452-e4b54850-16c2-4c8e-bcd6-4fd546fa8620.jpg)

#



### :exclamation::bug: Correct response with incorrect value of "includeArticleTitle" :fast_forward:
![64](https://user-images.githubusercontent.com/115346533/206859582-10055455-e03c-4c31-95f2-145a90ec5101.jpg)

#



### :exclamation::bug: "Fasle" has the same correct result as "false" value :fast_forward:
![65](https://user-images.githubusercontent.com/115346533/206859711-8f4dc3fb-b846-42e6-8b72-2ba2cba82040.jpg)

#



### :exclamation::bug: The default value of "includeArticleAuthors" is false, not true, as in docs :fast_forward:
![66](https://user-images.githubusercontent.com/115346533/206859780-1911f701-6dff-4731-8919-0616bbf9b982.jpg)

#



### :exclamation::bug: The default value of "includeArticleBody" is false, not true, as in docs :fast_forward:
![67](https://user-images.githubusercontent.com/115346533/206859840-0e4b4ab3-fdaa-4d70-95ee-a71ef5c75a43.jpg)

#



### :exclamation::bug: The default value of "includeArticleImage" is false, not true, as in docs :fast_forward:
![68](https://user-images.githubusercontent.com/115346533/206859908-c08fe7cb-56f8-4aac-a399-9ed4d3001e30.jpg)

#



### :exclamation::bug: Correct response when is written "includearticleimage", not "includeArticleImage" :fast_forward:
![69](https://user-images.githubusercontent.com/115346533/206859971-c4aea331-80e0-4be3-ac92-3924c5210214.jpg)

#



### :exclamation::bug: The key "articlesCount" returns correct results as "articlescount" :fast_forward:
![70](https://user-images.githubusercontent.com/115346533/206860051-1163aea4-c9a2-4fd8-841f-e73ecfab12ad.jpg)


------



## :six: Chuck Norris Jokes API on https://api.chucknorris.io/ :arrow_down:



### :exclamation::bug: The endpoint works with parameters which are not mentioned in docs :fast_forward:
![71](https://user-images.githubusercontent.com/115346533/206860578-fa583d83-34e7-4e5e-a07c-cc78791be6ad.jpg)

#



### :exclamation::bug: The link from "icon_url" parameter is not working :fast_forward:
![72](https://user-images.githubusercontent.com/115346533/206860671-1869b237-e8f5-4663-8236-808a4adca2a4.jpg)

#



### :exclamation::bug: Valid response instead of error parameter message :fast_forward:
![73](https://user-images.githubusercontent.com/115346533/206860752-366f3d7a-2313-443f-8a58-ef9a896691e7.jpg)

#



### :exclamation::bug: Valid random response with parameter "category" written wronng :fast_forward:
![74](https://user-images.githubusercontent.com/115346533/206860835-4553bae2-f702-4877-89a8-8d563910fb67.jpg)

#


### :exclamation::bug: Valid response with an inexistent parameter :fast_forward:
![75](https://user-images.githubusercontent.com/115346533/206860877-9e61bbaf-43ed-4790-9431-f27a00161a7b.jpg)

#



### :exclamation::bug: Valid random joke with "query" parameter :fast_forward:
![76](https://user-images.githubusercontent.com/115346533/206860952-e4a40799-2781-41c5-a3ec-ddade4212a4d.jpg)

#



### :exclamation::bug: Normal response with an inexistent parameter :fast_forward:
![77](https://user-images.githubusercontent.com/115346533/206861039-d8e595d9-6670-42a8-b75a-52f0bcc8a8e7.jpg)

#



### :exclamation::bug: No error message for user :fast_forward:
![78](https://user-images.githubusercontent.com/115346533/206861204-1b630db5-ebd9-4783-9e72-326ec1045bb5.jpg)

#



### :exclamation::bug: No error message for a request with no parameter :fast_forward:
![79](https://user-images.githubusercontent.com/115346533/206861214-231e196b-081e-4bf4-9367-8d8b7fc3d648.jpg)


------


