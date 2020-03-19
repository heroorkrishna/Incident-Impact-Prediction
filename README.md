# Incident-Impact-Prediction

Data set Details
The dataset is having incidents raised by customers.Which contains an event log of an incident management process extracted from a service desk platform of an IT company

ID

Incident identifier (24,918 different values)

ID_status

Eight levels controlling the incident management process transitions from opening until closing the case

active

Boolean attribute that shows whether the record is active or closed/canceled

count_reassign

Number of times the incident has the group or the support analysts changed

count_opening

Number of times the incident resolution was rejected by the caller

count_updated

Number of incident updates until that moment

ID_caller

Identifier of the user affected

opened_by

Identifier of the user who reported the incident

opened_time

Incident user opening date and time

Created_by

Identifier of the user who registered the incident

created_at

Incident system creation date and time

updated_by

Identifier of the user who updated the incident and generated the current log record

updated_at

Incident system update date and time

type_contact

Categorical attribute that shows by what means the incident was reported

location

Identifier of the location of the place affected

Category Id

First-level description of the affected service

user_symptom

Description of the user perception about service availability

Impact

Description of the impact caused by the incident (values: 1â€“High; 2â€“Medium; 3â€“Low)

Support_group

Identifier of the support group in charge of the incident

support_incharge

Identifier of the user in charge of the incident

Doc_knowledge

Boolean attribute that shows whether a knowledge base document was used to resolve the incident

confirmation_check

Boolean attribute that shows whether the priority field has been double-checked

Notify

Categorical attribute that shows whether notifications were generated for the incident

Problem_id

identifier of the problem associated with the incident

change_request

identifier of the change request associated with the incident

