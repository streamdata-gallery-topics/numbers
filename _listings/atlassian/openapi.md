swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/version/{id}/relatedIssueCounts:
    get:
      summary: Get version's related issues count
      description: |-
        Returns the following counts for a version:

        *   Number of issues where the `fixVersion` is set to the version.
        *   Number of issues where the `affectedVersion` is set to the version.
        *   Number of issues where a version custom field is set to the version.

        [Permissions](https://confluence.atlassian.com/x/FQiiLQ) required: _Browse projects_ project permission
      operationId: com.atlassian.jira.rest.v2.issue.VersionResource.getVersionRelatedIssues_get
      x-api-path-slug: api2versionidrelatedissuecounts-get
      parameters:
      - in: path
        name: id
        description: The ID of the version
      responses:
        200:
          description: OK
      tags:
      - Versions
      - Related
      - Issues
      - Count