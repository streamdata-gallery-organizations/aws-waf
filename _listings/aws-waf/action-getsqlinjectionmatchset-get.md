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
  /?Action=GetSqlInjectionMatchSet&k=1:
    get:
      summary: ' Get Sql Injection Match Set '
      description: 'Service: AWS WAFReturns the'
      operationId: getSqlInjectionMatchSet
      parameters:
      - in: query
        name: SqlInjectionMatchSetId
        description: The SqlInjectionMatchSetId of the SqlInjectionMatchSet that you
          want to get
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