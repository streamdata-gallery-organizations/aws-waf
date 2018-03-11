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
  /?Action=CreateSqlInjectionMatchSet&k=1:
    get:
      summary: ' Create Sql Injection Match Set '
      description: 'Service: AWS WAFCreates a'
      operationId: createSqlInjectionMatchSet
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: Name
        description: A friendly name or description for the SqlInjectionMatchSet that
          you're creating
        type: string
      responses:
        200:
          description: OK
      tags:
      - sql injection match set
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