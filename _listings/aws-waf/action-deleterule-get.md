---
swagger: "2.0"
info:
  title: AWS WAF API Delete Rule
  version: 1.0.0
  description: 'Service: AWS WAFPermanently deletes a.'
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteRule:
    get:
      summary: ' Delete Rule '
      description: 'Service: AWS WAFPermanently deletes a'
      operationId: deleteRule
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: RuleId
        description: The RuleId of the Rule that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - rules
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