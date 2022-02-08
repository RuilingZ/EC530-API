Keras is a deep learning API written in Python, running on top of the machine learning platform TensorFlow. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result as fast as possible is key to doing good research.

The Twitter API enables programmatic access to Twitter in unique and advanced ways. Tap into core elements of Twitter like: Tweets, Direct Messages, Spaces, Lists, users, and more.

# The comparation between Twitter API and Keras API

## Entity versus procedural：
Twitter API is an entity based API with the entity: Active Entities, the Active Entities endpoint: POST，GET，etc.
and the parameters contained: account_id, entity, start_time, end_time, etc..
Keras API is an procedure based API. The core data structures of Keras are layers and models. The simplest type of
model is the Sequential model, a linear stack of layers. The basic operation unit is the parameters instead of the 
entities,

## Syntax
Twitter API use json objects to communicate between server and the client or simply different programmes between 
programmes. The object combines data (in the following way) or message about operation like: PUT, POST, GET

"data": {
    "start_time": "2019-03-12T00:00:00Z",
    "segmentation_type": null,
    "url": null,
    "id_str": "1120829647711653888",
    "entity_ids": [
      "el32n"
    ],
    "end_time": "2019-03-20T00:00:00Z",
    "country": null,
    "placement": "ALL_ON_TWITTER",
    "id": 1120829647711653888,
    "expires_at": null,
    "account_id": "18ce54d4x5t",
    "status": "PROCESSING",
    "granularity": "TOTAL",
    "entity": "LINE_ITEM",
    "created_at": "2019-04-23T23:19:46Z",
    "platform": null,
    "updated_at": "2019-04-23T23:19:46Z",
    "metric_groups": [
      "ENGAGEMENT"
    ]
  }
  
  In Keras API, every function has their input and output in diffreent ruled type and amount, function could be imported
  by adding subsidiary APIs and could be called simply by their name and right format of input. All input are just the 
  necessary information to accomplish the function.
  
  ## Status
  In Twitter API, the status is stored in the entities in server and convey base on request or regularly by JSON objects
  according to the operation from client.
  In Keras API, the status of success or fail could be given at each step or the called of the function.
  
  ## Documentation
  Both API gives the guide on functions while twitter give extra introduce on the way of keeping in touch constantly between
  server and client and keras mentioned their promote branch API for more functions many times.
  
  ## Version
  Keras updates a lot more than twitter API. Since it's based on python, all updates or debugging in python will possibly caused the
  versioning of Keras and any problems reported could also leads to a small-change--which is really easy for an open-scource API. 
  While twitter is not only rely less on outer programming enviroment but also is mainly tested by limited professionals.
  
