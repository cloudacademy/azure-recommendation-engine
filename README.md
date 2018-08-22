# Building a Recommendation Engine on Azure
This file contains URLs and commands from the demos in Cloud Academy's _Building a Recommendation Engine on Azure_ course.  

### Introduction
[Azure Free Trial](https://azure.microsoft.com/free)  

### Deploying and Testing
[Product Recommendations Solution](https://github.com/Microsoft/Product-Recommendations/tree/master/deploy)

User transactions for personalized recommendations:
```
[{"itemId": "DAF-00448",
"eventType": "Purchase",
"timestamp": "2018-08-15T09:05:00"},
{"itemId": "DHF-01333",
"eventType": "Purchase",
"timestamp": "2018-08-14T23:01:00"}]
```

### Making API Requests
```
curl -i -X GET --header 'x-api-key: <Primary Key>' '<Website URL>/api/models/<Model ID>/recommend?itemId=DQF-00248'
```

[API Documentation](https://github.com/Microsoft/Product-Recommendations/blob/master/doc/api-reference.md)

### Conclusion
support@cloudacademy.com
