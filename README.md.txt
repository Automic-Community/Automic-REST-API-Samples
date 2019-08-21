Automic REST API Samples
========================
The attachment contains the sample codes and the required automic objects

Endpoint to execute the objects:	*http://{ipaddress}:{port}/ae/api/{client_id}/executions/*

Endpoint to restart the object:		*http://{ipaddress}:{port}/ae/api/{client_id}/executions/{run_id}/status*

The sample codes can be executed from any software that can handle the REST codes

All the objects that are being accessed by the REST calls should have the attribute setting "Generate at runtime".

Below is the short description for the attached code snippets

Basic_Execute : To execute an object with an alias
Basic_PromptInput_Execute : Execute an object by passing prompt values
Basic_Restart : Minimal restart of an object [*RunId need to provided in the endpoint*]
Execute_once_with_logical_date : Pass the logical date as input value and execute the object
Execute_once_with_specific_start_time : Execute an object at a specific time
Execute_once_with_WaitForManualRelease : Execute an object and it should wait for manual release
Execute_Recurring_Basic : Simple recurring execution for n number of times
Execute_Recurring_with_Between_Start_End_Time : Execute an object recurringly during specific date and time
Execute_Recurring_with_Execute_At : Execute an object at a specific time during certain period
Execute_Recurring_with_Start_End_Date : Execute an object for every certain time during certain period

