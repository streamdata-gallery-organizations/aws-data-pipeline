---
name: AWS Data Pipeline
x-slug: aws-data-pipeline
description: AWS Data Pipeline is a web service that helps you reliably process and
  move data between different AWS compute and storage services, as well as on-premise
  data sources, at specified intervals. With AWS Data Pipeline, you can regularly
  access your data where it&rsquo;s stored, transform and process it at scale, and
  efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS,
  Amazon DynamoDB, and Amazon EMR.AWS Data Pipeline helps you easily create complex
  data processing workloads that are fault tolerant, repeatable, and highly available.
  You don&rsquo;t have to worry about ensuring resource availability, managing inter-task
  dependencies, retrying transient failures or timeouts in individual tasks, or creating
  a failure notification system. AWS Data Pipeline also allows you to move and process
  data that was previously locked up in on-premise data silos.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS Data Pipeline
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Data Pipeline API Activate Pipeline
  x-api-slug: aws-data-pipeline-api
  description: Validates the specified pipeline and starts processing pipeline tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=ActivatePipeline
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionactivatepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionactivatepipeline-get-openapi.md
- name: AWS Data Pipeline API Add Tags
  x-api-slug: aws-data-pipeline-api
  description: Adds or modifies tags for the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=AddTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionaddtags-get-openapi.md
- name: AWS Data Pipeline API Create Pipeline
  x-api-slug: aws-data-pipeline-api
  description: Creates a new, empty pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=CreatePipeline
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actioncreatepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actioncreatepipeline-get-openapi.md
- name: AWS Data Pipeline API Deactivate Pipeline
  x-api-slug: aws-data-pipeline-api
  description: Deactivates the specified running pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=DeactivatePipeline
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondeactivatepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondeactivatepipeline-get-openapi.md
- name: AWS Data Pipeline API Delete Pipeline
  x-api-slug: aws-data-pipeline-api
  description: Deletes a pipeline, its pipeline definition, and its run history.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=DeletePipeline
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondeletepipeline-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondeletepipeline-get-openapi.md
- name: AWS Data Pipeline API Describe Objects
  x-api-slug: aws-data-pipeline-api
  description: Gets the object definitions for a set of objects associated with the
    pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=DescribeObjects
  tags: Objects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondescribeobjects-get-openapi.md
- name: AWS Data Pipeline API Describe Pipelines
  x-api-slug: aws-data-pipeline-api
  description: Retrieves metadata about one or more pipelines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=DescribePipelines
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondescribepipelines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiondescribepipelines-get-openapi.md
- name: AWS Data Pipeline API Evaluate Expression
  x-api-slug: aws-data-pipeline-api
  description: Task runners call EvaluateExpression to evaluate a string in the context
    of the specified object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=EvaluateExpression
  tags: Expressions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionevaluateexpression-get-openapi.md
- name: AWS Data Pipeline API Get Pipeline Definition
  x-api-slug: aws-data-pipeline-api
  description: Gets the definition of the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=GetPipelineDefinition
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiongetpipelinedefinition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actiongetpipelinedefinition-get-openapi.md
- name: AWS Data Pipeline API List Pipelines
  x-api-slug: aws-data-pipeline-api
  description: Lists the pipeline identifiers for all active pipelines that you have
    permission to access.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=ListPipelines
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionlistpipelines-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionlistpipelines-get-openapi.md
- name: AWS Data Pipeline API Poll For Task
  x-api-slug: aws-data-pipeline-api
  description: Task runners call PollForTask to receive a task to perform from AWS
    Data Pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=PollForTask
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionpollfortask-get-openapi.md
- name: AWS Data Pipeline API Put Pipeline Definition
  x-api-slug: aws-data-pipeline-api
  description: Adds tasks, schedules, and preconditions to the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=PutPipelineDefinition
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionputpipelinedefinition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionputpipelinedefinition-get-openapi.md
- name: AWS Data Pipeline API Query Objects
  x-api-slug: aws-data-pipeline-api
  description: Queries the specified pipeline for the names of objects that match
    the specified set of conditions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=QueryObjects
  tags: Objects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionqueryobjects-get-openapi.md
- name: AWS Data Pipeline API Remove Tags
  x-api-slug: aws-data-pipeline-api
  description: Removes existing tags from the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=RemoveTags
  tags: Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionremovetags-get-openapi.md
- name: AWS Data Pipeline API Report Task Progress
  x-api-slug: aws-data-pipeline-api
  description: Task runners call ReportTaskProgress when assigned a task to acknowledge
    that it has the task.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=ReportTaskProgress
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionreporttaskprogress-get-openapi.md
- name: AWS Data Pipeline API Report Task Runner Heartbeat
  x-api-slug: aws-data-pipeline-api
  description: Task runners call ReportTaskRunnerHeartbeat every 15 minutes to indicate
    that they are operational.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=ReportTaskRunnerHeartbeat
  tags: Task Runner Hearbeat
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionreporttaskrunnerheartbeat-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionreporttaskrunnerheartbeat-get-openapi.md
- name: AWS Data Pipeline API Set Status
  x-api-slug: aws-data-pipeline-api
  description: Requests that the status of the specified physical or logical pipeline
    objects be updated in the specified pipeline.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=SetStatus
  tags: Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionsetstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionsetstatus-get-openapi.md
- name: AWS Data Pipeline API Set Task Status
  x-api-slug: aws-data-pipeline-api
  description: Task runners call SetTaskStatus to notify AWS Data Pipeline that a
    task is completed and provide information about the final status.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=SetTaskStatus
  tags: Tasks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionsettaskstatus-get-openapi.md
- name: AWS Data Pipeline API Validate Pipeline Definition
  x-api-slug: aws-data-pipeline-api
  description: Validates the specified pipeline definition to ensure that it is well
    formed and can be run without error.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: ://///?Action=ValidatePipelineDefinition
  tags: Pipeline
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionvalidatepipelinedefinition-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/actionvalidatepipelinedefinition-get-openapi.md
- name: AWS Data Pipeline API
  x-api-slug: aws-data-pipeline-api
  description: AWS Data Pipeline is a web service that helps you reliably process
    and move data between different AWS compute and storage services, as well as on-premise
    data sources, at specified intervals. With AWS Data Pipeline, you can regularly
    access your data where it&rsquo;s stored, transform and process it at scale, and
    efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS,
    Amazon DynamoDB, and Amazon EMR.AWS Data Pipeline helps you easily create complex
    data processing workloads that are fault tolerant, repeatable, and highly available.
    You don&rsquo;t have to worry about ensuring resource availability, managing inter-task
    dependencies, retrying transient failures or timeouts in individual tasks, or
    creating a failure notification system. AWS Data Pipeline also allows you to move
    and process data that was previously locked up in on-premise data silos.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Analytics_AWSDataPipeline.png
  humanURL: https://aws.amazon.com/datapipeline/
  baseURL: :///
  tags: AWS Data Pipeline
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-data-pipeline/master/_listings/aws-data-pipeline/openapi.md
x-common:
- type: x-blog
  url: http://blogs.aws.amazon.com/bigdata
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Data-Pipeline/
- type: x-documentation
  url: http://docs.aws.amazon.com/datapipeline/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/datapipeline/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=151
- type: x-pricing
  url: https://aws.amazon.com/datapipeline/pricing/
- type: x-tools
  url: http://aws.amazon.com/developertools/AWS-Data-Pipeline/
- type: x-website
  url: https://aws.amazon.com/datapipeline/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---