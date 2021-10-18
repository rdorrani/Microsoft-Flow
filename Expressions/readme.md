[![Everything Is AWESOME](http://img.youtube.com/vi/O97IdCbfMQI/maxresdefault.jpg)](https://youtu.be/4eWGdi_C2hQ "Power Automate flow Expressions")
**Click image to view video**

# Power Automate Expressions
## Flow Run Link Expression
concat('https://us.flow.microsoft.com/manage/environments/',
workflow()?['tags']?['environmentName'],
'/flows/',
workflow()?['name'],
'/runs/',
workflow()?['run']['name']
)
