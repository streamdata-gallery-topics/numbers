---
swagger: "2.0"
x-collection-name: TelAPI
x-complete: 0
info:
  title: hetras Hotel API Version 0 Partially updates a room.
  version: v0
  description: "The hetras API is using this Patch Specification\r\n            to
    partially update an existing resource. Currently this call only allows to modify
    condition and housekeeping occupancy status of the room.\r\n            \r\n            A
    request example:\r\n            [\r\n              {\r\n                \"op\":
    \"replace\", \"path\": \"/status/condition\", \"value\": \"CleanNotInspected\"\r\n
    \             }, {\r\n                \"op\": \"replace\", \"path\": \"/status/housekeeping_occupancy\",
    \"value\": \"Vacant\"\r\n              }\r\n            ]\r\n            \r\n
    \           For more details on how the API responds to errors please check our
    documentation on \r\n            Error Handling."
host: api.hetras-certification.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/hotel/v0/hotels/{hotelId}/rooms/{roomNumber}:
    get:
      summary: Get all the details for a specific room in the hotel.
      description: With this call you can load the details about a specific room in
        the hotel. It will show you the current status of the room.
      operationId: Rooms_GetRoom
      x-api-path-slug: apihotelv0hotelshotelidroomsroomnumber-get
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
        description: The hotel id the room belongs to
      - in: path
        name: roomNumber
        description: The room number you want to see details for
      responses:
        200:
          description: OK
      tags:
      - Detailsa
      - Specific
      - Room
      - In
      - Hotel
    patch:
      summary: Partially updates a room.
      description: "The hetras API is using this Patch Specification\r\n            to
        partially update an existing resource. Currently this call only allows to
        modify condition and housekeeping occupancy status of the room.\r\n            \r\n
        \           A request example:\r\n            [\r\n              {\r\n                \"op\":
        \"replace\", \"path\": \"/status/condition\", \"value\": \"CleanNotInspected\"\r\n
        \             }, {\r\n                \"op\": \"replace\", \"path\": \"/status/housekeeping_occupancy\",
        \"value\": \"Vacant\"\r\n              }\r\n            ]\r\n            \r\n
        \           For more details on how the API responds to errors please check
        our documentation on \r\n            Error Handling."
      operationId: Rooms_PatchRoom
      x-api-path-slug: apihotelv0hotelshotelidroomsroomnumber-patch
      parameters:
      - in: header
        name: App-Id
        description: Application identifier
      - in: header
        name: App-Key
        description: Application key
      - in: path
        name: hotelId
        description: The hotel id the room belongs to
      - in: body
        name: patchRequest
        description: A set of JSON Patch operations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: roomNumber
        description: The room number of the room you would like to update
      responses:
        200:
          description: OK
      tags:
      - Partially
      - Updates
      - Room
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---