#Vote App API Specification
##HTML page
- Method: GET
- Path: /
- Reponse: home page HTML
----
> New Topic
- Method: GET
- Path: /new
- Response: New Topic HTML
----
> Vote Topic Page
- Method: Get
- Path: /topic/<topic_id>
	- variable: topic_id
- Response: Vote topic HTML

##API
> Add new topic
- Method: POST
- Path: /newTopic
- Request:
	- body
	```json
	{
	"name":"string"
	}
	```

- Response: home page with update topic list
----
> Add choice to the topic
> Path: /topic/<topic_id>/mewChoice
	- variable: topic_id
- Requet:
	- Body
```json
{
"choice":"string"
}
```
> Vote for choice in topic



> Written with [StackEdit](https://stackedit.io/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM2NTA0NTk5OF19
-->