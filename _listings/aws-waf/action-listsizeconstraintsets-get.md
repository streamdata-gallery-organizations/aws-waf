---
swagger: "2.0"
info:
  title: AWS WAF API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListSizeConstraintSets&k=1:
    get:
      summary: ' List Size Constraint Sets '
      description: 'Service: AWS WAFReturns an array of'
      operationId: listSizeConstraintSets
      parameters:
      - in: query
        name: Limit
        description: Specifies the number of SizeConstraintSet objects that you want
          AWS WAF to return for this request
        type: string
      - in: query
        name: NextMarker
        description: "If you specify a value for Limit and you have more SizeConstraintSets
          than the value of Limit, \t\t\tAWS WAF returns a NextMarker value in the
          response that allows you to list another group of SizeConstraintSets"
        type: string
      responses:
        200:
          description: OK
      tags:
      - size constraint sets
definitions: []
x-collection-name: AWS WAF
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