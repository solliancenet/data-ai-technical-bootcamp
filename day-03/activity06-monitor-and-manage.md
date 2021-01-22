# Activity 06: Monitor & Manage

## Audience Poll 1

Q: You want to use a UI to review the assigned workload group and importance for a running SQL query. Which option should you use (pick only one)?

A) Log Analytics

B) Monitoring Hub SQL requests

C) Query the `sys.dm_pdw_exec_requests` DMV

## Audience Poll 2

Q: What information is NOT provided when querying the `sys.dm_pdw_exec_requests` DMV (pick only one)?

A) Count of sessions by user

B) Queued, active or complete queries

C) Query command text

## Audience Poll 3

Q: which of these can you not monitor directly from the Monitor hub (pick only one)?

A) Pipeline Runs

B) SQL request

C) Notebook executions

## Audience Poll 4

Q: How do users release Spark resources used by their notebook (pick only one)?

A) Stop any cells running in the notebook

B) Publish the notebook

C) Close the notebook in Studio

## Audience Poll 5

Q: Which of the following requests will have the highest priority in executing (pick only one)?

A) A user with high importance

B) A role with high importance

C) A role with a resource class of `largerc`

## Audience Poll 6

Q: The customer is claiming that they are running multiple requests in a single session, but getting different classification results, is this possible (pick only one)?

A) Yes

B) No

## Audience Poll 7

Q: The customer is observing that critical requests that involve a high degree of locking scheduled first are being pre-emptied by other query requests. How can the fix this (pick only one)?

A) It cannot be controlled

B) Assign the query requests to a user with normal importance

C) Assign the locking requests to a user with above_normal or high importance


